# ⚡ A.E.G.I.S
## AI Enabled Gig-worker Insurance System

![Guidewire DEVTrails 2026](https://img.shields.io/badge/Guidewire-DEVTrails%202026-blue?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-Code%20Blooded-red?style=for-the-badge)
![Phase](https://img.shields.io/badge/Phase-1%20Ideation-yellow?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-React%20%7C%20Node.js%20%7C%20MongoDB-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

> Protecting India's Q-Commerce delivery workforce
> from income loss caused by uncontrollable
> external disruptions — automatically.

 **[Watch our 2-minute pitch video](#)**
*(link will be updated before March 20 deadline)*

---

##  Table of Contents
- [The Problem](#The-Problem)
- [Our Solution](#Our-Solution)
- [Claim Processing — Two Track System](#claim-processing-two-track-system)
- [Our Persona](#Our-Persona)
- [Real Scenarios](#Real-Scenarios)
- [Weekly Premium Model](#Weekly-Premium-Model)
- [Parametric Triggers](#Parametric-Triggers)
- [AI/ML Integration](#AI/ML-Integration)
- [System Architecture](#System-Architecture)
- [Tech Stack](#Tech-Stack)
- [Development Plan](#Development-Plan)
- [UI Mockups and Wireframes](#UI-Mockup-and-Wireframes)
- [Business Viability](#Business-Viability)
- [Adversarial Defense & Anti-Spoofing Strategy](#Adversarial-Defense-&-Anti-Spoofing-Strategy)
- [Team](#Team)

---

##  The Problem

India's Q-Commerce sector is growing at an
unprecedented pace. Platforms like Blinkit and
Instamart promise 10-minute deliveries — and
behind every one of those deliveries is a
partner riding through India's most extreme
weather conditions.

**The hard truth:**
- 5 million+ active Q-Commerce delivery 
  partners across India
- Average daily earnings of ₹500–900 per partner
- External disruptions cause 20–30% monthly 
  income loss
- Zero existing income protection for 
  these workers

When heavy rain hits Bengaluru, when floods
block Chennai roads, when Delhi AQI crosses
dangerous levels — these partners cannot work.
And when they cannot work, they do not earn.
Not a rupee. No safety net. No fallback.

**A.E.G.I.S exists to change that.**

---

##  Our Solution

A.E.G.I.S is an AI-powered parametric income
insurance platform built exclusively for
Q-Commerce delivery partners on Blinkit
and Instamart.

**How it works in 4 steps:**
```
1. DETECT   → Real-time monitoring of weather,
               AQI, and civic disruption data

2. TRIGGER  → When a parametric threshold is
               crossed, claim is auto-initiated
               with zero manual intervention

3. VALIDATE → AI fraud engine cross-checks
               location, activity, and claim
               patterns in milliseconds

4. PAY      → Verified payout credited to
               partner's UPI within 2 hours
               WhatsApp confirmation sent
```

**No forms. No assessors. No waiting.
No rejection drama.**

---

## Claim Processing — Two Track System

**Track 1 — Auto Approved (95% of claims)**
Worker in verified zone + 
Low behavioral anomaly score +
No suspicious signals
→ Fully automatic payout in 2 hours
→ Zero worker involvement needed

**Track 2 — Verify and Pay (5% of claims)**
Suspicious signals detected +
High behavioral anomaly score +
Fraud ring patterns found
→ WhatsApp verification request sent
→ Worker completes face verification
→ Payout released within 4 hours
→ Worker ignores → claim held for review

---

##  Our Persona

### Primary User: Q-Commerce Delivery Partner
*Blinkit / Instamart*

| Attribute | Detail |
|-----------|--------|
| Age | 18–35 years |
| Cities | Metro + Tier-2 cities across India |
| Daily Earnings | ₹500–900/day |
| Weekly Earnings | ₹3,000–5,500/week |
| Working Hours | 8–14 hours/day |
| Working Days | 6–7 days/week |
| Tech Comfort | Smartphone, WhatsApp daily |
| Biggest Pain | Full day income lost to bad weather |

### Why Q-Commerce Specifically?

Unlike food delivery, Q-Commerce partners
operate on extremely tight time windows
(8–15 minutes per delivery). This means:

- They cannot wait out a rain shower
- They operate in hyper-local zones making
  location-based triggers highly accurate
- Their income is more directly impacted
  by short but intense disruptions
- Fraud detection is easier due to
  zone-based activity tracking

---

##  Real Persona Scenarios

### Scenario 1 — Heavy Rain 
> It is 6:30 PM in Bengaluru. Rainfall crosses
> 40mm in 3 hours. A.E.G.I.S weather monitor
> detects the threshold breach. All active
> Blinkit partners in Bengaluru with valid
> policies receive automatic claim initiation.
> Fraud engine validates zone presence.
> ₹350 credited to UPI within 2 hours.
> WhatsApp message confirms payout.
> Partner does not touch the app once.

### Scenario 2 — Severe Pollution 
> Delhi AQI crosses 450 — classified as
> Severe by CPCB standards. A.E.G.I.S AQI
> monitor triggers automatically. Partners
> on Standard and Premium plans receive
> 40% daily income protection. GPS data
> confirms partners were in registered zones.
> Claims processed without any manual step.

### Scenario 3 — Local Strike / Curfew 
> Unplanned strike declared in specific
> zones of Hyderabad. Admin triggers manual
> disruption event via A.E.G.I.S dashboard.
> Only partners registered within affected
> zones receive payouts. Location validation
> prevents claims from unaffected areas.

---

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

##  System Architecture

### High Level Architecture
```
┌─────────────────────────────────────────────┐
│           PARTNER (React Web App)            │
│  Onboarding → Policy → Monitor → Dashboard  │
└──────────────────┬──────────────────────────┘
                   │ HTTPS API Calls
┌──────────────────▼──────────────────────────┐
│           NODE.JS + EXPRESS API              │
│                                              │
│  /auth  /policy  /claims  /payout  /admin   │
└────┬──────────┬──────────┬──────────┬───────┘
     │          │          │          │
┌────▼───┐ ┌───▼────┐ ┌───▼───┐ ┌───▼──────┐
│MongoDB │ │Brain.js│ │Weather│ │Razorpay  │
│ Atlas  │ │  ML    │ │+ AQI  │ │Test Mode │
└────────┘ └────────┘ └───┬───┘ └──────────┘
                           │
                    ┌──────▼──────┐
                    │   Twilio    │
                    │  WhatsApp   │
                    └─────────────┘
```

### Automated Claim Flow
```
Weather API polled every 30 minutes
          ↓
Threshold breach detected
(e.g. Rainfall >35mm in Bengaluru)
          ↓
All active Bengaluru policyholders fetched
          ↓
Fraud engine validates each claim
          ↓
Clean claims → Razorpay payout triggered
          ↓
MongoDB claim record updated → PAID
          ↓
Twilio WhatsApp notification sent
          ↓
Admin dashboard updated with loss ratio
```

### MongoDB Collections
```
users         → partner profiles + risk scores
policies      → active weekly policies
claims        → all triggered + processed claims
disruptions   → logged disruption events
payouts       → payment transaction records
fraud_logs    → flagged claim audit trail
```

---

##  Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | React.js + Tailwind CSS | Partner and admin UI |
| Backend | Node.js + Express.js | REST API server |
| Database | MongoDB Atlas | Cloud data storage |
| AI/ML | Brain.js | Neural network premium calc |
| Weather API | OpenWeatherMap | Disruption detection |
| AQI API | AQICN.org | Pollution monitoring |
| Payments | Razorpay Test Mode | Payout simulation |
| Notifications | Twilio WhatsApp | Partner alerts |
| Hosting | Railway.app | Cloud deployment |
| Version Control | GitHub | Team collaboration |

---

##  Development Plan

###  Phase 1 — Ideation & Foundation
*March 4 – March 20*

- [x] Define persona and use case scenarios
- [x] Design system architecture
- [x] Define weekly premium model
- [x] Define parametric triggers
- [x] Set up GitHub repository
- [x] Document tech stack and AI plan
- [ ] Record 2-minute strategy video

###  Phase 2 — Automation & Protection
*March 21 – April 4*

- [ ] Worker registration and onboarding
- [ ] Weekly policy purchase with Razorpay
- [ ] OpenWeatherMap + AQICN integration
- [ ] Brain.js premium calculator
- [ ] Parametric trigger engine
- [ ] Automated claim initiation pipeline
- [ ] Fraud detection engine
- [ ] Partner dashboard

###  Phase 3 — Scale & Optimise
*April 5 – April 17*

- [ ] Advanced fraud detection (GPS spoofing)
- [ ] Twilio WhatsApp notifications
- [ ] Admin analytics dashboard
- [ ] Predictive risk modeling
- [ ] Loss ratio monitoring
- [ ] Final 5-minute demo video
- [ ] Final pitch deck PDF

---

## UI Mockups and Wireframes

> **Disclaimer:** The visuals below are **UI Mockups and Wireframes**. They represent the architectural logic and intended design aesthetic. The final production UI may be built to match these specifications during Phase 2.

###  High-Fidelity Mockups
| 1. Onboarding | 2. Buy Policy | 3. Live Monitor | 4. Claims | 5. Dashboard |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/cd9860b6-6b8f-4b5d-b06c-6c139e131ad0" width="180" /> | <img src="https://github.com/user-attachments/assets/b9137eb1-4fda-4790-989d-7edd6fa5382b"  width="180" /> | <img src="https://github.com/user-attachments/assets/5885d7a7-dd72-400b-ad55-d6f42ec4c21d" width="180" /> | <img src="https://github.com/user-attachments/assets/16b56ebd-0ca7-4d47-be13-2455e89f580c" width="180" /> | <img src="https://github.com/user-attachments/assets/45fce1d7-2170-40db-88ba-9d61c4cfd92a" width="180" /> |

###  Structural Wireframes
| Onboarding Logic | Pricing Engine | Trigger Monitor | Claim Pipeline | Data Summary |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8c6afe65-0817-40e6-9516-f90f1e4a7bea"  width="180" /> | <img src="https://github.com/user-attachments/assets/a12579f0-2ffe-4607-bb1d-8d7bb8d01a71" width="180" /> | <img src="https://github.com/user-attachments/assets/8fbcfe21-7d77-4613-9fc0-782232d05204" width="180" /> | <img src="https://github.com/user-attachments/assets/d3bb19be-b84c-4a0a-abcb-a78f684c4c4c" width="180" /> | <img src="https://github.com/user-attachments/assets/57ab8f23-e491-434b-bb1b-755382f1e41a" width="180" /> |

---

###  Design Breakdown
* **Onboarding:** Collects hyper-local zone data for precise risk monitoring.
* **Policy Selection:** Displays dynamic premiums calculated by our **Brain.js** neural network.
* **Live Monitor:** Real-time polling of **OpenWeatherMap** and **AQI** APIs.
* **Claims:** Automated status tracking for **Razorpay** payouts.
* **Dashboard:** High-level view of the partner's weekly income protection.

##  Business Viability

| Metric | Value |
|--------|-------|
| Target Market | 5M+ Q-Commerce delivery partners |
| Weekly Premium Range | ₹29 - ₹89 per worker |
| Average Weekly Premium | ₹49 |
| Target Year 1 Users | 10,000 workers |
| Year 1 Weekly Revenue | ₹4,90,000/week |
| Year 1 Annual Revenue | ₹2.5 Crore |
| Loss Ratio Target | <45% |
| Customer Acquisition | Via Blinkit/Instamart partner apps |

---


## Adversarial Defense & Anti-Spoofing Strategy

### The Attack Scenario
A coordinated fraud ring attempts to exploit 
A.E.G.I.S by spoofing GPS locations and 
coordinating mass claims during real 
disruption events to steal payouts without 
genuinely being affected workers.

---

### Q1 — How We Spot Fake GPS vs Real Stranded Worker

#### Layer 1 — Velocity Threshold Detection
A genuine delivery partner travels at 
realistic speeds on Indian roads. 
A.E.G.I.S tracks real-time speed and 
calculates minimum possible travel time 
between two points.

If a worker's GPS shows them moving faster 
than the maximum legal speed limit for 
delivery partners on Blinkit/Instamart — 
their account is instantly flagged.
```
Jagamara to Saheed Nagar = 25 mins minimum
Worker appears there in 2 mins = FRAUD 
Worker appears there in 20 mins = Genuine 
```

#### Layer 2 — Time Window Presence Verification
A.E.G.I.S monitors all workers during a 
defined time window around each disruption:
```
Disruption: 5:00 PM to 5:30 PM
Window: 4:50 PM to 5:40 PM
(10 minute buffer each side)

Workers tracked continuously in this window.
Location consistency checked every second.
Teleportation within window = FRAUD 
Consistent presence = Genuine 
```

#### Server-Side Tracking 
All location data is stored on A.E.G.I.S 
servers, not the worker's device. Workers 
are unaware of continuous server pings — 
making it impossible to manipulate.

If network dies during event:
```
Last confirmed server location checked.
Network returns → real-time sync resumes.
In Tier 1/2 cities network interruption 
= seconds to minutes, never hours.
Gap under 10 minutes = ignored 
Gap over 30 minutes = investigated 
```

#### Layer 3 — Warehouse Radius Verification
Every Blinkit/Instamart partner is assigned 
to a specific dark store warehouse with a 
defined delivery radius. A.E.G.I.S cross 
references 14 days of historical working 
zone data.
```
Worker assigned to Jagamara warehouse 
Suddenly appears in Patia during rain event
= Outside warehouse radius
= No prior zone history
= FRAUD 

Worker wants zone transfer?
Must establish link bondage with new 
warehouse — minimum 14 days activity 
in new zone before claims accepted there.
```

#### Layer 4 — 14 Day Waiting Period for New Workers
New workers cannot claim for first 14 days.

Just like a new employee doesn't get paid 
leave on Day 1 — you earn trust first. 
Fraudsters hate waiting. Genuine workers 
understand it.

Workers are informed upfront during onboarding:
```
"Your coverage starts Week 3, once we 
can verify your work zone."

They still pay premium from Week 1 — 
that builds the pool. Payouts only 
unlock after 14 days of verified 
delivery activity.
```

#### Layer 5 — Weighted Trust Score
Each worker carries a dynamic 
Weighted Trust Score combining:
```
→ Star ratings (quality signal)
→ Delivery count (experience signal)
→ Claim history (fraud signal)
→ Zone consistency (location signal)

Dynamic weighting applied:
Recent behavior weighted MORE 
than old behavior (time decay).

New workers → Cold start protocol
Real-time GPS signals weighted 
higher than ratings initially.
Score builds over time.

Low Trust Score = Enhanced monitoring
High Trust Score = Fast track claims
```

---

### Q2 — What Data Catches a Fraud Ring

#### Signal 1 — Registration Spike Detection
```
Normal registrations = ~10 per day
Sudden spike = 500 in 3 days
= 50x abnormal spike 

Detection method:
Same device ID across multiple accounts
Same IP address at registration
Same WiFi network fingerprint
Registered within 30 minute window

No contact permission needed.
Device and network data tells 
the full story without 
invading worker privacy.
```

#### Signal 2 — Surge Pricing and Portal Lock
No insurance before predicted disruption.
```
72 hours before predicted rain:
→ Premium increases significantly

48 hours before:
→ Premium doubles

24 hours before:
→ Portal LOCKED for new purchases
   in that specific affected zone

Genuine workers already have 
weekly policy before prediction.
Fraud rings buy last minute.
Surge pricing destroys their profit.
Portal lock destroys their strategy.
```

#### Signal 3 — Claims Velocity Check
```
Normal claims per minute = ~10
500 claims in 30 seconds = 
50x spike detected 

System response:
→ All 500 claims FROZEN instantly
→ Fraud check runs on each claim
→ 2 hour processing window used
   as fraud verification time
→ Clean claims → paid within 2 hours 
→ Suspicious claims → held for review 

Worker WhatsApp notification:
"Disruption detected! Your claim 
is being processed. Payment within 
2 hours if verified."
```

#### Signal 4 — Aadhaar KYC Verification
```
One Aadhaar = One AEGIS account.
Period.

Cross verified with Blinkit/Instamart
worker onboarding records.

Cannot create 500 fake accounts
without 500 unique Aadhaar numbers.
Fraud rings cannot operate at scale
under this system.

Single device linked to multiple
Aadhaar attempts = instant block 
```

#### Signal 5 — CaughtRedHanded Pattern
```
Same workers claiming every 
single disruption event.
Week after week. Like clockwork.

MongoDB flags this as:
"CaughtRedHanded" pattern 

Strike system:
Strike 1 → Yellow flag + warning sent
Strike 2 → Legal agreement signed
           "Further fraud = legal action"
Strike 3 → Account suspended
           Blinkit/Instamart notified
           Worker loses delivery job

Ultimate deterrent:
Not just losing AEGIS account.
Losing their entire livelihood.
No fraudster risks that.
```

---

### Q3 — Protecting Honest Workers

#### The Core Philosophy
```
"Assume honesty. 
Verify mathematically. 
Protect aggressively. 
Resolve instantly."

Rule is equal for everyone.
But our system acknowledges 
it can make mistakes.
```

#### Two Track Claim Processing
```
Track 1 — Auto Approved (95% of claims)
Clean trust score + verified location
→ Fully automatic payout in 2 hours
→ Worker does nothing 

Track 2 — Verify and Pay (5% of claims)  
Suspicious signals detected
→ Face verification requested via WhatsApp
→ Verified → paid within 4 hours 
→ Ignored → claim held for review 
```

#### Loyalty Protection System
```
Workers with 3+ months clean history
receive PERSONAL outreach when flagged.

Not a generic notification.
A personal mail:
"Hey Raju, we noticed something unusual 
in your recent claim. Can you help us 
understand what happened? 
Our team will review within 24-48 hours."

Treats loyal workers with respect.
Not treated like criminals.
```

#### Appeal System with SLA
```
Worker appeal window: 7 days
AEGIS resolution SLA: 24-48 hours
(Based on case complexity and traffic)

During appeal period:
→ Account stays FULLY ACTIVE
→ Worker can still claim normally
→ Presumption of innocence maintained
→ Timer visible to worker on app

Resolution outcomes:
Fraud confirmed → Strike applied
Mistake from AEGIS side → 
  Account restored immediately +
  Held payout released +
  Goodwill compensation: ₹50-100
  (amount based on inconvenience level)
```

#### Why Goodwill Compensation Matters
```
Genuine worker wrongly flagged:
→ Gets their claim paid 
→ Gets ₹50-100 compensation 
→ Gets personal apology 
→ Trust score manually corrected 

They are BETTER OFF than if 
nothing happened.
This turns a bad experience 
into a loyalty moment.
```

---

### Summary
```
GPS Spoofing Defense:
5 layer detection system from
velocity checks to warehouse
radius verification.

Fraud Ring Defense:  
5 signal detection from
registration spikes to
CaughtRedHanded pattern.

Honest Worker Protection:
Presumption of innocence +
Personal loyalty outreach +
24-48 hour SLA resolution +
Goodwill compensation for mistakes.

No single signal blocks anyone.
Patterns catch fraud rings.
History protects honest workers.
Speed protects everyone.
```

---


##  Team — CODE BLOODED 🩸

| Member | Role | GitHub | LinkedIn |
|--------|------|--------|----------|
| Sagar | Team Lead | [@T-sagar-pradhan](https://github.com/T-sagar-pradhan) | [LinkedIn](https://www.linkedin.com/in/t-sagar-pradhan-530036300) |
| Swayam | Backend Developer | [@Swaa-aple](https://github.com/Swaa-aple) | [LinkedIn](https://www.linkedin.com/in/swayam-tripathy-swaa) |
| Sibaram | Frontend Developer | [@Sibaram-patra](https://github.com/Sibaram-patra) | [LinkedIn](https://www.linkedin.com/in/sibaram-patra/) |
| Shaswat | Docs + Testing + Strategy | [@Shaswat-Panda](https://github.com/Shaswat0804) | [LinkedIn](https://www.linkedin.com/in/shaswat-panda-0a65b93a9/) |

🏫 Siksha 'O' Anusandhan - Institute of Technical Education and Research (ITER)
📍 Bhubaneswar, Odisha
   Team Code Blooded | Guidewire DEVTrails 2026

---

##  Getting Started

*(Available from Phase 2 onwards)*
```bash
# Clone the repository
git clone https://github.com/Swaa-aple/Guidewire_Devtrails_2026.git

# Navigate to project
cd Guidewire_Devtrails_2026

# Backend setup
cd server
npm install
cp .env.example .env
npm run dev

# Frontend setup
cd ../client
npm install
npm start
```

### Environment Variables
```
MONGODB_URI=your_mongodb_atlas_connection_string
OPENWEATHER_API_KEY=your_openweathermap_key
AQICN_API_KEY=your_aqicn_key
RAZORPAY_KEY_ID=your_razorpay_test_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
TWILIO_WHATSAPP_NUMBER=whatsapp:+14155238886
JWT_SECRET=your_jwt_secret
PORT=5000
```

---

##  Why A.E.G.I.S Wins

| Factor | Traditional Insurance | A.E.G.I.S |
|--------|----------------------|-----------|
| Claim Process | Manual, weeks long | Automatic, instant |
| Pricing | Fixed, one-size | AI dynamic, personalized |
| Payout Speed | Days to weeks | Under 2 hours |
| Fraud Check | Manual assessor | AI engine, real-time |
| Weekly Model | Not available | Core feature |
| Gig Focus | Non-existent | Built exclusively for them |

---

*Built with purpose by Team Code Blooded* 
*Guidewire DEVTrails 2026*
*Protecting India's instant delivery economy,
one partner at a time* 
```
