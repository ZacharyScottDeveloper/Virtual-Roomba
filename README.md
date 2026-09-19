# Virtual Roomba

A Python simulation of an autonomous robot vacuum that explores and cleans a room while avoiding obstacles.

https://github.com/user-attachments/assets/YOUR-GIF

> Replace the link above with your uploaded GIF or use `![Demo](demo.gif)` if you add one to the repo.

## About

This project recreates the basic behaviour of a robotic vacuum. The Roomba moves around a 2D room, detects walls, avoids collisions, and gradually covers every reachable tile instead of following a predefined path.

The simulation focuses on autonomous movement and coverage rather than perfect pathfinding.

## Features

- Autonomous room exploration
- Obstacle and wall avoidance
- Full room coverage algorithm
- Real-time visual simulation
- Configurable room layouts

## Files

```text
.
├── house-layouts/     # Room layout presets
├── demo.mp4           # Demonstration video
├── index.html         # Browser interface
├── roomba.py          # Simulation logic
└── styles.css         # Interface styling
```

## Running

Open `index.html` in your browser, then select a room layout to start the simulation.

## How it works

The robot repeatedly performs four steps:

1. Scan nearby tiles
2. Detect obstacles
3. Choose the next movement
4. Mark cleaned areas and continue

This produces realistic roaming behaviour similar to early robotic vacuum navigation.

## Future improvements

- Smarter coverage heuristics
- Adjustable robot speed
- Battery and docking simulation
- Cleaning statistics
