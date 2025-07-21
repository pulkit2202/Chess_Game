# ♟️ Real-Time Multiplayer Chess Game

A real-time multiplayer chess game built with **Node.js**, **Express**, **Socket.io**, and **Chess.js**. Supports two players (White and Black) and unlimited spectators.

## 🔧 Features

- Real-time two-player chess using WebSockets (Socket.io)
- Drag-and-drop chess piece movement
- Automatic role assignment (White, Black, Spectator)
- Game state synchronization using FEN notation
- Spectator support for viewing ongoing games
- Turn-based move enforcement
- Board flip for Black player's perspective
- Unicode rendering of chess pieces
- Clean and simple UI

---

## 📦 Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Socket.io](https://socket.io/)
- [Chess.js](https://github.com/jhlywa/chess.js)
- [EJS](https://ejs.co/) (for templating)
- Vanilla JS (frontend)

---

## 🚀 Getting Started

### Prerequisites

- Node.js installed
- Git (optional)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/chess-game.git
cd chess-game

# Install dependencies
npm install

# Start the server
npm start
