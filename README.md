# 🌊 LocalPulse – Community Reporting App

> A modern Flutter-based community issue reporting platform that allows users to report local problems, explore nearby events, and stay connected with their community in real time.

## 🚀 Features

### 📢 Community Feed

* Post and view local issues
* Upvote important reports
* Comment in real-time
* Filter by category (Water, Road, Electricity, etc.)
* Search issues instantly

### 🧭 Location-Based Reporting

* Auto-detect current location
* Manual location picker
* Latitude & longitude tracking
* Location-based issue tagging

### 📸 Media Support

* Upload images from gallery or camera
* Attach photos to reports

### 🗓️ Events Module

* View nearby community events
* Create events with details
* Refresh & real-time updates

### 👤 User System

* Login / Register authentication
* Persistent login using SharedPreferences
* User profile with personal posts

### 📊 Profile Dashboard

* User details (phone, address)
* My posts history
* Activity overview

---

## 🛠️ Tech Stack

### Frontend

* Flutter (Dart)
* Material UI (custom themed)
* Image Picker
* Geolocator & Geocoding

### Backend

* FastAPI (Python)
* REST APIs
* JSON-based communication

### Storage

* SharedPreferences (local session)
* Backend database (API-driven)

---

## 📱 App Screens

* 🔐 Splash Screen (Animated)
* 🔑 Login / Register Screen
* 🏠 Home (Bottom Navigation)
* 📰 Feed Screen
* 📢 Report Issue Screen
* 🗓️ Events Screen
* 👤 Profile Screen

---

## 🎨 UI Highlights

* Modern purple gradient theme 🎨
* Card-based clean layout
* Smooth animations & transitions
* Responsive design
* Consistent design system across all screens

---

## 📂 Project Structure

```
lib/
│
├── screens/
│   ├── splash_screen.dart
│   ├── login_screen.dart
│   ├── home_screen.dart
│   ├── feed_screen.dart
│   ├── report_screen.dart
│   ├── events_screen.dart
│   ├── profile_screen.dart
│
├── services/
│   ├── api_service.dart
│
├── models/
│   ├── event_model.dart
│
├── widgets/
│   ├── event_card.dart
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/localpulse.git
cd localpulse
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Run the app

```bash
flutter run
```

---

## 🔌 Backend Setup

Make sure your FastAPI backend is running:

```bash
uvicorn main:app --reload
```

Update base URL in Flutter:

```dart
final String baseUrl = "http://YOUR_IP:8000";
```

---

## 📸 Screenshots

> Add your screenshots here

```
![Login](assets/login.png)
![Feed](assets/feed.png)
![Report](assets/report.png)
```

---

## 💡 Future Improvements

* 🔔 Push notifications
* 🗺️ Map-based issue tracking
* 🤖 AI issue categorization
* 🏆 User leaderboard system
* 🌐 Live chat for community updates

---

## 👨‍💻 Author

**Manas**
Flutter Developer | Full Stack Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it with others!

