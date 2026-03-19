# GIGShield AI+

Hyperlocal AI-Powered Income Protection for Delivery Partners

## Problem Statement

Delivery partners in India’s gig economy often lose income due to external disruptions such as heavy rainfall, extreme heat, and high air pollution. These factors reduce their working hours and lead to significant weekly income loss. Currently, there is no system that compensates them for this loss of income.

## Target Persona

This solution is designed for a food delivery partner working with platforms like Swiggy or Zomato in Hyderabad.
A typical worker earns around ₹500 per day and works 8–10 hours. Their earnings are highly dependent on weather and environmental conditions.

## Proposed Solution

GIGShield AI+ is an AI-based parametric insurance platform that provides income protection on a weekly subscription basis. The system monitors external conditions and automatically triggers payouts when disruptions occur, without requiring manual claims.

## System Workflow

1. The user registers and provides basic details such as location and delivery platform.
2. The system calculates a risk score based on environmental and historical data.
3. Based on the risk score, suitable weekly plans are suggested.
4. The system continuously monitors weather conditions and pollution levels.
5. If predefined thresholds are crossed, a disruption is detected.
6. The claim is automatically initiated without user intervention.
7. Fraud checks are performed using location and activity validation.
8. The payout is processed instantly using a simulated payment system.
   
## Prototype

A simple frontend prototype is included to demonstrate the basic workflow of the system.

Features:
- Plan selection
- Monitoring system
- Claim trigger simulation

## How to Run the Prototype

1. Download or clone this repository
2. Open the project folder
3. Open the file `index.html` in any web browser

No installation is required.

## Persona-Based Scenario

Ravi, a delivery partner in Hyderabad, subscribes to a weekly plan. On a particular day, heavy rainfall exceeds the defined threshold. Ravi is unable to work for several hours. The system detects the event, verifies his location, and automatically credits the payout amount.

## Weekly Pricing Model

The platform follows a weekly pricing structure aligned with gig workers’ earning cycles.

* Lite Plan: ₹20 per week with limited coverage
* Flex Plan: ₹35 per week with moderate coverage
* Pro Plan: ₹50 per week with full coverage

This model ensures affordability and flexibility for workers.

## Parametric Triggers

The system uses predefined measurable conditions to trigger payouts:

* Rainfall greater than 20mm per day
* Temperature above 42°C
* Air Quality Index above 300
* Flood or severe disruption alerts (API or simulated data)

These triggers directly affect the ability of workers to perform deliveries.

## AI/ML Integration

### Risk Modeling

A risk score is calculated based on environmental factors such as rainfall, temperature, air quality, and historical disruption patterns.

### Dynamic Pricing

The weekly premium is adjusted based on the calculated risk score. Higher-risk areas may have higher premiums, while safer areas receive lower pricing.

### Predictive Analysis

The system can estimate the likelihood of disruptions in the coming days and provide alerts to users.

### Fraud Detection

The system checks for inconsistencies such as location mismatch, repeated claims, or unusual activity patterns using rule-based and anomaly detection methods.

## Platform Choice

A mobile-first approach is chosen since delivery partners primarily use smartphones during work. This ensures easy access, real-time notifications, and a simple user experience.
A web interface can be used for administrative monitoring and analytics.

## Tech Stack

Frontend: React.js
Backend: Python (Flask or FastAPI)
Database: Firebase or MongoDB
AI/ML: Python with scikit-learn
APIs: OpenWeather API or mock data
Payments: Razorpay test mode or simulated payment system

## Integration Plan

Weather APIs will be used to fetch real-time environmental data.
Mock data will be used to simulate delivery activity.
Payment systems will be simulated for demonstrating instant payouts.

## Key Highlights

- Fully automated claim system with zero manual effort
- Weekly pricing model tailored for gig workers
- AI-driven risk assessment and fraud detection

## Development Plan

Phase 1:
Ideation, requirement analysis, and system design

Phase 2:
Development of core features such as registration, plan selection, and claim triggering

Phase 3:
Integration of fraud detection, payment simulation, and dashboard features

## Future Scope

The system can be extended to multiple cities and different types of gig workers.
It can also be integrated with delivery platforms for real-time data access and improved accuracy.

## Conclusion

GIGShield AI+ provides a practical and scalable solution to protect the income of gig workers. By combining AI-based risk analysis with automated payouts, it ensures financial stability during unpredictable external disruptions.
