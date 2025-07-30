# 🐠 Feeding Frenzy – JavaFX Arcade Game

A 2D underwater arcade game built with JavaFX, inspired by the classic Feeding Frenzy.  
🎮 Final project for the *Comprehensive Java Practice* course at Zhejiang Normal University.

![Gameplay Screenshot](assets/screenshots/ffg_main_screenshot.jpg)

---

## 🎮 Features

- ✅ Size-based predation mechanics
- ✅ Real-time AI behaviors: basic, intermediate, flocking
- ✅ Dynamic fish spawning and coin collection
- ✅ Multilingual UI (English 🇺🇸, Arabic 🇸🇦, Chinese 🇨🇳)
- ✅ Save system for high scores and profiles
- ✅ 60 FPS smooth performance

---

## 🎥 Gameplay Demo (MP4)

📽️ [Click here to download and watch the demo](assets/demo/FeedingFrenzyGameplay.mp4)

> This is a local `.mp4` video file hosted in the repository. Download it to view the game in action.

---

## 🧠 Architecture

---

## 🛠️ Tech Stack

| Component       | Description                    |
|----------------|--------------------------------|
| JavaFX 17+      | UI toolkit and game loop       |
| AnimationTimer  | Main game loop                 |
| MediaPlayer     | Background music & SFX         |
| JSON / I/O      | Save player profiles           |
| MVC Architecture| Clean separation of concerns   |

---

## ▶️ Run Instructions

### 🧪 Compile & Run (Command Line)

```bash
javac -cp "lib/*" src/**/*.java
java -cp "lib/*:src" main.WelcomePage

