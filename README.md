CampusPulse ⚡ — Live Activity Map of VIT-AP University

**See what's happening on campus right now — on a real-time 3D map of VIT-AP

🔗 **Live demo:** https://anav-awasthi.github.io/campuspulse/
(works on desktop and mobile — no install, no login)

<!-- Upload your screenshot to a folder named 'screenshots' as realistic.png, or delete this line -->
![CampusPulse — Realistic view](screenshots/realistic.png)

---

## 💡 The Problem

Campus life is invisible. A jam session at Rock Plaza, a cricket match at the courts, a study group in the CB library — by the time word spreads through group chats, it's already over. Students constantly miss things happening **200 metres away from them**.

## ✅ The Solution

CampusPulse is a live, location-anchored activity map built on a 3D model of the actual VIT-AP campus (Inavolu, Amaravati). Anyone can:

- **Drop a live activity** anywhere on the map — cricket, study group, food run, jam session, club meet, gaming, chill, or SOS
- **Schedule it up to 5 days ahead** — it appears as an *Upcoming* event with a ⏰ badge and automatically goes 🔴 LIVE when the clock hits zero
- **Discover & join instantly** — tap a pulsing marker, see who's in, RSVP, and chat with the group
- **Watch it expire** — activities are ephemeral; markers fade as time runs out. This is about *now*, not next week.

## ✨ Features

| | |
|---|---|
| 🗺️ **Accurate 3D campus** | The real layout, modelled from aerial photography: the ring-shaped **Central Block (CB)**, Flag Plaza, **AB-1 (Radhakrishnan)** & **AB-2 (Kalam)** with solar roofs, **SAC**, Rock Plaza, MH/LH hostel towers, covered walkways, gate complex, VITRINA guest house, and the hill on the horizon |
| ◉ **Hologram mode** | One tap dissolves the campus into a Tron-style hologram — wireframe buildings with **X-ray interiors**: hostel floors with cots, study tables & cupboards, the CB library level, 70-seat AB classrooms, and the SAC indoor court |
| 🌦️ **Live weather** | Pulls real conditions for the campus coordinates from the free [Open-Meteo](https://open-meteo.com/) API — rain actually falls, storms flash lightning, fog rolls in, clouds thicken, and the scene auto-switches to night when it's night in Amaravati |
| 🕹️ **Fully interactive** | Orbit / zoom / pan camera, cinematic fly-to on any building or event, intro flythrough, Map / Explore / Street view presets, search that flies you to results |
| 📅 **Schedule ahead** | Now / +1 hr / Tomorrow / custom date-picker (up to 5 days), with a dedicated Upcoming feed and go-live notifications |
| 🗑️ **Host controls** | Only the creator of an event can remove it (tap-to-confirm) |
| ✨ **Gamification** | Hosting and joining earn Aura points with ranks from *Freshman Explorer* to *Campus Legend* |
| 📱 **Mobile-first** | Bottom-sheet UI, touch camera controls, safe-area support, reduced GPU load on phones |
| 🌙 **Day / night cycle** | Warm window glow, lamp-post light cones, stars and moon |

<!-- Upload your screenshot to a folder named 'screenshots' as hologram.png, or delete this line -->
![CampusPulse — Hologram mode](screenshots/hologram.png)

## 🛠️ Tech Stack

- **Three.js (r128)** — 3D rendering, custom orbit camera, procedural campus geometry
- **Vanilla JavaScript, HTML, CSS** — no frameworks, no build tools, no dependencies to install
- **Open-Meteo API** — live weather, keyless and free
- **localStorage** — persistence for events, chat, and Aura points
- **Single file.** The entire application — engine, UI, data layer — is one `index.html` (~110 KB). Open it and it runs.

Everything is procedurally generated at runtime: building geometry, facade window textures, grass, the sky gradient, even the emoji markers. There are zero image assets.

## 🚀 Run It

**Option 1:** Visit the live demo → https://anav-awasthi.github.io/campuspulse/

**Option 2:** Download `index.html` and double-click it. That's the whole install.

## 🔮 What's Next

- **Shared backend** (Firebase free tier) so events sync live across every student's phone
- College-email auth to keep it VIT-AP-only
- Push notifications when something starts near you
- A template any campus can fork — the map is data-driven

## 🙏 Credits

- Weather data by [Open-Meteo](https://open-meteo.com/) (CC BY 4.0)
- Campus layout referenced from public aerial photography of VIT-AP University, Amaravati

## 👥 Team

**Anav Awasthi** — VIT-AP University

---

*Built for VIT-AP Hackathon.init() 2026.*

