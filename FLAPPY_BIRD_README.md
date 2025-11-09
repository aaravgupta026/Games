# Flappy Bird Game

## Overview
This is a Flappy Bird game implementation with customizable speed control and sound effects.

## Features

### Speed Control
When you open the game, you'll be prompted to select a game speed:
- **0.25x** - Very Slow (for beginners)
- **0.5x** - Slow (easy mode)
- **0.75x** - Moderate
- **1x** - Normal (classic speed)
- **1.5x** - Fast
- **2x** - Very Fast (challenge mode)

### Sound Effects
The game includes two distinct sound effects:
1. **Flying Sound** - Australian EAS alarm (three-tone pattern) plays when the bird flaps
2. **Collision Sound** - Normal alarm clock beeping plays when the bird hits an obstacle

### Controls
- **Press SPACE** or **Click** anywhere to make the bird flap
- Navigate through the pipes without hitting them
- Your score increases each time you successfully pass through a pipe

## How to Play
1. Open `flappy-bird.html` in a web browser
2. Select your preferred game speed
3. Press SPACE or click to start flying
4. Avoid the green pipes and the ground
5. Try to get the highest score possible!

## Technical Details
- Built with HTML5 Canvas and vanilla JavaScript
- Uses Web Audio API for sound generation
- Responsive design with smooth animations
- Real-time collision detection

## Browser Compatibility
Works best in modern browsers that support:
- HTML5 Canvas
- Web Audio API
- ES6+ JavaScript

Recommended browsers: Chrome, Firefox, Safari, Edge (latest versions)
