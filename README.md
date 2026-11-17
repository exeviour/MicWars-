# MicWars-
​MicWars — Ultimate speech, debate, poetry, and storytelling 1v1 battle arena featuring a cyber-themed authentication portal, live lobby, and persistent session routing.
# ⚡ MicWars — Battle Your Bars. Win The Mic.

![MicWars Banner](https://img.shields.io/badge/Season-4%20Live-purple?style=for-the-badge&logo=microphone)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**MicWars** is a next-generation battle arena web application built for public speakers, debaters, poets, and storytellers. Compete 1v1 live or via recorded pitch, get judged by certified experts and the live audience, and cash out your winnings instantly.

---

## 📂 Project Architecture

This project is structured into modular authentication and platform directories to handle secure user onboarding and live stage management:

```text
micwars_03/
├── Log in/
│   ├── index.html        # Secure authentication portal (Login & Sign Up)
│   └── js/
│       └── script.js     # Auth logic, validation, state management & session bridging
└── Platfom/
    └── index.html        # Main battle arena, lobby, leaderboards, and dashboard
