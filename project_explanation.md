# Project Explanation: MandiSense AI

MandiSense is a localized, AI-powered business companion for market vendors.

## 1. Core Mission
To digitize the "Traditional Mandi" experience by providing tools that were previously out of reach for small vendors.

## 2. Component Breakdown

### Market Prices (The "Ticker")
- Uses a **Supabase** backend to provide real-time pricing.
- Includes **percentage change** logic to show market trends.
- **Visuals**: Dynamic icons (Emojis) tailored to each product for fast recognition.

### AI Expert (The "Brain")
- **Gemini 1.5 Flash**: Processes complex vendor queries.
- **Local Logic**: A fallback system that ensures the AI is "always-on" even without internet, using the phone's last-known data.

### Digital Slate (The "Accounting")
- A custom-built calculator for Mandi-specific economics.
- Helps vendors avoid losses due to hidden transport costs or vegetable waste.

## 3. Deployment Ready
- Environment variables are bundled in `assets/app.env`.
- No tree-shake icons issue resolved.
- Full localization (English/Kannada) integrated.
