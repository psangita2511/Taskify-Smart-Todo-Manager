# Taskify-Smart-Todo-Manager

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue)
![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-orange)
![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-purple)
![DI](https://img.shields.io/badge/DI-Hilt-red)

A modern, scalable Android Todo application built using Clean Architecture and the latest Android development best practices.

---

## 📌 Overview

Taskify is a production-ready task management application designed to demonstrate:

- Clean Architecture implementation
- SOLID principles
- MVVM pattern
- Jetpack Compose UI
- Hilt for Dependency Injection
- Room database with KSP
- Background task handling using WorkManager
- Material 3 design system

This project reflects real-world Android development standards and scalable project structure.

---

## ✨ Features

- ✅ Add new tasks
- ✏️ Edit tasks
- 🗑 Delete tasks
- ✔️ Mark tasks as completed
- 📂 Create and manage task categories
- 💾 Persistent local storage using Room
- ⚡ Optimized compilation using KSP
- 🔄 Background task support (WorkManager)
- 🎨 Clean Material 3 UI

---

## 📸 Screenshots

### 🏠 Home Screen
![Home Screen](screenshots/home_screen.jpeg)

### ➕ Add Task Screen
![Add Task Screen](screenshots/add_task_screen.jpeg)

### 📂 Show Category Screen
![Show Category Screen](screenshots/show_category_screen.jpeg)

### ➕ Add Category Screen
![Add Category Screen](screenshots/add_category_screen.jpeg)

---

## 🏗 Architecture

This project follows Clean Architecture principles:

Presentation Layer  
→ Jetpack Compose UI  
→ ViewModel (MVVM)

Data Layer  
→ Repository Pattern  
→ Room Database  
→ DAO

Dependency Injection is handled using Hilt.

Room database uses Kotlin Symbol Processing (KSP) for improved build performance.

WorkManager is used for background task execution.

---
com.mahantkrupa.taskify
│
├── data
│ ├── dao
│ ├── database
│ ├── entity
│ ├── mechanism
│ ├── repository
│ ├── workmanager
│
├── di
│ ├── AppModule.kt
│ ├── DataModule.kt
│ ├── UiModule.kt
│
├── ui
│ ├── addTask
│ ├── categories
│ ├── edit
│ ├── home
│ ├── landingpage
│ ├── maincontent
│ ├── nav
│ ├── theme
│ ├── utils

This modular structure ensures scalability, maintainability, and separation of concerns.

---

## 🛠 Tech Stack

- Kotlin
- Jetpack Compose
- MVVM Architecture
- Clean Architecture
- Hilt (Dependency Injection)
- Room Database
- KSP (Kotlin Symbol Processing)
- WorkManager
- Material 3

---

## 🚀 Future Improvements

- Task priority levels
- Reminder notifications
- Dark mode support
- Firebase cloud sync
- Search & filtering

---

## 👩‍💻 Author

**Sangita Patel**  
Android Developer (8+ Years Experience)  
Founder – Mahant Krupa Technologies  

---

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub.

