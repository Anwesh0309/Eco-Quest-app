# 🌱 ECO Quest - Campus Sustainability & AI Verification Portal

> **An AI-powered offline gamified sustainability portal built for college campuses.** Complete real-world eco-missions, play green games, earn Eco-Coins, and verify plant/tree saplings using local AI feature classification!

---

## ✨ Features

- 🌿 **Strict Plant & Tree AI Verifier**: Uses HTML5 Canvas pixel analysis (Chlorophyll Green Leaf Index $2G - R - B$) to verify living plants, trees, and saplings while rejecting non-plants (laptops, food, buildings).
- 📹 **Live Cyberpunk Viewfinder**: Supports live device camera snapping, laser scanline HUD overlay, and single-click proof test samples.
- 🎮 **Gamified Learning Suite**:
  - 🧠 **Eco-Knowledge Quiz**: Interactive questions with dancing Teddy 🧸 & Seedling 🌱 animations on correct answers + 🤖⚡ AI Quiz generator!
  - 🗑️ **Waste Sorting Rush**: Categorize items into Organic 🍂, Recyclable ♻️, and E-Waste 🔋.
  - 🔤 **Word Scramble**: Unscramble eco keywords.
  - ⚡ **Reflex Rush**: Fast-tap green targets.
- 🎁 **Rewards & Vouchers**: Redeem Eco-Coins for canteen discounts and eco-swag with interactive **📱 QR Code Modal Popups**.
- 📊 **Real-Time Campus Impact**: Dynamic counters for trees planted, CO2 saved, and zero-waste meals.
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
├── message.html                         # Primary Web App UI & AI Engine
├── local-server.js                      # Static Node.js HTTP dev server
├── vercel.json                          # Vercel deployment routing configuration
└── libs/                                # Local Offline AI Libraries
    ├── tf.min.js
    └── teachablemachine-image.min.js
```
