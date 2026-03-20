# GigShield AI - Parametric Insurance for Gig Workers

## 📌 Problem Statement
Delivery partners (Swiggy/Zomato) lose 20–30% of their income due to external disruptions like heavy rain, extreme heat, pollution, and curfews. Currently, there is no structured income protection system available for them.

---

## 👤 Persona
We are targeting food delivery partners in urban areas like Vijayawada.

Example Persona:
- Name: Ramesh
- Age: 24
- Works: Swiggy Delivery Partner
- Income: ₹500–₹800/day
- Works: 8–10 hours/day

---

## ⚠️ Problems Faced
- Heavy rain → cannot deliver
- Extreme heat → reduced working hours
- Pollution → unsafe working conditions
- Curfews → restricted movement

➡️ Result: Loss of daily/weekly income

---

## 💡 Our Solution
GigShield AI is an AI-powered parametric insurance platform that protects delivery workers from income loss due to external disruptions.

---

## ⚙️ Workflow
1. User registers with basic details  
2. AI calculates risk score based on location and historical data  
3. Weekly premium is generated dynamically  
4. System monitors real-time disruptions using APIs  
5. If disruption occurs → automatic claim triggered  
6. AI estimates income loss  
7. Instant payout is processed  

---

## 💰 Weekly Pricing Model
- Low Risk → ₹20/week  
- Medium Risk → ₹35/week  
- High Risk → ₹50/week  

Premium depends on location and working pattern.

---

## 🌦️ Parametric Triggers
- Rainfall > 50mm  
- Temperature > 42°C  
- AQI > 300  
- Curfew / restricted movement  
- Platform downtime (mock)  

---

## 🤖 AI/ML Usage
- Risk prediction for premium calculation  
- Income estimation during disruptions  
- Fraud detection using anomaly detection  

---

## 🔐 Fraud Detection
- GPS + IP location validation  
- Weather API cross-check  
- Duplicate claim prevention  
- Suspicious activity detection  

---

## 🚨 Adversarial Defense & Anti-Spoofing Strategy

### 1. Differentiation
We differentiate real vs fake users using:
- Behavior analysis (delivery activity patterns)  
- Movement consistency (not just GPS points)  
- AI-based risk scoring  

Genuine users show consistent delivery behavior, while fraud users show activity only during trigger events.

---

### 2. Data Used
- GPS + IP location  
- Delivery activity (mock data)  
- Weather API validation  
- Device ID tracking  
- Crowd pattern detection (multiple users in same location)  

---

### 3. UX Balance
- Low risk → instant payout  
- Medium risk → slight delay  
- High risk → flagged for review  

We ensure genuine users are not penalized during network issues by allowing retry and delayed validation.

---

## 🏗️ System Architecture

GigShield AI is designed as a scalable system:

- Frontend handles user onboarding and dashboard  
- Backend processes risk scoring, triggers, and claims  
- AI layer performs risk prediction and fraud detection  
- APIs provide real-time environmental data  
- Payment system enables instant payouts  

The system is fully automated with zero manual intervention.

## 🛠️ Tech Stack

- **Frontend:** React (Vite) – User dashboard and onboarding  
- **Backend:** Node.js / Spring Boot – Business logic and API handling  
- **Database:** MongoDB – Stores user profiles, policies, and claims  

### 🔗 APIs & Data Sources
- Weather API – Rainfall, temperature detection  
- Air Quality API – AQI monitoring  
- Traffic Data (Mock) – Delivery feasibility analysis  
- Platform Activity Data (Mock) – Delivery behavior tracking  
- Government Alerts (Mock) – Curfew/restriction detection  

### 💳 Payments
- Razorpay (Test Mode) – Simulated instant payouts  

### 🤖 AI/ML Layer
- Risk Scoring Model – Dynamic premium calculation  
- Income Loss Estimation Model  
- Fraud Detection Model – Anomaly detection & spoofing prevention  

---

## 📊 Future Scope
- Multi-city expansion  
- Advanced ML models  
- Integration with delivery platforms  

---
## 🎥 Demo Video

> 🎬 **Click below to watch our 2-minute project walkthrough**

🔗 [▶️ Click to Watch](https://youtu.be/PVqK4OZDV4I?si=3meY_RtWCSdNm_JD)

## 🚀 Conclusion
GigShield AI ensures financial protection for gig workers by combining AI-driven risk assessment, parametric automation, and strong fraud prevention mechanisms.
