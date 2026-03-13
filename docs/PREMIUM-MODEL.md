##  Weekly Premium Model

We operate on a strictly **weekly pricing model**
aligned with the weekly payout cycle of
Q-Commerce delivery partners.

| Plan | Weekly Premium | Max Daily Coverage | Target User |
|------|---------------|-------------------|-------------|
| Basic | ₹29/week | ₹300/day | Part-time partners |
| Standard | ₹49/week | ₹600/day | Regular partners |
| Premium | ₹89/week | ₹900/day | Full-time partners |

**Key features of our weekly model:**
- Auto-renews every Monday
- Cancel anytime, no lock-in
- Premium adjusts dynamically based on 
  upcoming weather forecast
- Aligned with Blinkit/Instamart weekly 
  settlement cycles

### How AI Adjusts the Premium

Our Brain.js neural network computes a
**risk multiplier (0.8x – 1.6x)** based on:
```
Input Factors:
├── City historical flood/rain risk score
├── Hyper-local zone waterlogging history
├── Current season risk index
├── Upcoming 7-day weather forecast
├── Partner's personal claim history
├── Average AQI in partner's zone
└── Peak delivery hour overlap with
    historical disruption windows

Output:
└── Personalized weekly premium in ₹
```

**Example:**
> Base Standard Plan = ₹49/week
> Dharavi zone, Mumbai, monsoon season
> Risk multiplier = 1.45x
> Final Premium = ₹49 × 1.45 = **₹71/week**

### Payout Calculation Example
```
Worker:          Raju, Bengaluru, Standard Plan
Daily Average:   ₹600
Trigger:         Heavy Rain (50% payout)
Payout:          ₹600 × 50% = ₹300
Credited to UPI: Within 2 hours 
```

---

##  Parametric Triggers

These 6 automated triggers initiate claims
with **zero human intervention:**

| # | Trigger | Condition | Payout |
|---|---------|-----------|--------|
| 1 | Heavy Rain | Rainfall >35mm/3hrs | 50% daily avg |
| 2 | Extreme Heat | Temperature >43°C | 30% daily avg |
| 3 | Severe Pollution | AQI >400 | 40% daily avg |
| 4 | Flood Alert | Active govt warning | 100% daily avg |
| 5 | Low Visibility | Visibility <500m | 25% daily avg |
| 6 | Civic Disruption | Admin-verified strike | 60% daily avg |

### Why Parametric Insurance?

Traditional insurance requires **you to prove
your loss** — assessors, paperwork, weeks of
waiting, frequent rejections.

Parametric insurance uses **objective,
verifiable data**. If the trigger condition
is met, the payout happens. Period.
No human judgment. No bias. No delay.

---

##  AI/ML Integration

### 1. Dynamic Premium Calculation
**Technology: Brain.js Neural Network**

- Trained on historical weather data,
  zone-level disruption frequency, and
  claim patterns
- 7 risk input parameters per partner
- Output: Personalized weekly premium in ₹
- Retrains weekly with fresh incoming data
- Ensures pricing stays fair and accurate

### 2. Intelligent Fraud Detection
**Technology: Rule-Based ML Engine**

| Signal | Flag Condition |
|--------|---------------|
| Location Mismatch | GPS ≠ registered zone |
| Excessive Claims | >3 claims per week |
| Suspicious Timing | Claim outside work hours |
| Short Disruption | Event lasted <30 minutes |
| Duplicate Event | Same event claimed twice |
| Velocity Check | Multiple claims in <1 hour |
```
Risk Levels:
LOW → MEDIUM → HIGH → BLOCKED
```

### 3. Predictive Risk Dashboard
**Technology: Forecast API + Trend Analysis**

- Predicts next week's likely disruptions
  using 7-day weather forecast data
- Estimates expected claim volumes for
  insurer reserve planning
- Monitors loss ratios in real time
- Flags zones at high risk for upcoming week

---
