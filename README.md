# MandiSense: AI-Powered Market Intelligence for KR Market

![MandiSense Header](https://raw.githubusercontent.com/username/repo/main/assets/banner.png)

MandiSense is a state-of-the-art Flutter application designed to empower small-scale vendors and farmers in the Bangalore KR Market. By leveraging real-time cloud synchronization and advanced AI insights, MandiSense transforms raw market data into actionable business intelligence.

## 🌟 Key Features

- **Real-Time Market Prices**: Live synchronization with a Supabase cloud database for the most accurate KR Market data.
- **AI Expert Assistant**: A hybrid intelligence engine (Gemini 1.5 Flash + Local Logic) that provides expert advice even in offline conditions.
- **Digital Slate (Calculation Tool)**: Automate complex profit margin calculations, waste management, and suggested RRP (Recommended Retail Price).
- **Price Trend Analytics**: Visual indicators of price fluctuations (Rising/Falling) over 24 hours.
- **Dual-Language Support**: Fully localized in **English** and **Kannada** (ಕನ್ನಡ) for local accessibility.
- **Offline-First Resilience**: Robust fallback mechanisms ensuring the app works perfectly regardless of connectivity.

## 🚀 Quick Start

### Prerequisites
- Flutter SDK (v3.19+)
- Android Studio / VS Code
- Supabase Account
- Google AI (Gemini) API Key

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nandan/mandisense.git
   cd mandisense
   ```

2. **Environment Configuration**:
   Create a file at `assets/app.env` with the following variables:
   ```env
   GEMINI_API_KEY=your_gemini_key
   SUPABASE_URL=your_supabase_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

3. **Install Dependencies**:
   ```bash
   flutter pub get
   ```

4. **Build Production APK**:
   ```bash
   flutter build apk --release --no-tree-shake-icons
   ```

## 🛠️ Technology Stack

- **Frontend**: Flutter (Dart)
- **Backend**: Supabase (PostgreSQL, Real-time)
- **AI Engine**: Google Gemini 1.5 Flash (via REST API)
- **State Management**: BLoC (Business Logic Component)
- **Local Persistence**: Flutter Secure Storage & Env-loading

## 📁 Project Structure

```text
lib/
├── core/           # Constants, Theme, Config
├── data/           # Models, Services, Repositories
├── presentation/   # Screens, BLoCs, Widgets
├── l10n/           # English & Kannada Translations
└── main.dart       # Application Entry Point
```

## 📄 Documentation

For detailed information, please refer to:
- [Project Guide & Installation](docs/PROJECT_GUIDE.md)
- [Presentation Guide (Slide-by-Slide)](docs/PRESENTATION_GUIDE.md)
- [Technical Architecture](docs/TECHNICAL_ARCHITECTURE.md)

---
© 2026 MandiSense Team. All Rights Reserved.
