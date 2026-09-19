# 🤖 Virtual Roomba

A Python simulation of an autonomous robot vacuum that explores and cleans 2D room layouts.

**Demo:** [demo.mp4](demo.mp4)
**House Layouts:** [View Here](https://billy-bit.zescott.com/python/virtual-roomba)

## Overview

Virtual Roomba simulates the behaviour of a robotic vacuum using autonomous movement rather than a predefined route. The robot navigates around walls, avoids obstacles, and attempts to clean every reachable tile within a room.

## Features

- Autonomous exploration
- Wall and obstacle avoidance
- Complete room coverage
- Multiple room layouts
- Visual Python simulation

## Project Structure

.
├── house-layouts/      # Room layout files
├── roomba.py           # Main simulation
├── demo.mp4            # Demonstration
└── README.md

## Running

1. Install Python 3.
2. Run the simulation:

```bash
python roomba.py
```

3. Choose one of the layouts from the `house-layouts` folder when prompted (or as configured in the script).

## How It Works

The robot continuously repeats four steps:

1. Scan its surroundings
2. Detect walls and obstacles
3. Choose the next valid move
4. Mark the tile as cleaned and continue

The result is a realistic room-coverage simulation inspired by the navigation behaviour of early robotic vacuum cleaners.

## Author

**Zachary Scott**
