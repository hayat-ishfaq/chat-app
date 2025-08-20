
# 💬 NexTalk – Modern Flutter Chat App

NexTalk is a **real-time chat application** built with **Flutter** and **Firebase**.  
It comes with **dual authentication (Email/Password & Google Sign-In)**, a **WhatsApp-inspired UI**, and a **clean MVVM architecture** using **Provider**.  
The app supports **light/dark themes**, **push notifications**, and delivers a smooth messaging experience across Android & iOS.

---

## ✨ Features

- 🔐 **Authentication** – Email/Password & Google Sign-In  
- 💬 **Realtime Chat** – One-to-one messaging with bubble-style UI  
- 🎨 **Dynamic Theming** – Gradient themes + Dark/Light mode  
- 🔍 **Search** – Find users & conversations instantly  
- 📱 **Material 3 UI** – Modern design with animations  
- 🔔 **Push Notifications** – Powered by Firebase Cloud Messaging  
- 🏗️ **MVVM Architecture** – Scalable & maintainable project structure  

---

## 📂 Project Structure

```

lib/
├── main.dart
├── models/                # Data models
├── services/              # Firebase services (auth, chat)
├── viewmodels/            # Business logic & state management
├── views/                 # Screens (login, chat list, chat detail)
├── widgets/               # Reusable UI widgets
└── utils/                 # Theme & utilities

````

---

## 🛠️ Tech Stack

- **Flutter (Dart)**  
- **Firebase (Auth, Realtime DB, Cloud Messaging)**  
- **Provider** – State management  
- **Material Design 3**  
- **Google Sign-In**  

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK `>=3.8.1`  
- Firebase project with **Auth** + **Realtime Database** enabled  

### Installation
```bash
# Clone repo
git clone https://github.com/M-Attaullah/Chat-App.git
cd Chat-App

# Install packages
flutter pub get

# Run app
flutter run
````

👉 Add `google-services.json` (Android) & `GoogleService-Info.plist` (iOS) before running.

---

## 📦 Dependencies

```yaml
firebase_core: ^2.30.0
firebase_auth: ^4.17.8
firebase_database: ^10.4.8
firebase_messaging: ^14.7.20
google_sign_in: ^6.2.1
provider: ^6.1.2
connectivity_plus: ^5.0.2
flutter_local_notifications: ^17.0.0
intl: ^0.19.0
uuid: ^4.3.3
```

---

## 🔮 Roadmap

* [ ] 📸 Media sharing (images, videos)
* [ ] 👥 Group chats
* [ ] 🎵 Voice messages
* [ ] 📍 Location sharing
* [ ] 🔔 Custom notification settings
* [ ] 📊 Read receipts
* [ ] 🌍 Multi-language support
* [ ] 🔒 End-to-end encryption

---

## 👤 Author

**Hayat Ishfaq**
📌 [GitHub](https://github.com/hayat-ishfaq)

---

> 🚀 Built as a showcase of **MVVM architecture**, **Firebase integration**, and **modern Flutter UI** with real-time chat.

```

---

This is now in a **clean README format** like you’d see on GitHub.  
Want me to also add some **badges** (e.g., Flutter version, Firebase, license) at the top to make it look even more professional?
```
