# 🃏 Card Match Game

A simple **single-player card matching game** built with **Unity Engine (2021.3.8f1)**.  
The game is designed to be played in **portrait mode** and includes builds for both **Android** and **Windows** (available inside the `BUILDS` folder).

---

## 📱 Gameplay

1. Launch the game and choose a difficulty:
   - **Easy** – Small grid size  
   - **Medium** – Moderate grid size  
   - **Hard** – Large grid size  

2. Flip cards to find matching pairs.  
3. Your **score** is determined by the number of turns you take to complete the level.  
   - **Best Score** = Lowest number of turns recorded for that difficulty.  
4. Scores are saved using **PlayerPrefs** and automatically loaded when you replay.

---

## 🗂 Project Structure

- `Assets/` → Unity project files  
- `BUILDS/` → Playable builds  
  - `Android/` → APK build (portrait mode)  
  - `Windows/` → EXE build (portrait resolution)

---

## ▶️ How to Play Builds

- **Windows**:  
  Run the `.exe` file in **portrait resolution** for the best experience.  

- **Android**:  
  Install the `.apk` and play directly on your phone (portrait mode only).  

---

## 💾 Save System

- **PlayerPrefs** is used to **save and load best scores** per difficulty level.  
- Best scores persist between game sessions.  

---

## ⚙️ Requirements

- Unity **2021.3.8f1** (LTS) for development  
- Android 7.0+ (if playing the APK)  
- Windows 8+ (if playing the EXE build)

---

## 📌 Notes

- The game is locked to **portrait mode** on all platforms.  
- If playing on Windows, adjust the game window to **portrait resolution** (e.g., 720x1280).

---

## 🛠️ Development

- Engine: **Unity 2021.3.8f1**  
- Language: **C#**  

---

## 📄 License

This project is released under the **MIT License**.  
You’re free to use, modify, and distribute it with proper attribution.

---
