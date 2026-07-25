<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,20,6&height=200&section=header&text=AI%20COIN%20EMPIRE&fontSize=55&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Real-Time%20Multiplayer%20Crypto%20Strategy%20Game&descAlignY=55&descSize=18" width="100%"/>

<br/>

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Firestore](https://img.shields.io/badge/Firestore-FF6F00?style=for-the-badge&logo=google-cloud&logoColor=white)](https://firebase.google.com/docs/firestore)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

> **🪙 Build your crypto empire. Mine, hack, trade — dominate the leaderboard.**
> A full-stack, real-time multiplayer strategy game powered by Firebase, featuring an interactive city map, hacking mini-games, and an evolving AI faction (DONA).

<br/>

</div>

---

## ✨ Overview

**AI Coin Empire** is a real-time multiplayer strategy game where players build cryptocurrency empires in a shared, persistent world. Mine digital coins, purchase and upgrade data centers and startups, hack rival players, trade on the open market, and fight for dominance on the global leaderboard — all in real-time powered by **Firebase Firestore**.

At the heart of the game is **DONA** — an evolving AI entity that players collectively power up through energy contributions, unlocking global game-changing abilities across 3 phases.

---

## 📸 Interface Screenshots

<div align="center">

<img src="./assets/ai_coin_empire_1.jpg" width="48%" alt="Empire Dashboard & Mining Rig" />
<img src="./assets/ai_coin_empire_2.jpg" width="48%" alt="Global Leaderboard & DONA AI Core" />

<br/><br/>

<img src="./assets/ai_coin_empire_3.jpg" width="48%" alt="Interactive Hack Mini-Game" />
<img src="./assets/ai_coin_empire_4.jpg" width="48%" alt="Marketplace & Asset Trading" />

</div>

---

## 🎮 Core Features

| Feature | Description |
|---|---|
| 🗺️ **Interactive City Map** | Zoom/pan city map with live NPC markers, landmarks, and player positions |
| ⛏️ **Crypto Mining Engine** | Dynamic mining rates based on hardware, skills, and DONA phase |
| 🏢 **NPC Economy** | Buy, sell, and upgrade Data Centers, Startups, and Stores |
| 💹 **Coin Market** | Real-time coin portfolio, trading, and dynamic pricing |
| 🔓 **Hacking Mini-Game** | Wordle-style password cracker for `ddos`, `phishing`, `ransomware`, `zeroday` attacks |
| 🌑 **Dark Web Market** | Reputation-gated black market for advanced hardware and consumables |
| 🤖 **DONA AI System** | 3-phase collective AI with global ability unlocks |
| 🏆 **Leaderboard** | Live global ranking by net worth |
| 🎖️ **Mission System** | Progressive objectives with coin + reputation rewards |
| 📊 **Skill Tree** | 6 skills: Mining, Hacking, Trading, Energy, Hardware, Defense |
| 🔊 **Ambient Sound Engine** | Dynamic audio based on game state |
| 🎨 **Dynamic Background** | Animated city background that reacts to DONA phase |
| 👑 **Admin Panel** | Full game management dashboard |
| 🔐 **Firebase Auth** | Google OAuth + Email/Password authentication |

---

## 🤖 DONA — The AI Faction

DONA is a collective AI entity that all players power together by contributing energy. As DONA evolves through phases, it unlocks powerful global buffs:

| Phase | Name | Key Abilities | Cost Multiplier |
|---|---|---|---|
| **1** | Çekirdek Şebeke | Company Access Unlock, Mining +10% | 1× |
| **2** | Dış Halka Sistemi | Remote Company Access, Cyber Attack +20% | 3× |
| **3** | Siber Omni-Link | Full Automation, Global Company Control, Production +50% | 5× |

---

## 🛠️ Tech Stack

```
Frontend:     React 18 + TypeScript (10,000+ lines)
Build Tool:   Vite
Database:     Firebase Firestore (real-time listeners)
Auth:         Firebase Authentication (Google + Email)
Animation:    Motion (Framer Motion)
Map Engine:   react-zoom-pan-pinch
Icons:        Lucide React
Styling:      Tailwind CSS + Custom CSS
Server:       Node.js (server.ts for streaming support)
```

---

## 📁 Project Structure

```
ai-coin-empire/
├── src/
│   ├── App.tsx              # Main game engine (10,000+ lines)
│   ├── types.ts             # Full type definitions
│   ├── constants.tsx        # NPC configs, hardware market, landmarks, missions
│   ├── firebase.ts          # Firebase config + re-exports
│   ├── ErrorBoundary.tsx    # React error boundary
│   ├── components/
│   │   ├── EventCountdown.tsx    # Live event timer
│   │   ├── HackMiniGame.tsx      # Hacking puzzle game
│   │   ├── Leaderboard.tsx       # Real-time global rankings
│   │   ├── AdminPanel.tsx        # Admin management UI
│   │   ├── AmbientSound.tsx      # Dynamic audio system
│   │   ├── DynamicBackground.tsx # Animated city background
│   │   └── CityMapBackground.tsx # SVG city map renderer
│   └── lib/
│       ├── gameUtils.ts          # Mining rates, pricing, net worth calculators
│       └── firestoreUtils.ts     # Firestore error handling & helpers
├── firebase-blueprint.json   # Full Firestore schema
├── firestore.rules           # Security rules
├── server.ts                 # Node.js streaming server
└── .env.example
```

---

## ⚡ Quick Start

**Prerequisites:** Node.js 18+, Firebase project

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ai-coin-empire.git
cd ai-coin-empire

# 2. Install dependencies
npm install

# 3. Configure Firebase
cp .env.example .env.local
# Fill in your Firebase project credentials

# 4. Deploy Firestore rules (optional)
firebase deploy --only firestore:rules

# 5. Start development
npm run dev
```

---

## 🔑 Environment Variables

```env
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
GEMINI_API_KEY=
```

---

## 🗄️ Firestore Schema

The game uses a carefully structured Firestore schema defined in `firebase-blueprint.json`:

```
/users/{userId}          → Player profiles, skills, inventory, portfolio
/global/npcs             → Shared NPC ownership state
/global/dona             → DONA AI collective state
/leaderboard             → Aggregated net worth rankings
/events                  → Active game events
/transactions            → Market transaction history
```

All game state updates use **Firestore batch writes** and **atomic increments** to prevent race conditions in multiplayer scenarios.

---

## 🏗️ Architecture Highlights

- **Real-Time Multiplayer**: `onSnapshot` listeners keep all clients in sync without polling
- **Optimistic UI**: Local state updates immediately, Firestore confirms asynchronously
- **Memoized Map Rendering**: `React.memo` + `useMemo` for 60fps city map with 50+ markers
- **Skill-Based Economy**: All rates (mining, hacking success, prices) computed from player skill levels
- **Error Recovery**: `ErrorBoundary` + `handleFirestoreError` wrapper for graceful degradation

---

## 🤝 Contributing

Pull requests are welcome! Please open an issue first for major changes.

---

## 📜 License

MIT © [Your Name](https://github.com/yourusername)

<div align="center">
<br/>
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,20,6&height=100&section=footer" width="100%"/>
</div>
