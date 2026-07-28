<h1 align="center">🍽️ Restro — Restaurant Reservation System</h1>

<p align="center">
  A cross-platform Flutter app for browsing menus, booking restaurant reservations, and managing bookings in real time.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

---

## 📖 Overview

Restro is a full-stack mobile reservation platform built with **Flutter** and **Firebase**. It lets users create an account, browse a restaurant's menu, and book a table, while giving admins the tools to manage reservations and track activity through a live analytics dashboard.

## ✨ Features

- 🔐 **User Authentication** — Secure sign-up/login via Firebase Authentication
- 📅 **Reservation Booking** — Real-time table booking backed by Cloud Firestore
- 🍕 **Menu Browsing** — Menu data loaded from a structured JSON asset
- 📸 **Image Uploads** — Profile/menu image uploads via `image_picker`
- 📧 **Email Notifications** — Automated reservation confirmations via the `mailer` package
- 📊 **Analytics Dashboard** — Visual booking insights using `fl_chart`
- 📶 **Offline Awareness** — Connectivity monitoring via `connectivity_plus`
- 💾 **Local Preferences** — Persisted user settings with `shared_preferences`
- 🔗 **Deep Linking** — External links (maps, calls) handled via `url_launcher`

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | Flutter (Dart) |
| **Backend / Auth** | Firebase Authentication, Cloud Firestore |
| **State Management** | Provider |
| **Notifications** | Mailer (SMTP email) |
| **Charts & Analytics** | fl_chart |
| **Other** | image_picker, path_provider, shared_preferences, connectivity_plus, url_launcher |

## 🏗️ Architecture

```
restro/
├── lib/                  # App source (screens, widgets, services, models)
├── assets/
│   ├── images/           # App image assets
│   └── menu_data.json    # Menu content
├── android/ / ios/       # Platform-specific runners
├── firebase.json         # Firebase project configuration
└── pubspec.yaml          # Dependencies & asset registration
```

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart ≥ 3.3.3)
- A configured [Firebase project](https://firebase.google.com/docs/flutter/setup) with Authentication and Firestore enabled

### Installation

```bash
# Clone the repository
git clone https://github.com/hiten-patil/Restaurant_reservation_system.git
cd Restaurant_reservation_system

# Install dependencies
flutter pub get

# Connect your Firebase project (generates firebase_options.dart)
flutterfire configure

# Run the app
flutter run
```

## 📱 Screens (planned/implemented)

- Sign up / Login
- Menu browsing
- Table reservation & booking confirmation
- User profile & reservation history
- Admin analytics dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes and open a Pull Request

## 📝 License

This project is available under the MIT License.

---

<p align="center">Built with ❤️ using Flutter & Firebase</p>
