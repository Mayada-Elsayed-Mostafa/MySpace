# 📱 MySpace – Jetpack Compose Android App

A modern, modular Android application built with **Jetpack Compose**, designed to help users stay productive with features like task management, notes, motivational quotes, and secure authentication.  
This project integrates **Firebase**, **Room**, **Retrofit**, and follows **MVVM + Clean Architecture** principles.

---

## ✨ Features

### 🔐 Authentication
- Firebase Login with Email & Google
- Session management using DataStore

### 📝 To-Do Tasks
- Add / Edit / Delete tasks
- Mark tasks as done
- Filter tasks (All / Done / Pending)
- Stored locally using Room DB

### 📓 Notes
- Add / Edit / Delete notes
- Sort notes by title or date
- Room DB with ViewModel

### 💬 Daily Quotes
- Fetch motivational quotes from public API
- Refreshable with loading/error states
- Integrated with Retrofit + Coroutines

### ⚙️ Settings
- Dark / Light Theme toggle
- Language switch (EN / AR)
- Logout & user info

### 📲 Extra Features
- Task reminders with notifications
- Sync notes/tasks with Firebase Firestore
