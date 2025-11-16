# ⚽ Haxball — Multiplayer Online Football (LAN Version)

This project is a lightweight, browser-based multiplayer football game inspired by **Haxball**.
Built using **HTML, CSS, JavaScript, Express, and WebSockets**, it enables smooth real-time gameplay over a local network.

---

## 🎮 Why This Game Is Fun

* Fast, responsive 2D football mechanics
* Instant browser-based play — no installs required
* Stable LAN multiplayer with minimal latency
* Simple, clean codebase ideal for learning or extending
* Easy to host, share, and customize

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js + Express
* **Networking:** WebSocket (ws)
* **Static Assets:** Served from `public/`

```
Haxball/
 ├── public/
 │    ├── index.html
 │    ├── script.js
 │    ├── styles.css
 ├── server.js
 ├── package.json
 └── README.md
```

---

## 🚀 Running the Game Locally

### 1. Install Node.js

Verify installation:

```bash
node -v
```

### 2. Install dependencies

From the project folder:

```bash
npm install
```

### 3. Start the server

```bash
node server.js
```

You should see:

```
Server running on port 4000
```

### 4. Play the game

Open in a browser:

```
http://localhost:4000
```

---

## 🧑‍🤝‍🧑 LAN Multiplayer Setup

1. Ensure all players are on the same WiFi/network.
2. Find the host machine’s IP:

   ```bash
   ifconfig | grep inet
   ```
3. Other players connect using:

   ```
   http://<host-ip>:4000
   ```

---

## 📌 Future Improvements

* Score tracking
* Goal detection
* Match timer
* Game lobby or rooms
* Improved physics
* Online (non-LAN) matchmaking

---

## 📄 License

This project is open-source and free to modify.
