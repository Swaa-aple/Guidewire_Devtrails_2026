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
