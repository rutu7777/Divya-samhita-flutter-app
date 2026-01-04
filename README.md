# 🌺 Divya Samhita

**Divya Samhita** is a Flutter-based mobile application that helps users discover
eternal wisdom from ancient Indian scriptures using simple keyword-based search.

The app presents verses from the **Bhagavad Gita**, **Sant Tukaram Maharaj**, and
**Sant Dnyaneshwar Maharaj**, making ancient teachings accessible for modern life.

---

## ✨ Features

- 🔍 Keyword-based verse search (Life, Karma, Peace, Ego, Love, etc.)
- 📜 Multiple verse results for a single keyword
- 🧠 Handles both single-word and long questions gracefully
- 📦 Offline data using JSON assets
- 🎨 Elegant UI with gradients, cards, and smooth layout
- 📱 Clean navigation with welcome and home screens
- 🕉 Sanskrit verses with explanations for better understanding

---

## 🛠 Tech Stack

- **Flutter** – Cross-platform mobile development
- **Dart** – Programming language
- **Material UI** – UI components & styling
- **JSON** – Offline data storage
- **Android SDK** – Mobile deployment

---

## 📂 Project Structure

divya-samhita-flutter/
│
├── assets/
│ └── data/
│ └── verses.json
│
├── lib/
│ ├── models/
│ │ └── verse.dart
│ ├── services/
│ │ └── data_service.dart
│ ├── screens/
│ │ ├── welcome_screen.dart
│ │ └── home_screen.dart
│ └── main.dart
│
├── pubspec.yaml
└── README.md



---

## ▶️ How to Run the App (Step-by-Step)

### 🔹 Prerequisites
- Flutter SDK installed  
  👉 https://flutter.dev/docs/get-started/install
- Android Studio or VS Code
- Android Emulator **or** Physical Android Device
- USB Debugging enabled (for real device)

---

### 🔹 Step 1: Clone the Repository
---
🔹 Step 2: Install Dependencies
---
flutter pub get
---
🔹 Step 3: Check Flutter Setup
---
flutter doctor
---
Make sure there are no critical errors.

🔹 Step 4: Run the App
Option A: Using Emulator
flutter run
Option B: Using Physical Device
Connect phone via USB
Enable USB Debugging

flutter run
🔹 Step 5: Hot Reload (Optional)
Press r → Hot Reload

Press R → Hot Restart

📸 UI Highlights
Calm spiritual gradients

Elegant verse cards

Minimal typography

Distraction-free experience

🧩 Current Limitations
Limited verse dataset

Keyword-based matching only

🔮 Future Enhancements
AI-based semantic search

Larger scripture database

Multi-language support

Audio verse recitation
