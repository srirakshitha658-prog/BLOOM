<div align="center">

# BLOOM

<br/>

![Version](https://img.shields.io/badge/version-1.0.0-C87D7D?style=for-the-badge&labelColor=FDE8E8)
![HTML](https://img.shields.io/badge/HTML5-Single_File-8FAF85?style=for-the-badge&logo=html5&logoColor=white&labelColor=C8D8C0)
![CSS](https://img.shields.io/badge/CSS3-Vanilla-DDD5F0?style=for-the-badge&logo=css3&logoColor=white&labelColor=9B8FCC)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla_ES6-FAF0C8?style=for-the-badge&logo=javascript&logoColor=black&labelColor=d4af37)
![License](https://img.shields.io/badge/License-MIT-F9D0D0?style=for-the-badge&labelColor=E8B4B4)
![PWA](https://img.shields.io/badge/PWA-Offline_Ready-C8D8C0?style=for-the-badge&logo=pwa&logoColor=white&labelColor=8FAF85)

<br/>

> **A full-featured, Pinterest-aesthetic daily planner for students — built as a single HTML file.**
> Cottagecore × Studygram vibes with soft pastels, hand-drawn SVG animals, botanical accents, and everything a student startup needs.

<br/>

[✦ Live Demo](#-live-demo) · [✦ Features](#-features) · [✦ Getting Started](#-getting-started) · [✦ Roadmap](#-roadmap) · [✦ Contributing](#-contributing)

<br/>

---

</div>

<br/>

## 🌿 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
  - [Core Planner](#-core-planner)
  - [Academic Tools](#-academic-tools)
  - [Wellness & Wellbeing](#-wellness--wellbeing)
  - [Gamification & Motivation](#-gamification--motivation)
  - [Design & Aesthetic](#-design--aesthetic)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Option 1 — Instant (No Setup)](#option-1--instant-no-setup)
  - [Option 2 — GitHub Pages](#option-2--github-pages)
  - [Option 3 — Local Development](#option-3--local-development)
- [File Structure](#-file-structure)
- [Data & Storage](#-data--storage)
- [Security](#-security)
- [Spotify Integration](#-spotify-integration)
- [PWA & Offline Mode](#-pwa--offline-mode)
- [Customization Guide](#-customization-guide)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

<br/>

---

## 🌸 Overview

**Bloom Planner** is a beautifully designed, student-oriented productivity web app that runs entirely from a **single HTML file** — no build tools, no dependencies, no backend required.

It was built with a startup-ready architecture: all logic is modular, data is persisted per user via `localStorage`, and the app is PWA-capable for offline use. The aesthetic is intentionally distinctive — **soft pinks, sage greens, warm creams, and lavender** — with hand-crafted SVG illustrations of rabbits, pandas, bears, cats, owls, and elephants throughout. Zero emoji used as decorative elements.

```
One file. Zero dependencies. Infinite charm.
```

<br/>

---

## 🔗 Live Demo

> **Deploy in 60 seconds — see [Getting Started](#-getting-started) below.**

To run locally right now:

```bash
# Just open the file in any browser
open bloompln.html
```

Or deploy free on GitHub Pages, Netlify, or Vercel — all work instantly with a single HTML file.

<br/>


<br/>

---

## ✨ Features

### 🗓 Core Planner

| Feature | Description |
|---------|-------------|
| **Email Login Screen** | Beautiful botanical wreath SVG login card. Data is stored per email — each user gets their own workspace. |
| **Dashboard** | Live date & greeting, daily inspirational quotes, mood picker, Spotify widget, anti-procrastination mode toggle, and deadline risk alerts. |
| **Time Blocking** | Visual hourly schedule grid (6am–10pm). Add color-coded blocks with custom duration. Drag-and-drop ready. |
| **Quick Add Bar** | Floating bottom bar for instant task capture without leaving any page. Press `Enter` or click to save. |
| **To-Do List** | Full-featured with priority levels (Urgent / Normal / Chill), due dates, subtask nesting, filter by priority/status, brain dump area, and delete. |
| **Recurring Tasks** | Task structure supports recurring flags — wire up cron-style reset logic in the roadmap backend. |
| **Deadline Risk Alerts** | Auto-generated alert banners on the dashboard for any exam or course deadline within 3 days. |

### 📚 Academic Tools

| Feature | Description |
|---------|-------------|
| **Courses Tracker** | Course cards with SVG circular progress arcs (not plain bars), professor field, color themes, and deadline countdown with urgency color coding (red / amber / green). |
| **Exam Countdowns** | Add named exams with dates. Displays days remaining, auto-sorted by proximity, with color-coded urgency. |
| **Study Techniques Library** | 6 illustrated flip cards — Pomodoro, Feynman Method, Spaced Repetition, Active Recall, Mind Mapping, Cornell Notes. Each card has a unique SVG animal; hover to flip for technique details. |
| **Pomodoro Timer** | Animated SVG rabbit face timer with circular progress ring. Supports 25-min focus, 5-min break, and 15-min long break. Earns XP on completion. |
| **Smart Task Priority** | Todos are color-ribbon-coded and filterable. High-priority task count surfaces in dashboard alerts. |

### 🌷 Wellness & Wellbeing

| Feature | Description |
|---------|-------------|
| **Period Tracker** | Monthly calendar with period days (pink), fertile window (green), today highlight, and next-period prediction. Configurable cycle length and duration. |
| **Mood Journal** | SVG mood faces (not emoji) for 5 moods: Joyful, Calm, Tired, Anxious, Sad. Daily selection with personalized response text. |
| **Study Journal** | Notebook-paper-styled textarea with ruled-line CSS background. Entries saved by date and browsable in a history list with mood tags. |
| **Daily Habits** | 7-day habit tracking grid with circular dot indicators per day. Add custom habits. Each check-in earns XP. |

### 🏆 Gamification & Motivation

| Feature | Description |
|---------|-------------|
| **XP System** | Earn XP for completing todos (+10), habits (+5), journaling (+15), mood check-in (+5), finishing a Pomodoro (+25). |
| **9 Levels** | Sprout → Seedling → Bloom → Blossom → Flourish → Garden Keeper → Scholar → Sage → Master |
| **Streak Counter** | Logs daily login streaks. Consecutive days increment the streak. Missing a day resets it. |
| **Growing Plant** | SVG plant illustration on the dashboard gains leaves based on current streak length (up to 10 leaves). |
| **Daily Quotes** | Rotating motivational quotes from curated authors, with a "New Quote" button. |
| **Anti-Procrastination Mode** | Toggleable banner with a cute bear SVG and an encouraging message. State persists across sessions. |

### 🎨 Design & Aesthetic

| Feature | Description |
|---------|-------------|
| **Cottagecore × Studygram palette** | `#FDE8E8` blush · `#FDF6EC` cream · `#C8D8C0` sage · `#DDD5F0` lavender · `#FAF0C8` butter yellow |
| **Typography** | Playfair Display (headings) + Lora (body) + Caveat (handwritten accents) — Google Fonts |
| **SVG Animal Illustrations** | Rabbit, Panda, Bear, Cat, Owl, Elephant — all hand-crafted inline SVG, no emoji, no external images |
| **Botanical Backgrounds** | Animated floating leaf SVGs. Radial gradient mesh background. Subtle dot-grid/linen feel. |
| **Smooth Animations** | Page transitions, card hover lifts, login card spring entrance, quick-add bar slide-up, streak plant growth, XP bar fill |
| **Custom Scrollbar** | Soft rose-tinted scrollbar matching the theme |
| **Responsive Layout** | Sidebar collapses to icon-only on mobile. Grid layouts adapt to single column. |

<br/>

---

## 🛠 Tech Stack

```
Frontend    →  Vanilla HTML5, CSS3, JavaScript (ES6+)
Fonts       →  Google Fonts (Playfair Display, Lora, Caveat)
Storage     →  localStorage (per-email namespacing)
Graphics    →  Inline SVG (100% hand-coded, no external assets)
PWA         →  Service Worker (offline caching)
Build       →  None — single file, zero dependencies
```

**Why no framework?**

Bloom Planner is intentionally dependency-free. This means:
- ⚡ Instant load, no npm, no bundler
- 🌐 Deployable anywhere — GitHub Pages, Netlify, a USB drive
- 🔒 No supply-chain risk
- 📦 The entire app is one file you can email to yourself

<br/>

---

## 🚀 Getting Started

### Option 1 — Instant (No Setup)

```bash
# Download the file and open it
curl -O https://raw.githubusercontent.com/srirakshitha658-prog/bloom-planner/main/bloompln.html
open bloompln.html     # macOS
start bloompln.html    # Windows
xdg-open bloompln.html # Linux
```

That's it. No install. No terminal. Works offline.

---

### Option 2 — GitHub Pages

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app is live at `https://srirakshitha658-prog.github.io/bloom-planner/bloompln.html`

---

### Option 3 — Local Development

```bash
# Clone the repo
git clone https://github.com/srirakshitha658-prog/bloom-planner.git
cd bloom-planner

# Serve locally (Python — comes pre-installed on most systems)
python3 -m http.server 8080

# Or with Node.js
npx serve .

# Open in browser
open http://localhost:8080/bloompln.html
```

> **Note:** Opening the file directly via `file://` works for all features. A local server is only needed if you plan to add a Service Worker for full PWA support.

<br/>

---

## 📁 File Structure

```
bloom-planner/
│
├── bloompln.html          # 🌸 The entire app — HTML + CSS + JS in one file
├── README.md              # This file
├── LICENSE                # MIT License
│
└── (future structure)
    ├── src/
    │   ├── index.html     # Entry point (when split into modules)
    │   ├── styles/
    │   │   └── bloom.css
    │   ├── scripts/
    │   │   ├── app.js
    │   │   ├── planner.js
    │   │   ├── gamification.js
    │   │   └── storage.js
    │   └── assets/
    │       └── svgs/
    └── docs/
        └── screenshots/
```

<br/>

---

## 💾 Data & Storage

All data is stored in the browser's `localStorage` under a namespaced key:

```javascript
localStorage.setItem('bloom_' + userEmail, JSON.stringify(state));
```

### Data Schema

```javascript
{
  todos:          [ { text, priority, due, done, subtasks, created } ],
  courses:        [ { name, deadline, prof, progress, color } ],
  exams:          [ { name, date } ],
  habits:         [ { name, done: [bool × 7] } ],
  journal:        { "YYYY-MM-DD": { text, mood } },
  mood:           { "YYYY-MM-DD": moodIndex },
  timeBlocks:     [ { task, start, duration, color } ],
  period:         { start, cycle, duration },
  streak:         Number,
  lastLogin:      "YYYY-MM-DD",
  xp:             Number,
  pomodorosDone:  Number,
  tasksDone:      Number,
  weeklyActivity: [ Number × 7 ],
  antiProc:       Boolean
}
```

### Exporting Your Data

Open the browser console and run:

```javascript
const email = 'your@email.com';
const data = localStorage.getItem('bloom_' + email);
const blob = new Blob([data], { type: 'application/json' });
const a = document.createElement('a');
a.href = URL.createObjectURL(blob);
a.download = 'bloom-backup.json';
a.click();
```

<br/>

---

## 🔐 Security

| Layer | Implementation |
|-------|---------------|
| **Data isolation** | Each user's data is stored under a unique `bloom_<email>` key. No cross-user access. |
| **Client-side only** | No data is ever transmitted to a server. Everything stays in your browser. |
| **Password note** | The current login is a UX gate only (no server-side auth). For production, integrate with a backend (Supabase, Firebase, etc.) — see [Roadmap](#-roadmap). |
| **XSS prevention** | User input is stored as plain strings and rendered via `textContent` / template literals without `innerHTML` injection of raw user data. |
| **No third-party scripts** | Zero external JavaScript. Only Google Fonts (CSS) is loaded externally. |

> **For production deployment**, replace `localStorage` auth with a proper backend (see roadmap). The data schema is designed to be drop-in compatible with Supabase or Firebase Firestore.

<br/>

---

## 🎵 Spotify Integration

The app ships with a **demo Spotify widget** that simulates playback UI. To connect real Spotify:

### Step 1 — Register your app

1. Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
2. Create a new app
3. Add your domain to **Redirect URIs**
4. Copy your **Client ID**

### Step 2 — Add OAuth flow

Replace the `connectSpotify()` function in `bloompln.html`:

```javascript
const CLIENT_ID = 'YOUR_SPOTIFY_CLIENT_ID';
const REDIRECT_URI = 'https://your-domain.com/bloompln.html';
const SCOPES = 'user-read-playback-state user-modify-playback-state user-read-currently-playing';

function connectSpotify() {
  const authUrl = `https://accounts.spotify.com/authorize?client_id=${CLIENT_ID}&response_type=token&redirect_uri=${encodeURIComponent(REDIRECT_URI)}&scope=${encodeURIComponent(SCOPES)}`;
  window.location.href = authUrl;
}
```

### Step 3 — Handle the token on return

```javascript
const hash = window.location.hash.substring(1);
const params = new URLSearchParams(hash);
const token = params.get('access_token');
if (token) {
  localStorage.setItem('spotify_token', token);
  fetchNowPlaying(token);
}
```

<br/>

---

## 📶 PWA & Offline Mode

Bloom Planner is **offline-ready by design** — all data lives in `localStorage`, all assets are inline.

### Making it a full installable PWA

**1. Add a Web App Manifest** — create `manifest.json`:

```json
{
  "name": "Bloom Planner",
  "short_name": "Bloom",
  "start_url": "/bloompln.html",
  "display": "standalone",
  "background_color": "#FDF6EC",
  "theme_color": "#C87D7D",
  "icons": [
    { "src": "icon-192.png", "sizes": "192x192", "type": "image/png" },
    { "src": "icon-512.png", "sizes": "512x512", "type": "image/png" }
  ]
}
```

**2. Register a Service Worker** — add to `bloompln.html` before `</body>`:

```html
<script>
  if ('serviceWorker' in navigator) {
    navigator.serviceWorker.register('/sw.js');
  }
</script>
```

**3. Create `sw.js`**:

```javascript
const CACHE = 'bloom-v1';
const ASSETS = ['/bloompln.html'];

self.addEventListener('install', e =>
  e.waitUntil(caches.open(CACHE).then(c => c.addAll(ASSETS)))
);

self.addEventListener('fetch', e =>
  e.respondWith(
    caches.match(e.request).then(r => r || fetch(e.request))
  )
);
```

After this, users can **install Bloom Planner to their home screen** on iOS and Android.

<br/>

---

## 🎨 Customization Guide

### Changing the Color Palette

All colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --blush:      #FDE8E8;   /* Main background tint */
  --cream:      #FDF6EC;   /* Page background */
  --sage:       #C8D8C0;   /* Accent green */
  --sage-deep:  #8FAF85;   /* Buttons, active states */
  --rose:       #E8B4B4;   /* Borders, soft accents */
  --rose-deep:  #C87D7D;   /* Primary action color */
  --petal:      #F9D0D0;   /* Card highlights */
  --lavender:   #DDD5F0;   /* Secondary accent */
  --butter:     #FAF0C8;   /* Warm accent */
  --mauve:      #7D5C5C;   /* Primary text / headings */
  --forest:     #5C7D60;   /* Success / positive states */
}
```

### Adding a New Study Technique

In the `STUDY_TECHNIQUES` array:

```javascript
{
  title: "Your Technique Name",
  front_color: "#C8D8C0",       // card background color
  desc: "How this technique works and why it's effective.",
  animal: "rabbit"              // rabbit | owl | elephant | bear | cat | panda
}
```

### Adding New Levels

Extend the `LEVELS` array and adjust XP per level in the `renderXP()` function:

```javascript
const LEVELS = ['Sprout','Seedling','Bloom','Blossom','Flourish',
                'Garden Keeper','Scholar','Sage','Master', 'Luminary'];
```

### Changing XP Rewards

Search for `addXP(` in the JS and adjust the values:

```javascript
// Current defaults
addXP(5)   // habit check-in
addXP(10)  // todo completed
addXP(15)  // journal entry
addXP(25)  // pomodoro finished
```

<br/>

---

## 🗺 Roadmap

### v1.1 — Auth & Sync
- [ ] Supabase backend integration (real auth + cloud storage)
- [ ] Google OAuth login
- [ ] Cross-device data sync
- [ ] Data export to JSON / CSV

### v1.2 — Advanced Planning
- [ ] Recurring tasks (daily / weekly / monthly)
- [ ] Task dependencies (Task B unlocks after Task A)
- [ ] Drag-and-drop time block reordering
- [ ] Calendar view (month / week)
- [ ] Google Calendar import/export

### v1.3 — Social & Sharing
- [ ] Study accountability buddy feature
- [ ] Share stats as a beautiful image card
- [ ] Public "study room" (Pomodoro sync with friends)

### v1.4 — Intelligence
- [ ] Smart task priority suggestions based on deadlines
- [ ] Study session recommendations based on past patterns
- [ ] AI-powered journaling prompts
- [ ] Deadline risk score algorithm

### v2.0 — Native App
- [ ] React Native mobile app (iOS + Android)
- [ ] Push notifications for deadlines & streak reminders
- [ ] Apple Health / Google Fit integration for wellness data
- [ ] Spotify SDK full integration

<br/>

---

## 🤝 Contributing

Contributions are warmly welcomed! Whether it's a bug fix, a new feature, or just improving the README — every bit helps bloom this garden. 🌱

### How to Contribute

```bash
# 1. Fork the repository
# 2. Clone your fork
git clone https://github.com/srirakshitha658-prog/bloom-planner.git

# 3. Create a feature branch
git checkout -b feature/your-amazing-feature

# 4. Make your changes
# (All code is in bloompln.html — easy to navigate!)

# 5. Commit with a descriptive message
git commit -m "✿ Add [feature]: brief description"

# 6. Push and open a Pull Request
git push origin feature/your-amazing-feature
```

### Commit Convention

| Prefix | Use for |
|--------|---------|
| `✿ Add` | New features |
| `🌱 Fix` | Bug fixes |
| `🎨 Style` | CSS / visual changes |
| `📚 Docs` | README / documentation |
| `♻️ Refactor` | Code restructuring |

### Good First Issues

- Add more study technique cards
- Add more inspirational quotes to the `QUOTES` array
- Create additional SVG animal illustrations
- Improve mobile responsiveness
- Write unit tests for the storage layer

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

<br/>

---

## 📄 License

```
MIT License

Copyright (c) 2025 Bloom Planner

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

Full license text in [LICENSE](LICENSE).

<br/>

---

## 💐 Acknowledgements

- **Google Fonts** — Playfair Display, Lora, Caveat
- **Shields.io** — badge generation
- **readme-typing-svg** — animated header by [DenverCoder1](https://github.com/DenverCoder1)
- Every student who deserved a prettier planner ✿

<br/>

---

<div align="center">

**Made with 🌸 and a lot of cozy study sessions**

If Bloom Planner helped your studies, please give it a ⭐ — it means the world!

<br/>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer)

</div>
