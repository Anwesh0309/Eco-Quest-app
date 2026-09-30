# 🌱 ECO Quest - Campus Sustainability & AI Verification Portal

> **An AI-powered offline gamified sustainability portal built for college campuses.** Complete real-world eco-missions, play green games, earn Eco-Coins, track student level progress, and verify plant/tree saplings using local AI feature classification!

---

## ✨ Features

- 🔐 **Student Auth & Account Switcher**:
  - **Student Login & Sign-Up Panel**: Toggle between Student Login and Registering a New Student ID.
  - **0% Progress Initialization**: New registered accounts initialize with **0% Level Progress**, 0 XP, and 0 Eco-Coins.
  - **Quick One-Click Demo Logins**: Instant switching between `STU-2026-01` (Manisha - Lvl 4 Guardian, 75%), `STU-2026-02` (Rahul Sharma - Lvl 3, 62%), and `STU-2026-NEW` (New Student - 0% Fresh ID).
  - **Local Persistence**: User state automatically syncs to browser `localStorage`.
- 📊 **Real-Time Student Progress Bar & Level System**:
  - Dynamic Progress Bar tracking Level 1 Novice Seedling (0% starting) up to Level 5 Eco Legend.
  - Real-time XP gains from completing AI plant verification missions, quizzes, waste sorting, and reflex games.
  - Interactive toast notifications and level-up audio/confetti celebrations.
- 📱 **Digital Campus Eco Passport (ID Pass Modal)**:
  - Interactive student ID pass with student avatar, ID number, department, level progress bar, and digital barcode.
- 🌿 **Strict Plant & Tree AI Verifier**: Uses HTML5 Canvas pixel analysis (Chlorophyll Green Leaf Index $2G - R - B$) to verify living plants, trees, and saplings while rejecting non-plants (laptops, food, buildings).
- 📹 **Live Cyberpunk Viewfinder**: Supports live device camera snapping, laser scanline HUD overlay, and single-click proof test samples.
- 🎮 **Gamified Learning Suite**:
  - 🧠 **Eco-Knowledge Quiz**: Interactive questions with dancing Teddy 🧸 & Seedling 🌱 animations on correct answers + 🤖⚡ AI Quiz generator!
  - 🗑️ **Waste Sorting Rush**: Categorize items into Organic 🍂, Recyclable ♻️, and E-Waste 🔋.
  - 🔤 **Word Scramble**: Unscramble eco keywords.
  - ⚡ **Reflex Rush**: Fast-tap green targets.
- 🎁 **Rewards & Vouchers**: Redeem Eco-Coins for canteen discounts and eco-swag with interactive **📱 QR Code Modal Popups**.
- 🏆 **Synchronized Campus Leaderboards**: Dynamic rank sorting for individual student champions and department cups.
- 📜 **Official Eco Certificate Generator**: Issue customizable verified campus sustainability certificates.
- 📱 **Mobile Screen Optimized**: Touch momentum scrolling (`-webkit-overflow-scrolling: touch`) and responsive mode toggle (`🖥️ Wide` / `📱 Phone`).

---

## 🚀 Live Demo & Local Server

- **Vercel Live App:** [https://eco-quest-lime.vercel.app/message.html](https://eco-quest-lime.vercel.app/message.html)
- **Local Server:** Run `node local-server.js` and open `http://localhost:3000`

---

## 🛠️ Project Structure

```
├── index.html                           # Root redirect entrypoint
├── message.html                         # Primary Web App UI, Auth Engine & AI Engine
├── local-server.js                      # Static Node.js HTTP dev server
├── vercel.json                          # Vercel deployment routing configuration
└── libs/                                # Local Offline AI Libraries
    ├── tf.min.js
    └── teachablemachine-image.min.js
```

