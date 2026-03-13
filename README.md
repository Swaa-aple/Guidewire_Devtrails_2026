#⚡ A.E.G.I.S
## AI Enabled Gig-worker Insurance System

![Guidewire DEVTrails 2026](https://img.shields.io/badge/Guidewire-DEVTrails%202026-blue?style=for-the-badge)
![Phase](https://img.shields.io/badge/Phase-1%20Ideation-yellow?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-React%20%7C%20Node.js%20%7C%20MongoDB-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

> Protecting India's Q-Commerce delivery workforce 
> from income loss caused by uncontrollable 
> external disruptions — automatically.

 [Watch our 2-minute pitch video](#) 
*(link will be updated before March 20 deadline)*

------------------------------------------------------

##  Table of Contents
- [The Problem](#the-problem)
- [Our Solution](#our-solution)
- [Our Persona](#our-persona)
- [Weekly Premium Model](#weekly-premium-model)
- [Parametric Triggers](#parametric-triggers)
- [AI/ML Integration](#aiml-integration)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Development Plan](#development-plan)
- [Team](#team)
- [Getting Started](#getting-started)

--------------------------------------------------

##  The Problem

India's Q-Commerce sector is growing at an 
unprecedented pace. Platforms like Blinkit and 
Instamart promise 10-minute deliveries — and 
behind every one of those deliveries is a 
partner riding through India's most extreme 
weather conditions.

**The hard truth:**
- 5 million+ active Q-Commerce delivery partners 
  across India
- Average daily earnings of ₹500–900 per partner
- External disruptions cause 20–30% monthly 
  income loss
- Zero existing income protection mechanisms 
  for these workers

When heavy rain hits Bengaluru, when floods 
block Chennai roads, when Delhi's AQI crosses 
dangerous levels — these partners simply cannot 
work. And when they cannot work, they do not 
earn. Not a rupee. No safety net. No fallback.

**A.E.G.I.S exists to change that.**

--------------------------------------------------

## Our Solution

A.E.G.I.S is an AI-powered parametric income 
insurance platform built exclusively for 
Q-Commerce delivery partners on Blinkit 
and Instamart.

**How it works in 4 steps:**

1. DETECT   → Real-time monitoring of weather,
               AQI, and civic disruption data
               
2. TRIGGER  → When a parametric threshold is
               crossed, claim is auto-initiated
               — zero manual intervention
               
3. VALIDATE → AI fraud engine cross-checks
               location, activity, and claim
               patterns in milliseconds
               
4. PAY      → Verified payout credited to
               partner's UPI within 2 hours.
               WhatsApp confirmation sent.


**No forms. No assessors. No waiting. 
No rejection drama.**

------------------------------------------------

##  Our Persona

### Primary User: Q-Commerce Delivery Partner
*Blinkit / Instamart / Zepto*

| Attribute | Detail |
|-----------|--------|
| Age | 18–35 years |
| Cities | Metro + Tier-2 cities across India |
| Daily Earnings | ₹500–900/day |
| Weekly Earnings | ₹3,000–5,500/week |
| Working Hours | 8–14 hours/day |
| Working Days | 6–7 days/week |
| Tech Comfort | Smartphone proficient, WhatsApp daily |
| Biggest Fear | Losing a full day's income to bad weather |

### Why Q-Commerce Specifically?

Unlike food delivery, Q-Commerce partners operate 
on extremely tight time windows (8–15 minutes per 
delivery). This means:

- They cannot wait out a rain shower
- They operate in hyper-local zones making 
  location-based triggers highly accurate
- Their income is more directly impacted
  by short but intense disruptions
- Fraud detection is easier due to 
  zone-based activity tracking

-----------------------------------------------------

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

### Scenario 2 — Severe Air Pollution 
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
> Only partners registered within the 
> affected zones receive payouts. Location 
> validation prevents claims from 
> unaffected areas.

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
- Premium adjusts dynamically week to week 
  based on upcoming weather forecast
- Aligned with Blinkit/Instamart weekly 
  settlement cycles

### How AI Adjusts the Premium

Our Brain.js neural network computes a 
**risk multiplier** (0.8x – 1.6x) based on:
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
> Dharavi zone, Mumbai, during monsoon 
> season = 1.45x risk multiplier
> Final Premium = ₹49 × 1.45 = ₹71/week

---

##  Parametric Triggers

These 5 automated triggers initiate claims 
with **zero human intervention:**

| # | Trigger | Condition | Payout |
|---|---------|-----------|--------|
| 1 | Heavy Rain | Rainfall >35mm in 3hrs | 50% of daily avg |
| 2 | Extreme Heat | Temperature >43°C | 30% of daily avg |
| 3 | Severe Pollution | AQI >400 | 40% of daily avg |
| 4 | Flood Alert | Active govt flood warning | 100% of daily avg |
| 5 | Low Visibility | Visibility <500m | 25% of daily avg |
| 6 | Civic Disruption | Admin-verified strike/curfew | 60% of daily avg |

### Why Parametric Insurance?

Traditional insurance requires **you to prove 
your loss** — assessors, paperwork, weeks of 
waiting, frequent rejections.

Parametric insurance uses **objective, 
verifiable data**. If the trigger condition 
is met, the payout happens. Period. No 
human judgment. No bias. No delay.

This model is uniquely suited to gig workers 
who cannot afford to wait weeks for a claim 
to be processed.

---

##  AI/ML Integration

### 1. Dynamic Premium Calculation
**Technology:** Brain.js Neural Network

- Trained on historical weather data, 
  zone-level disruption frequency, and 
  claim patterns
- Inputs: 7 risk parameters per partner
- Output: Personalized weekly premium
- Model retrains weekly with fresh data
- Ensures pricing stays fair and 
  actuarially sound

### 2. Intelligent Fraud Detection
**Technology:** Rule-based ML Engine

Our fraud engine flags suspicious claims 
based on multiple signals:

| Signal | Flag Condition |
|--------|---------------|
| Location Mismatch | GPS ≠ registered zone |
| Excessive Claims | >3 claims per week |
| Suspicious Timing | Claim outside work hours |
| Short Disruption | Event lasted <30 minutes |
| Duplicate Event | Same event claimed twice |
| Velocity Check | Multiple claims in <1 hour |

Risk Levels: `LOW` → `MEDIUM` → `HIGH` → `BLOCKED`

### 3. Predictive Risk Dashboard
**Technology:** Trend Analysis + Forecast API

- Predicts next week's likely disruptions 
  using 7-day weather forecasts
- Estimates expected claim volumes for 
  insurer reserve planning
- Monitors loss ratios in real time
- Flags zones at high risk for 
  upcoming week

---

##  Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | React.js + Tailwind CSS | Partner and admin UI |
| Backend | Node.js + Express.js | API server |
| Database | MongoDB Atlas | Data storage |
| AI/ML | Brain.js | Premium calculation |
| Weather | OpenWeatherMap API | Disruption detection |
| AQI | AQICN.org API | Pollution monitoring |
| Payments | Razorpay Test Mode | Payout simulation |
| Notifications | Twilio WhatsApp API | Partner alerts |
| Hosting | Railway.app | Cloud deployment |
| Version Control | GitHub | Collaboration |

---

##  System Architecture
```
┌─────────────────────────────────────────────┐
│           PARTNER (React Web App)            │
│  Onboarding → Policy → Monitor → Dashboard  │
└──────────────────┬──────────────────────────┘
                   │ HTTPS
┌──────────────────▼──────────────────────────┐
│           NODE.JS + EXPRESS API              │
│                                              │
│   /auth  /policy  /claims  /payout  /admin  │
└────┬──────────┬──────────┬──────────┬───────┘
     │          │          │          │
┌────▼───┐ ┌───▼────┐ ┌───▼───┐ ┌───▼──────┐
│MongoDB │ │Brain.js│ │Weather│ │ Razorpay │
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
Twilio WhatsApp notification sent to partner
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

## 🗓️ Development Plan

### ✅ Phase 1 — Ideation & Foundation
*March 4 – March 20*

- [x] Define persona and use case scenarios
- [x] Design system architecture
- [x] Define weekly premium model
- [x] Define parametric triggers
- [x] Set up GitHub repository
- [x] Document tech stack and AI integration plan
- [ ] Record 2-minute strategy video

### 🔲 Phase 2 — Automation & Protection
*March 21 – April 4*

- [ ] Worker registration and onboarding flow
- [ ] Weekly policy purchase with Razorpay
- [ ] OpenWeatherMap + AQICN API integration
- [ ] Brain.js premium calculator (trained model)
- [ ] Parametric trigger engine (30-min polling)
- [ ] Automated claim initiation pipeline
- [ ] Rule-based fraud detection engine
- [ ] Partner dashboard (earnings + coverage)

### 🔲 Phase 3 — Scale & Optimise
*April 5 – April 17*

- [ ] Advanced fraud detection (GPS spoofing)
- [ ] Twilio WhatsApp notification system
- [ ] Admin analytics dashboard
- [ ] Predictive risk modeling
- [ ] Loss ratio monitoring
- [ ] Final 5-minute demo video
- [ ] Final pitch deck (PDF)

---

##  Team

| Member | Role | GitHub |
|--------|------|--------|
| Sagar | Team Lead | [@T-Sagar-Pradhan](#) |
| Swayam | Backend Developer | [@Swaa-aple](#) |
| Sibaram | Frontend Developer | [@SIBARAM-PATRA](#) |
| Shaswat | Docs + Testing + Strategy | [@Shaswat-Panda](#) |

🏫 Siksha 'O' Anusandhan - Institute of Technical Education and Research (ITER)
📍 Bhubaneswar, Odisha

---


### Environment Variables Required

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


---

##  Why A.E.G.I.S Will Win

| Factor | Traditional Insurance | A.E.G.I.S |
|--------|----------------------|-----------|
| Claim Process | Manual, weeks long | Automatic, instant |
| Pricing | Fixed, one-size | AI dynamic, personalized |
| Payout Speed | Days to weeks | Under 2 hours |
| Fraud Check | Manual assessor | AI engine, real-time |
| Weekly Model | Not available | Core feature |
| Gig Worker Focus | Non-existent | Built exclusively for them |

---

*Built with purpose for Guidewire DEVTrails 2026*
*Protecting India's instant delivery economy, 
one partner at a time* 
