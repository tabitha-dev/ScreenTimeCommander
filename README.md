

<h1 align="center">🛡️ Screen Time Commander</h1>
<p align="center">
  <i>Mission-Based Screen Time Tracker for Kids and Families</i><br>
  Gamified productivity meets digital wellness — complete missions, earn screen time, unlock badges, and stay balanced.
</p>

<p align="center">
  <a href="https://tabitha-dev.github.io/ScreenTimeCommander/">Live Demo</a> •
  <a href="#installation--setup">Install</a> •
  <a href="#features">Features</a> •
  <a href="#roadmap">Roadmap</a> •
  <a href="#contributing">Contribute</a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/github/stars/tabitha-dev/ScreenTimeCommander?style=for-the-badge&color=yellow" alt="GitHub stars">
  <img src="https://img.shields.io/github/last-commit/tabitha-dev/ScreenTimeCommander?style=for-the-badge&color=blue" alt="Last Commit">
  <img src="https://img.shields.io/github/license/tabitha-dev/ScreenTimeCommander?style=for-the-badge&color=green" alt="License">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="PWA">
</p>

---

## ⚡ Quick Start

```bash
git clone https://github.com/tabitha-dev/ScreenTimeCommander.git
cd ScreenTimeCommander
```

Then open `index.html` in your browser (or use **VS Code Live Server**).

No dependencies. 100% client-side.

---

## 💡 About

**Screen Time Commander** transforms everyday routines into fun, goal-driven missions. Each completed mission adds earned minutes that can be redeemed for approved screen time like games or shows.

No login, no tracking, no server — everything runs locally with offline persistence.

---

## ✨ Features

| Feature | Description |
|----------|--------------|
| 🎯 **Mission Control** | Daily missions with category toggles |
| ⏱️ **Earn & Redeem** | Track earned and redeemed time easily |
| 🔁 **Daily Reset** | Auto reset system with streak tracking |
| 🏅 **Badges & Achievements** | Collect milestone rewards like “Kindness Hero” |
| 🌗 **Dark / Light Mode** | Theme switcher with memory persistence |
| 💾 **Offline Ready (PWA)** | Works offline on mobile or desktop |
| ♿ **Accessibility** | ARIA, keyboard navigation, reduced motion |

---

## 🛠 Tech Stack

- **HTML5** — semantic, accessible structure
- **Tailwind CSS** — responsive design via CDN
- **JavaScript (ES6)** — game logic and rendering
- **PWA** — offline caching and app installability
- **LocalStorage** — saves progress between sessions

---

## 🧩 App Structure

| File | Purpose |
|------|----------|
| `index.html` | UI + core script |
| `manifest.json` | App manifest for PWA |
| `sw.js` | Service Worker for offline cache |
| `assets/` | Icons, badges, and theme images |

<details>
<summary><b>📦 Local Storage Schema</b></summary>

```json
{
  "tasks": [{ "id": "ready", "completed": false }],
  "earnedTime": 0,
  "spentTime": 0,
  "streak": 0,
  "badges": [],
  "lifetimeMinsEarned": 0,
  "lifetimeTasksCompleted": 0,
  "kindnessMissionsCompleted": 0,
  "readingDaysCompleted": 0,
  "accordionState": {},
  "lastResetDate": "YYYY-MM-DD",
  "schemaVersion": 3
}
```
</details>

---

## 🖼 UI Showcase

<p align="center">


  <<img width="1225" height="544" alt="image" src="https://github.com/user-attachments/assets/feb89ca6-54f6-4e17-989f-5888f2231d0e" />

</p>

---

## ♿ Accessibility Highlights

- Keyboard and touch friendly
- ARIA labels and live regions
- Focus management within dialogs
- Honors reduced motion preferences
- Optimized contrast for both themes

---

## 🔮 Roadmap

- [ ] Multi-user profiles
- [ ] Parent PIN-protected settings
- [ ] Weekly progress analytics
- [ ] Cloud sync (Firebase / Supabase)
- [ ] Advanced badge tiers
- [ ] Family leaderboard view

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`feature/your-idea`)
3. Commit and push your changes
4. Submit a Pull Request

For ideas or bugs, open an issue. Guidelines coming soon in `CONTRIBUTING.md`.

---

## 🧭 Motivation

Balancing screen time shouldn’t be a battle. This app helps parents and children collaborate by rewarding healthy routines with meaningful, earned entertainment time.

---

## 🪪 License

Licensed under the **MIT License** — free for personal and educational use.

---

## ❤️ Built With

- [Tailwind CSS](https://tailwindcss.com)
- [Inter Font](https://fonts.google.com/specimen/Inter)
- Native emoji + open-source icons

---

<p align="center">
Built with ❤️ for families who want to balance fun and responsibility.<br>
<a href="https://tabitha-dev.github.io/ScreenTimeCommander/">→ Try Screen Time Commander</a>
</p>
