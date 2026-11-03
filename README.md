# FacilPay Mobile

👋 **Welcome to FacilPay** — Revolutionizing Web3 Chat, Payment, and DeFi Banking.

FacilPay is a message-centric payment platform built on user-intent blockchain technology for both Web3 veterans and everyday users. Whether crypto or fiat, sending and receiving money is as seamless as sending or receiving a text message.

---

## 📁 Project Architecture (Portfolio Showcase)

> **Note:** To respect company confidentiality and intellectual property, proprietary business logic and internal credentials have been omitted from this public repository. The complete directory tree, modular feature structure, and `.dart` file layout are preserved to showcase the application's architecture and engineering contributions.

```text
lib/
├── app/                  # Environment & app-level configuration
├── feature/              # Feature-first modular architecture
│   ├── auth/             # Authentication, OTP verification, onboarding & state providers
│   ├── chat/             # Web3 messaging, in-chat crypto/fiat transfers & wallet resolution
│   ├── contacts/         # Contact synchronization & user discovery
│   ├── home/             # Main navigation shell & dashboard views
│   ├── notifications/    # Push & local notification handling
│   ├── onboarding/       # User onboarding flows
│   ├── profile/          # User profile & account management
│   ├── qr_scanner/       # QR code scanning for wallet addresses & payments
│   ├── savings/          # DeFi savings & yield features
│   ├── settings/         # Security, preferences & account settings
│   └── wallet/           # Multi-chain wallet (Solana, Stellar, EVM), token swaps & off-ramp
├── network/              # Dio HTTP client, interceptors & WebSocket services
├── Screens/              # Core application screens
├── services/             # Shared platform & cryptographic services
├── shared/               # Reusable UI components, validators, extensions & error handlers
├── main.dart             # Application entry point
└── routes.dart           # Centralized routing configuration
```

---

## 🛠 Tech Stack & Key Integrations

- **Framework:** Flutter & Dart
- **State Management:** Riverpod (`flutter_riverpod`, `riverpod_annotation`)
- **Networking & Real-Time:** `dio`, `web_socket_channel`
- **Blockchain & Web3:**
  - **Solana:** `solana`, `ed25519_hd_key`
  - **Stellar:** `stellar_flutter_sdk`, `stellar_asset_lists`
  - **EVM / HD Wallets:** `web3dart`, `bip39`, `dart_bip32`
- **Security & Storage:** `encrypt`, `crypto`, `hive`, `shared_preferences`
- **Notifications & Firebase:** `firebase_core`, `firebase_messaging`, `flutter_local_notifications`
