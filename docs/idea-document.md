# Idea Document

## Project Title
DeliveryShield AI – Parametric Income Protection for Delivery Workers

---

## Problem Description

Gig economy delivery workers face financial instability due to unpredictable environmental conditions.

Heavy rain, floods, pollution, and extreme heat can prevent them from completing deliveries, resulting in lost income.

Currently, there is no insurance system that compensates workers for income loss caused by these disruptions.

---

## Proposed Solution

DeliveryShield AI is a parametric insurance system that automatically compensates delivery workers when environmental disruption thresholds are exceeded.

Instead of manual claims, the system monitors real-time environmental data and triggers automatic payouts.

---

## Persona Example

Name: Rahul  
Platform: Swiggy  
City: Bangalore  
Average Weekly Income: ₹5000

If heavy rain prevents deliveries, Rahul may lose ₹700–₹1000 in earnings.

DeliveryShield AI compensates part of this loss.

---

## Weekly Premium Model

Insurance pricing is based on weekly income cycles.

Example:

Weekly income = ₹5000

Coverage = 40% of weekly income

Coverage amount = ₹2000

Premium formula:

premium = coverage × risk_factor × 0.01

Example:

risk_factor = 1.2

premium = 2000 × 1.2 × 0.01 = ₹24 per week

---

## Parametric Triggers

Heavy Rain → Rainfall > 80mm → ₹300 payout  
Extreme Heat → Temperature > 42°C → ₹200 payout  
Severe Pollution → AQI > 400 → ₹250 payout  
Flood Alert → City flood alert → ₹500 payout

---

## AI Integration

AI is used for:

1. Risk Prediction  
Predict disruption probability using historical weather data.

2. Dynamic Premium Calculation  
Adjust premiums based on environmental risk levels.

3. Fraud Detection  
Detect suspicious claims using anomaly detection models.

---

## Technology Stack

Frontend: React.js  
Backend: Node.js + Express  
Database: MongoDB  
AI: Python + Scikit-learn  
APIs: Weather, Pollution, Traffic