# 🔮 HoroscopoApp – Android Kotlin Application

HoroscopoApp is a modern Android application built in **Kotlin** that allows users to explore their horoscope, view detailed predictions, receive random “luck” tarot-style cards with animations, and access a palmistry guide using the device camera.

The project is structured following **Clean Architecture + MVVM**, leverages **Dependency Injection with Hilt**, and includes **Unit Tests and UI Tests** to ensure reliability and maintainability.

---

## ✨ Features

- ♈ Full zodiac horoscope list
- 📜 Daily horoscope prediction via API (Retrofit + Coroutines)
- 🎴 Random tarot-style “Lucky Card” animations
- ✋ Palmistry overlay guide using CameraX
- 🧭 Bottom Navigation with Navigation Component
- 🧩 Clean MVVM architecture with StateFlow
- 🛠️ Dependency Injection with Hilt
- 🧪 Unit Testing + Instrumented UI Testing

---

## 🏗 Architecture Overview

The project follows a layered architecture with clear separation of responsibilities:
data/
├─ network/
├─ providers/
domain/
├─ model/
ui/
├─ home/
├─ horoscope/
├─ detail/
├─ luck/
├─ palmistry/

---

**Key Principles**
- MVVM Pattern
- Separation of Concerns
- Single Responsibility Principle
- Reactive state handling with StateFlow
- Testability as a first-class concern

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Language | Kotlin |
| UI | ViewBinding |
| Architecture | MVVM + Clean principles |
| Networking | Retrofit + OkHttp + Interceptors |
| Concurrency | Coroutines + StateFlow |
| Dependency Injection | Dagger Hilt |
| Navigation | Jetpack Navigation Component |
| Camera | CameraX |
| Unit Testing | JUnit + MockK |
| UI Testing | Espresso |

---

## 🌐 Horoscope API

Predictions are fetched from the following public API:
https://aztro.sameerkumar.website

---

## 🧪 Testing

### ✅ Unit Tests
Includes testing for:
- ViewModels
- Data providers
- Response → Domain mapping
- Core business logic

### 📱 UI Tests
Built using:
- Espresso
- RecyclerView Actions
- Intent assertions
- Hilt testing utilities
- Custom Hilt Test Runner

---

