# Chess-Like Game

## Overview

A chess-inspired game on a 5x5 grid with real-time multiplayer capabilities. Players use unique characters with specific movement abilities. This project uses WebSocket for live interactions between players.

## Project Structure

```
/21BCE1961_SPARSHKandpal2
├── /client
│   ├── index.html       # HTML layout for the game
│   ├── styles.css       # Styling for the game interface
│   └── chess.js         # Client-side game logic
├── /server
│   └── server.js        # Server-side logic and WebSocket handling
├── package.json         # npm configuration file
└── package-lock.json    # npm lock file
```

## Setup

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd 21BCE1961_SPARSHKandpal2
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start the Server:**

   ```bash
   npm start
   ```

4. **Play the Game:**
   - Open your browser and go to `http://localhost:3000`.

## How to Play

- Click a piece to select it.
- Click a highlighted square to move the piece.
- The game will show whose turn it is.
- Notifications will indicate when a player wins.

## Dependencies

- **Express**: For the server.
- **ws**: For real-time communication.
