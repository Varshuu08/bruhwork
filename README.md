# 🚀 BruhWork

**BruhWork** is a productivity app built for people who *want* to be productive but somehow end up scrolling instead.
It combines **task management**, **streak tracking**, and **brutally honest feedback** to help users stay consistent — without toxic hustle culture.

> Productivity, but honest.

---

## 🧠 Why BruhWork?

Most productivity apps:

* Feel boring or strict
* Shame users for missing goals
* Get uninstalled after 3 days

**BruhWork does the opposite**:

* Encourages progress over perfection
* Uses humor & roasting instead of guilt
* Focuses on consistency, not motivation

---

## ✨ Features

### ✅ Core Features

* 📋 **Smart Task Management**
  Break work into realistic, doable tasks.

* 🔥 **Daily Streaks**
  Track consistency. Miss a day? Fine. Quit? No.

* 📊 **Honest Dashboard**
  See completed vs pending tasks, streaks, and time insights.

* 👤 **Profile Management**
  Edit profile details, avatar, and productivity score.

* 👥 **Friends Preview (WIP)**
  See friends’ streaks for accountability and motivation.

* 📴 **Offline-first (Local Storage)**
  Works without internet using local storage.

---

## 🔮 Upcoming Features

* ☁️ Firebase Cloud Sync
* 🤝 Real Friends System
* 🏆 Leaderboards
* 🤖 AI Productivity Insights
* 🎨 Custom Themes
* 😈 Ultra Roast Mode

---

## 💰 Pricing (Planned)

| Plan      | Price        | Features                                               |
| --------- | ------------ | ------------------------------------------------------ |
| **Basic** | Free         | Tasks, streaks, dashboard, offline usage               |
| **Pro**   | ₹199 / month | Analytics, cloud backup, friends leaderboard           |
| **Ultra** | ₹399 / month | AI insights, custom themes, early access, savage roast |

---

## 🛠 Tech Stack

* **Flutter** (UI & logic)
* **Dart**
* **SharedPreferences** (local storage)
* **Firebase (in progress)**

  * Firebase Authentication
  * Cloud Firestore
  * Firebase Storage

---

## 📁 Project Structure

```
lib/
 ├── pages/
 │    ├── intro_page.dart
 │    ├── auth_page.dart
 │    ├── dashboard_page.dart
 │    ├── profile_page.dart
 │    └── tasks_page.dart
 ├── models/
 │    ├── task.dart
 │    └── user_profile.dart
 ├── services/
 │    ├── task_storage.dart
 │    └── streak_service.dart
 ├── bottom_nav.dart
 └── main.dart
```

---

## 🚧 Project Status

🟡 **Active Development**

* UI & core features: ✅ Completed
* Firebase Auth: 🔄 In progress
* Cloud storage: ⏳ Planned
* Friends system: ⏳ Planned

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK
* Dart
* Android Studio / VS Code

### Run Locally

```bash
flutter pub get
flutter run
```

---

## 🔐 Security Note

Firebase config files are **ignored via `.gitignore`** to avoid exposing secrets:

* `google-services.json`
* `GoogleService-Info.plist`

---

## 🤝 Contributing

This is a personal learning + product project.
Suggestions and improvements are welcome via Issues.

---

## 📜 License

This project is for **educational and personal use**.
Commercial use to be decided later.

---

## 🙌 Final Note

BruhWork isn’t about becoming perfect.
It’s about showing up — even when you don’t feel like it.

**Stop procrastinating. Maybe.** 😌
