# Online-Car-Game-Player-Website

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://your-demo-link.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
<img width="1880" height="1644" alt="image" src="https://github.com/user-attachments/assets/2bd88432-29f1-4baf-afa8-ce6a69ec3933" />

<div align="center">
  <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="TurboRacer Screenshot" width="800"/>
  <p><em>Experience high-speed racing in your browser!</em></p>
</div>

##  Overview

**TurboRacer** is a fully responsive online car game player website built with pure HTML, CSS, and JavaScript. This interactive platform provides an engaging racing experience with realistic game mechanics, score tracking, and a sleek gaming interface.

## Features

### **Core Gameplay**
- **Interactive Racing**: Control your car with keyboard or on-screen controls
- **Obstacle Avoidance**: Dodge randomly generated obstacles at high speeds
- **Real-time Scoring**: Score based on speed, distance, and time
- **Collision Detection**: Realistic physics with collision feedback

### **Controls**
- **Keyboard Controls**: Arrow keys for movement, spacebar for boost
- **On-screen Controls**: Touch-friendly buttons for mobile devices
- **Game Controls**: Start, Pause, Restart, and Fullscreen functionality

### **Player Dashboard**
- **Player Statistics**: Track wins, top speed, win rate, and more
- **Game Categories**: Organized racing game library
- **Game Recommendations**: Discover new racing games

### **Design**
- **Modern UI**: Dark theme with vibrant racing-inspired colors
- **Fully Responsive**: Works on desktop, tablet, and mobile devices
- **Smooth Animations**: Road movement, car physics, and visual effects

## Technologies Used

- **HTML5**: Semantic markup and game structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript**: Game logic, controls, and interactive features
- **Font Awesome**: Icon toolkit for UI elements
- **Google Fonts**: Typography

## Quick Start

### Option 1: Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/turboracer.git

# Navigate to the project directory
cd turboracer

# Open the HTML file in your browser
open index.html
# or
xdg-open index.html
# or simply double-click the index.html file
```

### Option 2: Use with Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"
3. The game will open in your default browser at `http://localhost:5500`

## How to Play

### Basic Controls
- **Left Arrow / A**: Move car left
- **Right Arrow / D**: Move car right
- **Up Arrow / W**: Accelerate
- **Spacebar**: Turbo boost
- **P**: Pause/Resume game
- **R**: Restart game

### Game Objectives
1. Avoid obstacles by moving left and right
2. Maintain high speed to maximize your score
3. Use boost strategically for difficult obstacles
4. Beat your high score!

### Scoring System
- **Base Score**: Increases with speed
- **Distance Bonus**: Points for distance covered
- **Time Bonus**: Points for survival time
- **Speed Multiplier**: Higher speed = more points

## Responsive Design

TurboRacer is optimized for all screen sizes:

- **Desktop (≥1024px)**: Full sidebar with detailed stats
- **Tablet (768px-1023px)**: Adjusted layout for medium screens
- **Mobile (<768px)**: Stacked layout with touch-optimized controls

## Customization

### Game Difficulty
Adjust these variables in the JavaScript section:

```javascript
// Line 153-157
let gameInterval; // Current: 100ms (adjust for faster/slower updates)
let obstacleInterval; // Current: 1500ms (adjust for obstacle frequency)

// Line 290-293 (in startGame function)
gameInterval = setInterval(updateGame, 100); // Game loop speed
obstacleInterval = setInterval(createObstacle, 1500); // Obstacle spawn rate
```

### Visual Customization
Modify CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #ff3c00; /* Main accent color */
    --secondary-color: #1a1a2e; /* Background color */
    --accent-color: #00ccff; /* Highlight color */
    --dark-color: #0f0f1a; /* Dark background */
    --light-color: #f5f5f5; /* Text color */
    --success-color: #00cc66; /* Success/score color */
}
```

### Add New Games
Add game cards to the HTML:

```html
<div class="game-card">
    <img src="your-game-image.jpg" alt="Game Name">
    <div class="game-card-content">
        <h4>Game Name</h4>
        <p>Game description</p>
    </div>
</div>
```

##  Testing

### Browser Compatibility
-  Chrome 90+
-  Firefox 88+
-  Safari 14+
-  Edge 90+
-  Mobile browsers (iOS Safari, Chrome Mobile)

### Known Issues
- Sound effects not implemented (planned for v2.0)
- Multiplayer functionality pending
- Advanced physics engine in development

##  Future Enhancements

### Planned Features
- **Multiplayer Mode**: Race against friends online
- **Power-ups**: Collectible items during gameplay
- **Car Customization**: Custom paint jobs and upgrades
- **Leaderboards**: Global and friend-based rankings
- **Sound Effects**: Engine sounds, collisions, and music

### Version Roadmap
- **v1.0** (Current): Basic racing game with single-player mode
- **v1.5**: Add power-ups and car customization
- **v2.0**: Multiplayer functionality and leaderboards
- **v2.5**: Advanced physics and track editor

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Setup
```bash
# Install dependencies (if any are added)
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Game design inspired by classic arcade racing games
- UI/UX patterns from modern gaming platforms
- Icons by [Font Awesome](https://fontawesome.com)
- Demo images from [Unsplash](https://unsplash.com)
- Color palette from [Coolors](https://coolors.co)

## Contact & Support

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
