# AI-Based Crop Recommendation for Farmers

A hyper-local, profit-aware and explainable crop advisory platform for farmers, accessible through a mobile app, a WhatsApp chatbot and voice advisory in regional languages.

![Event](https://img.shields.io/badge/Event-GDG%20TechSprint-4285F4) ![Team](https://img.shields.io/badge/Team-HELL%20FIRE%20CLUB-red) ![Domain](https://img.shields.io/badge/Domain-AgriTech%20AI-green) ![Status](https://img.shields.io/badge/Status-Proposal-orange)

> Submission for the Google Developer Group On Campus **TechSprint: Leveraging the power of AI** hackathon. Team **HELL FIRE CLUB**, led by Payyavula Madhuri.

## Problem

Farmers lack a scientific, localized and profit-oriented decision-support system for choosing the right crop for their land. This leads to:

- Crop failures from unsuitable soil or weather
- Low income because of market price crashes
- Over-production of a single crop
- High dependency on subsidies and loans

### Gaps in existing solutions

1. They do not consider plot-level soil and climate variation
2. Advisories focus on yield, not future market prices
3. Recommendations come without explanation, so farmers do not know why a crop was suggested
4. Language and literacy barriers limit access

## Proposed Solution

| Capability | Approach |
|---|---|
| AI recommendation engine | Machine learning models (Random Forest / XGBoost) trained on soil, weather and crop datasets |
| Market-aware intelligence | Future crop price prediction from historical mandi data |
| Explainable AI | Shows how factors such as soil pH, rainfall and demand influenced each recommendation |
| Climate risk and crop rotation | Drought, flood and heatwave alerts, plus rotation and diversification suggestions |
| Multi-channel access | Mobile app, WhatsApp chatbot and voice advisory in regional languages |

## Process Flow

```
Farmer input (app / WhatsApp / voice)
  -> Location and soil data collection
  -> Weather and market data fetch
  -> AI recommendation engine
  -> Explainability layer
  -> Crop recommendation output
  -> Farmer feedback (post-harvest)
```

## Proposed Technology

As proposed in the submission:

- **Google Antigravity:** crop recommendation modelling, soil-crop suitability mapping, weather impact analysis and yield prediction
- **Firebase:** Authentication (farmer login), Firestore (crop, soil and recommendation data), Hosting (web dashboard) and Cloud Functions (API logic)

## Expected Impact

- Higher farmer income through profitable crop choices
- Lower crop failure risk
- More sustainable water usage
- Greater trust through transparent AI

## Status

This repository holds the idea-stage submission: problem statement, approach, features, process flow and architecture. The presentation is in `docs/`. Implementation is not included.

## Team

**HELL FIRE CLUB**

- Payyavula Madhuri (Team Leader)
- Konduru Mounika
