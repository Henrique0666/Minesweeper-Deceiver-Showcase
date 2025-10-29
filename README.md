# Minesweeper-Deceiver
Play the classic. Master the deception.

![Minesweeper Deceiver Demo](https://github.com/user-attachments/assets/0ccd543e-aeef-4685-b24b-bd1aacdc8ddb)

# 🧨 Minesweeper Deceiver — Android App

A modern twist on the classic **Minesweeper**, rebuilt for mobile devices using **C++ and SDL2**.  
This version features a clean design, touchscreen support, and a unique challenge mode: **Deceiver**, where some clues are false.

> 🎯 Goal: Build a fast, minimal, and intuitive game that appeals to both classic fans and new players.

---

## 📱 Features

- ✅ Modern UI with **light** and **dark** modes
- ✅ Exclusive **Deceiver Mode**: some hints can lie
- ✅ Two visual styles: **Classic pixel art** and **Rounded modern UI**
- ✅ Fully touch-friendly interface
- ✅ Built-in timer
- ✅ Optional sound and subtle animations (planned)
- ✅ Lightweight and responsive across screen sizes

---

## 🧰 Tech Stack

- **Language:** C++
- **Graphics/Input:** SDL2
- **Build System:** CMake + Android NDK
- **Editor:** VSCode (development) + Android Studio (build/deploy)
- **Optional:** SDL_image, SDL_ttf, SDL_mixer

---

## 🚀 Getting Started

### 📦 Requirements

- **Ubuntu** (Linux)
- **Android Studio** with:
  - Android SDK
  - Android NDK
  - CMake
  - SDK Build Tools
- **VSCode** (recommended)
- **SDL2 and extensions**

Install SDL2 libraries on Ubuntu:

```bash
sudo apt install libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev
```

## 🛠️ Build Instructions (Native C++ Android)

  - Create a Native C++ project in Android Studio.
  - Copy your C++ source files and CMakeLists.txt into the project.
  - Ensure SDL is linked correctly in your CMakeLists.txt.
  - Build the project (Build > Make Project) and run on a virtual or physical Android device.

---

## 🎮 Game Modes

  - Classic: Traditional Minesweeper
  - Deceiver: Hints can be wrong (+1 or -1 variation)

---

## ✨ Planned Features

  - 🌍 Online leaderboards
  - 🤖 Optional hint/AI system
  - 📲 Google Play release with ads & in-app purchase to remove them

---

## 🤔 Why SDL2?

SDL2 gives full control over graphics, input, sound, and timing in C++.
Perfect for:

  - Custom rendering
  - Efficient animations
  - Cross-platform performance
  - No need for heavy Java/Kotlin logic
  - Game can be done in C/C++


## 👨‍💻 About the Developer

  This game began as a Minix C project and evolved into a mobile app, blending classic logic with a modern user experience.
  The Deceiver mode adds a new twist for players seeking more strategy and challenge.
