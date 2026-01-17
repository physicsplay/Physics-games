# 🎮 Physics Games Lab

**Interactive physics games for high school students (mobile-friendly, no dependencies).**

Play games that promote understanding of physics through **calculation + experimentation** — not trial-and-error.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-E34F26.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![GDPR Compliant](https://img.shields.io/badge/GDPR-Compliant-green.svg)](#-privacy--gdpr)

---

## 🌐 Play Now

**👉 https://physicsplay.github.io/Physics-games/**

No registration. No download. Just click and play!

> Tip: The launcher passes `?lang=...` to each game, but players can still change language from the game’s intro screen.

---

## 🎯 Available Games

| Game | Topic | What you do | Core Physics |
|------|------|-------------|--------------|
| 💉 **Send Insulin to Grandma** (GR: **Στείλε την ινσουλίνη στη γιαγιά**) | **Projectile motion (horizontal launch)** | Compute the needed **initial horizontal speed** to deliver insulin across a flooded area. | `t = √(2h/g)` and `v₀ = d/t` |
| 🌊 **Save the Child** (GR: **Σώσε το παιδί**) | **Pendulum + projectile** | Choose an initial angle, swing like a pendulum and **release at the right moment** to reach the child through a window before the water rises. | `v = √(2ηgL(1−cosθ₀))` + projectile motion |
| ⚖️ **Bridge Equilibrium** (GR: **Ισορροπία γέφυρας**) | **Statics & torques** | Balance loads to keep the bridge stable by placing forces correctly. | `ΣF = 0` and `Στ = 0` |

---

## 🖼️ Screenshots

### 💉 Send Insulin to Grandma
<img src="screenshots/01_send_insulin.png" alt="Send Insulin to Grandma screenshot" width="900">

### 🌊 Save the Child
<img src="screenshots/02_save_the_child.png" alt="Save the Child screenshot" width="900">

### ⚖️ Bridge Equilibrium
<img src="screenshots/03_bridge_equilibrium.png" alt="Bridge Equilibrium screenshot" width="900">

---

## ✨ Features

### 🎓 Educational
- Scientifically accurate physics (SI units, correct formulas)
- Formulas always visible
- Pause to calculate (paper-friendly)
- Hints available (with score penalty)
- Post-game summary: theoretical vs “experimental” results

### 🏆 Gamification
- Medals: 🥇 Gold (<5% error) | 🥈 Silver (<10%) | 🥉 Bronze (<20%)
- Scoring rewards **calculation**, discourages random tries
- Physics jokes + easter eggs

### 🌍 Accessibility
- **5 Languages**: 🇬🇷 Greek | 🇬🇧 English | 🇮🇹 Italian | 🇪🇸 Spanish | 🇧🇬 Bulgarian
- Desktop / tablet / mobile
- Touch + keyboard controls
- No external libraries (pure HTML/CSS/JS)

---

## 👩‍🏫 For Teachers

### Quick classroom setup
1. Share the link with students
2. Use `qr_generator.html` to generate printable QR codes
3. Print and distribute or display in class

### Pedagogical notes
- Designed to **require calculation** for best scores
- Trial-and-error is penalized
- End screen supports discussion

---

## 📁 Project Structure

```
Physics-games/
├── index.html                      # Main launcher (passes ?lang=.. to games)
├── qr_generator.html               # QR generator for teachers
├── 01_send_insulin_to_grandma.html # Game 1: horizontal projectile
├── 02_save_the_child.html          # Game 2: pendulum + projectile
├── 03_bridge_equilibrium.html      # Game 3: statics & torques
├── screenshots/                    # README images
│   ├── 01_send_insulin.png
│   ├── 02_save_the_child.png
│   └── 03_bridge_equilibrium.png
└── README.md
```

---

## 🛡️ Privacy & GDPR

- ✅ No cookies
- ✅ No analytics
- ✅ No tracking
- ✅ No data collection
- ✅ No external requests
- ✅ Works offline if downloaded locally

---

## 📜 License

MIT License — free for educational use.

---

## 🙏 Acknowledgments

- Created for physics education at **2nd Lyceum of Moschato (Greece)** and **L.S. R. Caccioppoli (Napoli, Italy)**
- Developed in the context of **Erasmus+ KA122** educational innovation project

---
_Updated: 2026-01-17_
