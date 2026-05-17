# 🏆 ShredCountdown: The 6-Pack Goal Tracker

**ShredCountdown** is a gamified fitness application built with Kotlin and Jetpack Compose. Unlike traditional calorie trackers that reset every 24 hours, ShredCountdown treats your fat-loss journey like a **Boss Fight.** 

It calculates the total massive number of calories standing between you and a visible six-pack and provides a "Boss Health Bar" that you must chip away at until you reach the 1% goal.

## 🚀 The Hook
Most people quit their diets because they lose sight of the big picture. ShredCountdown creates **Radical Accountability.** If you overeat, the app adds those calories *back* to your total goal, showing you exactly how much your "cheat day" set back your timeline.

## ✨ Features
- **US Navy Body Fat Algorithm:** Scientifically-backed calculation using height, weight, waist, and neck measurements.
- **The "Boss Health Bar":** A persistent countdown of the total calories you need to burn to reach your target body fat percentage (defaulting to 10% for men and 18% for women).
- **Daily Victory/Setback Logic:** 
    - **Victory:** Hitting a deficit breaks a chunk off the Boss Bar.
    - **Setback:** Eating over your TDEE adds the surplus back to your total goal and resets your streak.
- **Victory Finale:** A celebratory screen with confetti, a hard-hitting motivational message, and a custom camera feature to take and share your "Shredded Selfie."
- **Privacy Focused:** All body measurements and progress photos are stored locally on the device.

## 🛠 Tech Stack
- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** MVVM (Model-View-ViewModel)
- **Camera:** CameraX API
- **Persistence:** DataStore / SharedPreferences
- **Animations:** Compose Animations & Infinite Transition for Confetti

## 📸 Screenshots
<p align="center">
  <img src="[screenshots/dashboard.png](https://github.com/Dhiman-Ajay/ShredCountdown/blob/37d707d9b8ccb71f554d94d95b87c48c22730116/scfeaturegraphics.png)" width="200" />
</p>

---
*Developed for those who want to join the 1%.*
