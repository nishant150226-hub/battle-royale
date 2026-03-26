<h1 align="center">⚔️ Multiplayer Battle Royale Game</h1>

<p align="center">
A fast-paced <b>browser multiplayer battle royale shooter</b> built using <b>Node.js, Socket.IO, and HTML5 Canvas</b>.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js">
<img src="https://img.shields.io/badge/Socket.IO-Realtime-black?style=for-the-badge&logo=socketdotio">
<img src="https://img.shields.io/badge/JavaScript-Game%20Logic-yellow?style=for-the-badge&logo=javascript">
<img src="https://img.shields.io/badge/Canvas-Rendering-blue?style=for-the-badge">
<img src="https://img.shields.io/github/stars/nishant150226-hub/battle-royale?style=for-the-badge">
<img src="https://img.shields.io/github/forks/nishant150226-hub/battle-royale?style=for-the-badge">
</p>

---

# 🎮 Gameplay

A real-time **battle royale survival game** where players fight bots and other players in a shrinking zone.

Features include:

* 🔫 Multiple weapons
* 🤖 AI enemy bots
* 🌎 Large scrolling world
* 🎯 Real-time shooting
* 👥 Multiplayer support
* 🗺 Minimap system
* ☠ Shrinking battle zone

---

# 🕹 Gameplay Preview

<p align="center">
<img src="screenshots/gameplay.gif" width="800">
</p>

*(Add your gameplay GIF inside `/screenshots/gameplay.gif`)*

---

# ✨ Features

### 🔫 Weapon System

* Pistol
* Shotgun
* Sniper
* SMG

Each weapon has unique:

* fire rate
* damage
* bullet spread
* projectile speed

---

### 🤖 Enemy Bots

Bots automatically:

* Track players
* Move toward targets
* Shoot at enemies
* Take damage and die

---

### 🌍 Dynamic World

* Large **2000x2000 game world**
* Camera follows player
* Boundary collision
* Smooth player movement

---

### ☢ Battle Zone

A shrinking safe zone that:

* Reduces in size over time
* Damages players outside the zone
* Forces players into combat

---

### 👥 Multiplayer System

Real-time multiplayer using **WebSockets**.

Players can:

* Join the game
* Move in real time
* Shoot
* Disconnect

---

# 🛠 Tech Stack

| Technology       | Purpose                |
| ---------------- | ---------------------- |
| **Node.js**      | Game server            |
| **Express.js**   | Backend framework      |
| **Socket.IO**    | Multiplayer networking |
| **HTML5 Canvas** | Game rendering         |
| **JavaScript**   | Game logic             |

---

# 📂 Project Structure

```
battle-royale
│
├── server.js        # Multiplayer server
├── package.json
│
├── public
│   ├── index.html
│   ├── game.js
│   ├── sounds
│
└── screenshots
    └── gameplay.gif
```

---

# 🚀 Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/nishant150226-hub/battle-royale.git
```

### 2️⃣ Enter project folder

```
cd battle-royale
```

### 3️⃣ Install dependencies

```
npm install
```

### 4️⃣ Start the server

```
npm start
```

The server will run on:

```
http://localhost:3000
```

---

# 🎮 Controls

| Key             | Action     |
| --------------- | ---------- |
| **W**           | Move Up    |
| **S**           | Move Down  |
| **A**           | Move Left  |
| **D**           | Move Right |
| **Mouse**       | Aim        |
| **Mouse Click** | Shoot      |

---

# 🗺 Game Mechanics

### Combat

* Bullets damage enemies
* Bots can attack players
* Weapon recoil system

### Health System

* Player health decreases when hit
* Smooth animated health bar

### Effects

* Bullet impacts
* Muzzle flash
* Hit indicators

---

# 📈 Future Improvements

* 🧑‍🤝‍🧑 Player vs Player combat
* 🎒 Loot and inventory system
* 🏠 Buildings and obstacles
* 🔊 Sound improvements
* 📱 Mobile support
* 🎨 Improved graphics

---

# 👨‍💻 Author

**Nishant**

GitHub:
https://github.com/nishant150226-hub

---

# ⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
🚀 Contribute improvements

---

# 📜 License

Released under the **MIT License**.

---

<p align="center">
🔥 Built with Node.js and Socket.IO
</p>
