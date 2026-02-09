# 🏎️ NitroRacer - Multiplayer Racing Game

An adrenaline-pumping real-time multiplayer racing game built with Node.js, Socket.IO, and HTML5 Canvas.

![Game Screenshot](https://via.placeholder.com/800x400/0a0a1a/00ffaa?text=NitroRacer+Gameplay)

## 🚀 Features

- **Real-time Multiplayer** - Race against up to 20 players simultaneously
- **Power-up System** - Collect speed boosts, shields, missiles, and turbo boosts
- **Cross-platform** - Play on desktop or mobile with responsive controls
- **Live Leaderboard** - Compete for the top position
- **In-game Chat** - Communicate with other players
- **Minimap** - Track all players' positions
- **Auto-reset Races** - New races start every 2 minutes

## 🎮 How to Play

1. **Accelerate**: `W` or `↑`
2. **Brake/Reverse**: `S` or `↓`
3. **Turn Left**: `A` or `←`
4. **Turn Right**: `D` or `→`
5. **Use Power-up**: `SPACEBAR`
6. **Toggle Chat**: `E`

**Mobile**: Use on-screen touch controls

## 🛠️ Tech Stack

- **Backend**: Node.js, Express, Socket.IO
- **Frontend**: HTML5 Canvas, Vanilla JavaScript
- **Styling**: CSS3 with custom properties
- **Real-time**: WebSockets via Socket.IO
- **Hosting**: Render.com (backend) + Shared Hosting (frontend)

## 📦 Installation & Deployment

### Option A: Deploy to Render.com (Recommended)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/yourusername/multiplayer-racing-game)

1. Click the "Deploy to Render" button above
2. Wait for deployment to complete
3. Get your Render URL (e.g., `https://your-app.onrender.com`)
4. Update the server URL in `public/game.js`

### Option B: Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/multiplayer-racing-game.git
cd multiplayer-racing-game

# Install dependencies
cd server
npm install

# Start the server
npm start

# Open browser and visit
http://localhost:3000
