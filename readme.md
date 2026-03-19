DeliveryShield AI
Parametric Income Protection for Delivery Workers
------------------------------------------------------------------------------------------------------------------------------------------------------------
Overview
-----------
DeliveryShield AI is an AI-powered parametric insurance platform designed to protect gig delivery workers from income loss caused by environmental and external disruptions.

Delivery partners working with platforms like Swiggy and Zomato depend on daily earnings. However, factors like heavy rain, extreme heat, and pollution can reduce their working hours and significantly impact their income.

Our solution provides affordable weekly insurance coverage, using AI-driven risk modeling and real-time triggers to automatically compensate workers during disruptions without any manual claim process.

Inspiration
-------------
India’s gig economy is rapidly growing, but delivery workers still lack financial protection against unpredictable disruptions.

We observed that:

   A single rainy day can reduce earnings drastically

   Extreme heat forces workers to stop working

   Pollution makes outdoor work unsafe

Despite this, no insurance product exists to protect their daily income.

This inspired us to build DeliveryShield AI, a system focused purely on income protection.

Problem Statement
--------------------
Delivery workers lose 20–30% of their weekly income due to:

   Heavy rainfall

   Extreme heat

   Severe pollution

   Traffic shutdowns or curfews

   Traditional insurance:

   Does not cover income loss

   Requires manual claims

   Is not designed for gig workers

What It Does
-------------------
DeliveryShield AI:

   Calculates AI-based weekly premiums

Monitors real-time environmental conditions

Uses parametric triggers to detect disruptions

Automatically initiates claims

Provides instant payouts (simulated)

No paperwork
No claim filing
Fully automated system

How It Works
------------------------------------------------------------------------------------------------------------------------------------------------------------
Worker Registration
        ↓
AI Risk Profiling
        ↓
Weekly Premium Calculation
        ↓
Policy Activation
        ↓
Real-Time Monitoring (Weather, AQI)
        ↓
Disruption Trigger Detected
        ↓
Automatic Claim Initiation
        ↓
Fraud Detection Check
        ↓
Instant Payout
AI Integration
1. Dynamic Risk Assessment

Uses historical weather + location data

Predicts risk level of disruption

2. Weekly Premium Calculation

Adjusts pricing based on:

Location risk

Environmental trends

Worker activity

3. Fraud Detection

Detects:

GPS spoofing

Fake claims

Duplicate claims

Uses anomaly detection models

Key Features
------------------------------------------------------------------------------------------------------------------------------------------------------------

AI-powered risk prediction

Dynamic weekly pricing model

Hyper-local disruption detection

Zero-touch automated claims

Fraud detection using machine learning

Worker and admin dashboards

Weekly Pricing Model
------------------------------------------------------------------------------------------------------------------------------------------------------------
Risk Level	Weekly Premium	Coverage
Low	₹20	₹500
Medium	₹40	₹1000
High	₹70	₹2000

Designed for gig workers
Matches weekly earning cycles

Parametric Triggers
------------------------------------------------------------------------------------------------------------------------------------------------------------
Trigger Type	Condition	Payout
Rain	> 50mm rainfall	₹300
Heat	> 40°C	₹200
Pollution	AQI > 300	₹250
Curfew	Government alert	₹500

Tech Stack
------------------------------------------------------------------------------------------------------------------------------------------------------------

Frontend

React.js, Tailwind CSS

Backend

Node.js, Express.js

Database

MongoDB

AI/ML

Python, Scikit-learn, Pandas

APIs

OpenWeather API, AQI API (Mock), Google Maps API

Payments

Razorpay Sandbox

Target Persona
------------------------------------------------------------------------------------------------------------------------------------------------------------

Food delivery partners working with:

Swiggy

Zomato

These workers:

Depend on daily income

Work outdoors

Are highly affected by environmental disruptions

Accomplishments
------------------------------------------------------------------------------------------------------------------------------------------------------------

Designed a fully automated insurance system

Created a weekly pricing model for gig workers

Integrated AI for pricing and fraud detection

Built a scalable architecture for real-world deployment

What We Learned
------------------------------------------------------------------------------------------------------------------------------------------------------------

Understanding parametric insurance systems

Applying AI in financial risk modeling

Designing solutions for gig economy users

Handling real-time automation workflows

Challenges Faced
------------------------------------------------------------------------------------------------------------------------------------------------------------

Defining accurate disruption thresholds

Designing a simple but effective pricing model

Simulating real-time APIs

Planning fraud detection systems

Future Scope
------------------------------------------------------------------------------------------------------------------------------------------------------------

Real-time API integration

Advanced fraud detection models

Mobile app development

Predictive analytics dashboard

Integration with delivery platforms

Expected Impact
------------------------------------------------------------------------------------------------------------------------------------------------------------

DeliveryShield AI ensures:

Financial stability for gig workers

Reduced income uncertainty

Faster and fair insurance payouts

Empowering the backbone of India’s digital economy

Adversarial Defense & Anti-Spoofing Strategy
------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Differentiation Between Genuine and Fraudulent Users

DeliveryShield AI uses a multi-layer verification system to distinguish between legitimate delivery partners and malicious actors using GPS spoofing.

Instead of relying solely on GPS location, the system analyzes behavioral and activity patterns, such as:

Continuous movement patterns during delivery hours

Order activity consistency

Route behavior and travel speed

Device motion signals

A genuine delivery partner will show natural movement patterns, active delivery logs, and consistent behavior, whereas spoofed users often show static or unrealistic movement patterns.

2. Data Points Used for Fraud Detection
------------------------------------------------------------------------------------------------------------------------------------------------------------

To detect coordinated fraud attempts, the system evaluates multiple data sources:

GPS trajectory history (not just current location)

Device sensor data (accelerometer, motion patterns)

App activity logs (order pickups, drop-offs)

Time-based behavior patterns

Network data anomalies (sudden location jumps)

Weather correlation check (matching real environmental conditions)

Cluster detection for identifying multiple users showing identical suspicious patterns

This multi-dimensional analysis makes it extremely difficult for fraudsters to bypass the system using simple spoofing tools.

3. User Experience Balance (Fairness for Genuine Workers)
------------------------------------------------------------------------------------------------------------------------------------------------------------

To ensure genuine workers are not penalized:

Claims are not immediately rejected, but flagged for secondary validation

A grace threshold is applied for minor inconsistencies (e.g., network drops)

Users can be temporarily marked as “Under Review” instead of blocked

The system uses confidence scoring, where only high-risk anomalies are rejected

Manual or semi-automated review can be triggered for edge cases

This approach ensures a balance between strong fraud prevention and fair treatment of honest workers.
