# figgy-ai-gig-worker-insurance
# FIGGY

### AI-Powered Parametric Income Insurance for Gig Workers

## Overview

FIGGY is an AI-powered parametric insurance platform designed to protect gig workers, particularly delivery partners, from income loss caused by external disruptions such as heavy rain, floods, pollution, strikes, or curfews.

Unlike traditional insurance systems that require manual claim filing and verification, FIGGY automatically detects disruptions using real-world data and triggers instant payouts when workers experience income loss.

The system also includes demand prediction intelligence to guide riders to high-demand delivery zones, helping them increase their earnings even before disruptions occur.

---

# Problem Statement

India's gig economy is rapidly growing, with millions of delivery partners working for platforms such as:

* Swiggy
* Zomato
* Zepto
* Amazon

These workers depend entirely on daily deliveries for income. However, external disruptions such as:

* Heavy rainfall
* Flooding
* Severe air pollution
* Local strikes or protests
* Government curfews

can reduce their working hours and earnings by **20–30%**.

Currently, gig workers have **no financial safety net** for such situations.

FIGGY addresses this gap by providing **automated parametric insurance and AI-driven income optimization**.

---

# Target Persona

### Example Worker Persona

**Name:** Ravi
**Role:** Swiggy Delivery Partner
**Location:** Chennai – T Nagar Zone
**Working Hours:** 6 hours/day
**Average Earnings:** ₹800/day

### Key Challenges

* Earnings fluctuate due to weather disruptions
* Idle time when demand is low
* No compensation for lost working hours
* No insurance support for gig workers

FIGGY provides Ravi with **income prediction, disruption protection, and automatic payouts**.

---

# Application Workflow

The FIGGY system operates through the following workflow:

### 1. Worker Onboarding

The delivery partner registers on the FIGGY platform.

Data collected includes:

* Worker ID
* Delivery platform
* Delivery zone
* Historical earnings
* Delivery count
* Working hours

---

### 2. AI Income & Premium Calculation

The system analyzes the worker's historical earnings and activity patterns to determine:

* Expected weekly income
* Risk score
* Insurance premium

---

### 3. Demand Prediction Engine

An AI model predicts **high-demand delivery zones 1–2 hours in advance**.

Inputs include:

* Time of day
* Weather conditions
* Local events
* Historical order data

Workers receive alerts such as:

“High delivery demand predicted in T Nagar from 7PM–9PM.”

This helps riders **increase their earnings**.

---

### 4. Disruption Detection

The platform continuously monitors disruptions using multiple data sources:

* Weather APIs
* Government alerts
* Social media signals
* News feeds

If a disruption such as heavy rain or pollution is detected, the system activates monitoring.

---

### 5. Worker Activity Verification

To prevent fraud, FIGGY verifies if the rider was actively working during the disruption.

Activity data includes:

* GPS movement
* App login status
* Delivery attempts
* Time spent in delivery zones

---

### 6. Parametric Claim Trigger

A payout is triggered only when two conditions are satisfied:

1. A disruption event is detected.
2. The worker was actively working but experienced reduced deliveries.

---

### 7. Income Loss Calculation

The system compares:

Expected Earnings vs Actual Earnings

Example:

Expected Earnings = ₹800
Actual Earnings = ₹250

Income Loss = ₹550

---

### 8. Instant Insurance Payout

The system compensates a portion of the loss.

Example:

Insurance Payout = ₹385

Final Earnings = ₹250 + ₹385 = ₹635

The payout is transferred instantly via:

* UPI
* Bank transfer
* Digital wallet

---

# Weekly Premium Model

FIGGY calculates weekly premiums dynamically based on worker income patterns and risk factors.

Factors considered:

* Average weekly income
* Delivery frequency
* Historical income stability
* Location risk
* Disruption probability

Example premium structure:

| Income Level  | Weekly Premium |
| ------------- | -------------- |
| Low Income    | ₹10            |
| Medium Income | ₹20            |
| High Income   | ₹35            |

This model ensures:

* affordability for workers
* fair risk distribution
* sustainable insurance pool

---

# Parametric Insurance Triggers

FIGGY uses predefined conditions to automatically trigger payouts.

### Weather Trigger

Rainfall > 40 mm/hour

### Pollution Trigger

AQI > 400

### Curfew or Strike

Government announcements or detected public disruptions.

### Worker Activity Requirement

The worker must be verified as active for at least:

3 working hours during the disruption period.

If both **disruption detection** and **verified activity** are confirmed, the claim is triggered automatically.

---

# AI / ML Integration

Artificial Intelligence plays a major role in FIGGY.

### 1. Premium Calculation Model

Predicts worker income stability and calculates insurance premiums.

Possible models:

* Random Forest
* Gradient Boosting
* XGBoost

---

### 2. Demand Prediction Model

Forecasts high-demand delivery zones.

Models used:

* XGBoost
* LSTM
* Facebook Prophet (time-series forecasting)

---

### 3. Fraud Detection System

Prevents fraudulent insurance claims using behavioral analysis.

Detection signals include:

* GPS movement consistency
* delivery attempt patterns
* idle activity detection

---

# Platform Choice (Web vs Mobile)

FIGGY is designed as a **mobile-first platform** because delivery workers rely primarily on smartphones while working.

Mobile app benefits:

* real-time disruption alerts
* GPS-based activity verification
* demand zone notifications
* instant payout updates

A **web dashboard** will be used for:

* admin analytics
* insurance monitoring
* disruption tracking

---

# Tech Stack

### Frontend

React
Tailwind CSS

### Backend

Node.js / Spring Boot

### AI & Machine Learning

Python
Scikit-learn
TensorFlow
Prophet

### Database

PostgreSQL
Redis

### APIs

Weather API
Maps API
Payment APIs

### Infrastructure

Docker
AWS / GCP

---

# Development Plan

### Phase 1 — Prototype Development

* Worker onboarding system
* demand prediction model
* weather disruption monitoring

### Phase 2 — Insurance Engine

* premium calculation module
* parametric trigger system
* fraud detection module

### Phase 3 — Platform Integration

* rider mobile interface
* admin analytics dashboard
* payment integration

---

# Expected Impact

FIGGY improves financial security for gig workers by:

* protecting against 20–30% income loss
* providing instant automated payouts
* improving delivery demand distribution
* reducing fraudulent claims

---

# Future Improvements

* Integration with delivery platforms (Swiggy, Zomato)
* Blockchain-based proof-of-work records
* Dynamic AI premium adjustment
* Multi-language support for workers

---

# License

MIT License
