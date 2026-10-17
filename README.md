# Fortune Teller - Mobile Application Lab 02 🔮

This project is a React Native mobile application built as part of the Mobile Application Development course (Academic Year 2024/2025, Semester 2) at the University of Kelaniya[cite: 1]. The application serves as an interactive "Fortune Teller" using Expo Router for navigation[cite: 13, 14, 16].

---

## 🚀 What We Built During This Lab Session

* **Android Emulator Setup:** Configured and launched a virtual Android device (Pixel 4 / API 37.2) via Android Studio and the command line[cite: 5, 7].
* **Expo React Native Project:** Initialized a clean React Native application using Expo Router and organized the source folder structure (`src/app/`)[cite: 8, 9].
* **Stack Navigation (`_layout.tsx`):** Implemented file-based stack navigation to manage screen transitions and header titles seamlessly[cite: 13].
* **Home Screen (`index.tsx`):** Built a welcome interface featuring custom styling, a profile image, an informative description box, and a routing button to trigger the fortune reveal[cite: 14, 15].
* **Reveal Screen (`reveal.tsx`):** Created a dynamic second screen displaying a randomized programming fortune with a custom-styled card view and a "Go Back" navigation button[cite: 16].

---

## 🛠️ Tech Stack & Tools

* **Framework:** React Native (Expo)[cite: 1]
* **Routing:** Expo Router (File-based navigation)[cite: 9, 13]
* **Language:** TypeScript / JavaScript[cite: 12, 14]
* **Environment:** Android Studio Emulator & Expo Go[cite: 1, 10]

---

## 📦 Project Structure

```text
FortuneTeller/
├── src/
│   └── app/
│       ├── _layout.tsx    # Stack navigation layout & header titles[cite: 13]
│       ├── index.tsx      # Welcome & home screen[cite: 14]
│       └── reveal.tsx     # Fortune display screen[cite: 16]
├── assets/                # App images and icons
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation