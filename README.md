# 🚭 Stop Smoking

**Stop Smoking** is a Flutter application designed to help users track their progress while quitting smoking.  
The app calculates key metrics like time since last cigarette, money saved, cigarettes avoided, and provides motivational insights to support the user's journey to quit smoking.

---

## 📌 Features

- 🕒 **Time counter** — Shows how long it’s been since the last cigarette.
- 💸 **Money saved** — Calculates money saved by not buying cigarettes.
- 🚬 **Cigarettes avoided** — Tracks how many cigarettes you’ve avoided.
- 📈 **Progress & Statistics** — Displays progress over days, weeks, and months.
- 🎯 **Motivational info** — Health and financial benefits of quitting smoking over time.
- 📱 Built with Flutter — can run on Android, iOS, Web, Windows, macOS, and Linux.

---

## 🧰 Screenshots

<p float="left">
  <img src="lib/homepage.png" alt="Home" width="200" />
  <img src="lib/chatbot.png" alt="Chatbot" width="200" />
  <img src="lib/3.png" alt="Progress" width="200" />
  <img src="lib/4.png" alt="Settings" width="200" />
</p>

---

## 🚀 Getting Started

These instructions will help you set up this project locally.

### Prerequisites

Make sure you have the following installed:

- Flutter SDK  
- Android Studio or VS Code  
- A connected device or emulator

### 🧩 Installation and Setup

1. **Clone the repository**

```bash
git clone https://github.com/abdelhalimramadan/stop_smoking.git
```
2. **Navigate into the project directory**
```
cd stop_smoking
```

3. **Install dependencies**
   ```
   flutter pub get
   ```

4. **Run the app**
   ```
      flutter run
   ```

## 📦 Project Structure
```
stop_smoking/
├─ android/
├─ ios/
├─ lib/
│  ├─ main.dart
│  ├─ screens/
│  ├─ widgets/
│  └─ utils/
├─ web/
├─ test/
├─ pubspec.yaml
├─ README.md
└─ .gitignore
```
## 🛠 Dependencies
dependencies:
```
  flutter:
    sdk: flutter
  flutter_localizations:
    sdk: flutter

  # Core dependencies
  cupertino_icons: ^1.0.6

  # HTTP and networking
  http: ^1.1.0

  # Local storage
  shared_preferences: ^2.2.2
  sqflite: ^2.3.0
  path: ^1.8.3

  # Notifications
  flutter_local_notifications: ^16.3.2
  timezone: ^0.9.2

  # Date and time
  intl: ^0.20.2

  # State management
  provider: ^6.1.1

  # UI components
  flutter_svg: ^2.0.9
  cached_network_image: ^3.3.0
  shimmer: ^3.0.0

  # Charts and graphs
  fl_chart: ^0.65.0

  # Utilities
  uuid: ^4.2.1
  url_launcher: ^6.2.2
  device_info_plus: ^9.1.1
  package_info_plus: ^4.2.0

  # Permissions
  permission_handler: ^11.1.0

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^3.0.1
  build_runner: ^2.4.7
```
## 🙌 Acknowledgements

Thanks to everyone who contributes and uses this app. Built with ❤️ and Flutter.
