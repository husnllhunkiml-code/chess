========================================
 VOICE ROOM + 2-PLAYER CHESS  (ONLINE)
========================================
LATEST VERSION — SVG pieces + auto-seat + smooth animation

Files:
  index.html        - Full app
  server.js         - Node.js server (HTTP + WebSocket)
  package.json      - Dependencies
  package-lock.json - Lockfile

NEW IN THIS VERSION:
  - SVG CHESS PIECES: ab white/black pieces har device (phone/PC)
    pe 100% sahi dikhte hain (Unicode emoji bug pura fix)
  - AUTO SEAT: player 1 (host) = WHITE, player 2 = BLACK (automatic)
  - SMOOTH ANIMATION: piece apni purani jagah se nayi jagah tak
    smoothly slide hota hai
  - HOST SYSTEM: host kick kar sakta hai, host chale jaye to
    agla player naya host ban jata hai

HOW TO RUN (LOCAL):
  1. Node.js install karo (https://nodejs.org)
  2. Folder me:
        npm install
        node server.js
  3. Browser:  http://localhost:3000

HOW TO DEPLOY ONLINE (FREE - Render.com):
  1. github.com pe ye files push karo
  2. render.com pe "New + > Web Service"
     - Build:  npm install
     - Start:  node server.js
  3. Permanent URL (jaise your-app.onrender.com)

NOTE:
  - Voice ke liye HTTPS (online) ya localhost zaroori hai
  - Pure ONLINE app - server zaroori hai
