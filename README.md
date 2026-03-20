#  GigShield: AI-Powered Income Protection for India’s Gig Workers

---

##  Problem Statement

India’s gig economy depends heavily on delivery workers and service partners who work in changing external conditions. Factors such as heavy rain, extreme heat, poor air quality, traffic disruption, and sudden local restrictions can directly reduce their working hours and weekly earnings.

For many gig workers, even a short disruption can lead to a major loss of income. At present, there is very limited financial protection available for these workers against such uncontrollable events.

---

##  Persona

**Target User:**  
Gig workers such as food delivery partners, parcel delivery agents, and other app-based workers operating in urban and semi-urban areas.

###  Scenario:
- A delivery partner usually earns a fixed amount based on daily completed orders.
- Bad weather or high pollution reduces the number of deliveries they can complete.
- Their weekly income drops because of conditions outside their control.
- There is no fast and reliable compensation process for this income loss.

---

##  Solution Overview

GigShield is an AI-powered parametric insurance platform designed to protect gig workers from income loss caused by external disruptions.

## Key Idea:
- Monitor real-world disruption signals
- Assess worker risk based on zone and conditions
- Automatically detect trigger events
- Enable quick claim approval and payout simulation

 Minimal paperwork  
 Faster claim processing  
 Smart risk-based protection  
 Built for gig economy workers

---

##  Workflow

1. User registers on the platform.
2. User chooses a weekly protection plan.
3. System captures work location and service zone.
4. Risk level is calculated using real-time and historical indicators.
5. The platform monitors disruption events such as:
   - Heavy rainfall
   - Extreme heat
   - High AQI / pollution
   - Curfews or city restrictions
6. If the event crosses the defined threshold:
   - Claim condition is validated
   - Compensation is triggered automatically or marked eligible
7. User receives payout status and claim details on the dashboard.

---

##  Weekly Premium Model

| Risk Level   | Weekly Premium |
|-------------|---------------|
| Low Risk     | ₹20/week      |
| Medium Risk  | ₹40/week      |
| High Risk    | ₹60/week      |

###  Factors Considered:
- Worker location and service zone
- Historical disruption frequency
- Weather and pollution patterns
- Area-based risk score

---

##  Parametric Triggers

| Event            | Condition                  | Payout |
|------------------|---------------------------|--------|
| Heavy Rain       | Rainfall above threshold  | ₹300   |
| Extreme Heat     | Temperature above limit   | ₹200   |
| High Pollution   | AQI above safe level      | ₹250   |
| Local Restriction| Curfew / zone shutdown    | ₹300   |

 Claims are triggered based on predefined conditions instead of long manual claim processing.

---

##  AI/ML Integration

###  Risk Prediction
- Estimates the probability of disruption in a worker’s service area

###  Smart Premium Suggestion
- Suggests weekly premium category based on expected risk

###  Fraud Detection
- Validates user location
- Detects repeated or suspicious claims
- Checks event-to-zone matching before payout

---

##  Platform Choice

**Web Application**

###  Why Web?
- Easy to access on laptop and mobile browser
- No installation required
- Suitable for quick prototype development
- Simple to demonstrate in hackathon phase submissions

---

##  Tech Stack

- **Frontend:** React / Vite
- **Backend:** Spring Boot or Node.js
- **Database:** MySQL
- **APIs:** Weather API, AQI API, Maps/Location API
- **AI/ML:** Python model or rule-based scoring
- **Payment Simulation:** Razorpay test mode / mock payout flow

---

##  Development Plan

###  Phase 1:
- Project idea finalization
- README and GitHub repository setup
- Basic prototype frontend showing user flow

###  Phase 2:
- User registration and login
- Plan selection
- Risk scoring and premium logic
- Trigger-based claims flow

###  Phase 3:
- Fraud detection features
- Admin dashboard
- Payout simulation
- Analytics and reporting

---

##  Dashboard Features

### Worker Dashboard:
- Selected protection plan
- Premium amount
- Active status
- Claim eligibility and history

###  Admin Dashboard:
- Number of registered users
- Claims triggered
- High-risk zones
- Payout summary

---

##  Future Enhancements

- Integration with gig platforms for better validation
- Live notifications for risk alerts
- Advanced ML-based premium prediction
- Personalized plans based on worker activity history
- Regional language support

---

## Conclusion

GigShield aims to make insurance smarter, faster, and more accessible for India’s gig workforce. By combining automation, AI-based risk scoring, and parametric claim logic, the platform can reduce income uncertainty and provide timely financial support during disruptions.

---

##  Repository Structure

devtrails-gigshield/
│── README.md
│── frontend/
│   │── src/
│   │── public/
│   │── package.json
│── docs/
│   │── screenshots/
│   │── demo-notes.md

This repository contains the Phase 1 prototype and documentation for the GigShield project. The frontend folder will hold the basic user flow prototype, while the docs folder will contain supporting screenshots and demo notes.
