# PinBall

A physics-based pinball game built with HTML5 Canvas and Matter.js.

## Features

- **Realistic Physics**: Uses Matter.js for accurate ball physics and collisions
- **Multiple Scoring Elements**:
  - Bumpers (100 points each)
  - Targets (500-1000 points each)
  - Slingshots (50 points each)
- **Combo System**: Build combos for higher multipliers
- **Particle Effects**: Visual feedback on collisions
- **Plunger Mechanism**: Pull back and release for powerful shots
- **Ramps and Obstacles**: Navigate complex table layout
- **High Score Tracking**: Persistent high score storage
- **Customizable Controls**: Rebindable keyboard controls
- **Zoom and Rewind**: Camera controls and 5-second rewind feature

## Controls

- **Left Arrow**: Left flipper
- **Right Arrow**: Right flipper
- **Space**: Plunge/launch ball
- **Mouse**: Zoom with slider in control panel

## How to Play

1. Use the plunger (Space) to launch the ball
2. Control the flippers to keep the ball in play
3. Hit bumpers, targets, and slingshots for points
4. Build combos for multiplier bonuses
5. Avoid letting the ball drain at the bottom

## Running the Game

Open `index.html` in a web browser or serve it with a local web server.

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`