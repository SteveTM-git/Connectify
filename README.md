<p align="center">
  <img src="https://img.icons8.com/?size=512&id=98957&format=png" width="80" />
</p>

<h1 align="center">Connectify</h1>

<p align="center">
  A clean, modern Flutter + Firebase social platform for sharing posts, comments, and campus updates.<br>
  Built with beautiful UI, animations, and real-time Firestore integration.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.19-blue?logo=flutter" />
  <img src="https://img.shields.io/badge/Firebase-Firestore-orange?logo=firebase" />
  <img src="https://img.shields.io/badge/Dart-3.0-blue?logo=dart" />
  <img src="https://img.shields.io/badge/Platform-Android%20|%20iOS-green" />
</p>

---

## 🚀 About the App

**Connectify** is a lightweight social feed application built using **Flutter** and **Firebase**.  
Users can:

- Register & Login securely  
- Create text posts  
- View posts in real-time  
- Like posts  
- Comment on posts (subcollection architecture)  
- Toggle Dark/Light mode  
- View profiles  
- Enjoy smooth page transitions and clean UI animations  

Built specifically to showcase **Flutter, Firebase, UI/UX, and real-time app development skills** for campus placements & recruiters.

---

## ✨ Features

### 🔐 Authentication
- Firebase Email/Password login  
- Secure session handling  
- Profile section with logout  

### 📝 Posts
- Create and share updates  
- Real-time Firestore sync  
- Animated feed list  
- Timeago timestamps  
- Smooth fade + slide transitions  

### 💬 Comments
- Nested Firestore subcollection:  
  `/posts/{postId}/comments/{commentId}`  
- Real-time comments  
- Uses user’s display name  

### 🎨 Modern UI/UX
- Gradient AppBar  
- Rounded cards with shadows  
- Lottie-based splash (optional)  
- Animated navigation  
- Floating action button animation  

### 🌙 Theming
- Dynamic Light/Dark mode  
- Persistent theme state via provider  

---

## 📸 Screenshots


| Home Feed (Light) |
|-------------------|
| <img width="309" height="678" alt="Screenshot 2025-11-13 at 11 09 47 AM" src="https://github.com/user-attachments/assets/8215c421-cfef-4074-a315-c4762c67814c" />
 

| Create Post | 
|-------------|
| <img width="306" height="676" alt="Screenshot 2025-11-13 at 11 10 28 AM" src="https://github.com/user-attachments/assets/fe7dd032-b1ee-46d4-b1ba-3b66bf566e3b" />
|Comments |
 | <img width="302" height="664" alt="Screenshot 2025-11-13 at 11 24 08 AM" src="https://github.com/user-attachments/assets/66ed5591-8fbc-438d-9ecc-edc92a73b0d8" />
 

| Login Screen | 
|--------------|
| <img width="305" height="673" alt="Screenshot 2025-11-13 at 11 10 54 AM" src="https://github.com/user-attachments/assets/cb6c033a-aadc-43f2-94cb-a4d74a70fb22" />
|Register Screen|
|               |
 |<img width="309" height="683" alt="Screenshot 2025-11-13 at 11 11 07 AM" src="https://github.com/user-attachments/assets/df89e3df-9e50-432b-a488-ce4df25cc5fc" />

| Firebase |
|----------|
|<img width="1142" height="650" alt="image" src="https://github.com/user-attachments/assets/55bb060d-74f1-4355-8e4f-c5668b4eb02f" />


---

## 🧑‍💻 Tech Stack

### **Frontend**
- Flutter  
- Dart  
- Provider (State Management)  
- Animations (AnimatedScale, PageRouteBuilder, FadeTransition)  

### **Backend**
- Firebase Auth  
- Firebase Firestore  
- Firebase Core  

### **Architecture**
- MVC-ish clean separation  
- Services: AuthService  
- Screens: Feed, Profile, Create Post, Comments  
- Providers: ThemeProvider  

---

## 📂 Folder Structure

lib/
├── screens/
│ ├── feed_screen.dart
│ ├── create_post_screen.dart
│ ├── comments_screen.dart
│ ├── profile_screen.dart
│ └── login & register screens
│
├── services/
│ └── auth_service.dart
│
├── utils/
│ └── animated_page_route.dart
│
├── theme_provider.dart
├── main.dart
└── firebase_options.dart (ignored in .gitignore)

---

## 🛠️ Setup & Installation

### Prerequisites
- Flutter SDK installed  
- Firebase project created  
- Android Studio / Xcode configured  

### 🔧 Clone the repository

```bash
git clone https://github.com/SteveTM-git/Connectify.git
cd Connectify
red in .gitignore for security.

🌐 GitHub: SteveTM-git
