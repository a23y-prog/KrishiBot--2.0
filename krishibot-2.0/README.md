# KrishiBot 2.0 — Smart Farming Companion

A polished, responsive React/Vite frontend prototype for a farming assistance hackathon demo.

## Run in VS Code

1. Install **Node.js LTS** from https://nodejs.org/ if it is not already installed.
2. Extract this folder and open `krishibot-2.0` in VS Code.
3. Open **Terminal → New Terminal**.
4. Run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local URL printed by Vite (usually `http://localhost:5173`).
6. To check the production build, run `npm run build`.

## Included interactive prototype areas

- Overview dashboard and demo weather/market snapshot
- AI assistant chat with simulated guidance
- Crop planner with filters and rule-based illustrative options
- Soil-test value entry, file picker, and demo review state
- Marketplace search, categories, seeded product listings, simulated seller enquiry
- Government benefits discovery cards (verify all details with official portals)
- Weather and alerts page with clearly labelled sample data
- Profit calculator using editable cost/revenue assumptions
- Community discussion mockups
- Farm profile and onboarding modal
- Feature-phone USSD-style interactive simulator
- Responsive sidebar, mobile layout, language preference control, toast messages

## Important prototype boundaries

This is a **frontend demo**, not a production agricultural service. Data is sample/illustrative. No real AI model, live weather, market price feed, soil lab integration, government database, SMS/IVR/USSD provider, phone call, user authentication, cloud database, payment, or live order processing is connected. The profile and form states remain in the current browser session only. Before using for real farming decisions, connect verified data providers and review advice with qualified local agricultural experts.

## Suggested next development steps

1. Add backend API and database (for example, Node/Express or Next.js + PostgreSQL).
2. Implement secure farmer/shopkeeper/admin authentication and role permissions.
3. Connect trusted weather, market price, and official scheme sources with timestamps and citations.
4. Store farm profiles, soil reports, enquiries, and listings securely.
5. Add SMS/IVR integration with a telephony provider and test regional-language accessibility.
6. Add admin moderation, validation, audit logs, privacy notice, and deployment monitoring.

## New module: AI Crop Disease Analysis

The sidebar now includes **Crop Disease Analysis**. Farmers can select a crop and growth stage, upload or capture a leaf image, preview it, and open an example results screen with cautious next steps.

**Important limitation:** the analysis result is simulated for UI demonstration. No image is sent to a model and no real disease prediction is performed. To make it genuine, connect a tested plant-disease image-classification model through a secure backend endpoint. Do not put provider API keys in front-end code. Validate the model on relevant regional crops and varieties, report uncertainty, and encourage expert confirmation before pesticide use.
