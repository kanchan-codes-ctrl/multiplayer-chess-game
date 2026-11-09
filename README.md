# ♟️ Real-Time Multiplayer Chess Game

A two-player online chess game built with Node.js and Socket.io. Two players can play from different browsers or devices in real time, and extra users join as spectators.

## Features
- Real-time move sync using WebSockets (Socket.io)
- Server-side move validation with chess.js
- Turn control: only the right player can move
- Drag-and-drop pieces
- Board flips for the Black player
- Spectator mode for extra users

## Tech Stack
- *Frontend:* HTML, CSS, Tailwind CSS, JavaScript
- *Backend:* Node.js, Express.js
- *Real-time:* Socket.io
- *Chess logic:* chess.js
- *Template engine:* EJS

## How to Run
1. Clone the repository
   git clone https://github.com/APKA-USERNAME/multiplayer-chess-game.git
2. Go to the project folder
   cd multiplayer-chess-game
3. Install dependencies
   npm install
4. Start the server
   node app.js
5. Open http://localhost:3000 in two browser tabs.
   The first tab is White, the second is Black.

## Author
Kanchan Sharma
GitHub: github.com/kanchan-codes-ctrl
