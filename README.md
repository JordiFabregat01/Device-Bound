# Device Bound

**Device Bound** is a first-person puzzle-platformer built solo in C++ on top of a partial game engine framework. Developed over a few weeks in 2024, the game challenges players to escape a research facility using a single experimental teleportation device.

## Overview

You play as a scientist equipped with a prototype teleportation ball. Throw the device — wherever it lands, you teleport.

The game revolves around:
- Precision throws  
- Bouncing trajectories  
- Strategic experimentation with a save/rewind system  

After a short tutorial, the game expands into **five puzzle stages**, each introducing new applications of the core mechanic.

## Features

- **Teleportation mechanic**: throw a ball to teleport to its landing point  
- **Three throw velocities**: slow, base, and fast for different trajectories  
- **Physics-based gameplay**: bouncing enables bank shots around obstacles  
- **Save & rewind system**:  
  - `G` → save position (15s snapshot)  
  - `R` → return to saved position  
- **Progressive level design**: tutorial + 5 puzzle stages  
- **Custom levels** built in Blender  

## Development

Solo project built on top of a partially provided C++ engine framework from Universitat Pompeu Fabra.

### Implemented:

- Full game design and core mechanics  
- Rendering pipeline completion + **frustum culling**  
- **Phong shading** with distance-based fog  
- Player controller and movement systems  
- Throw/teleport system and ball physics  
- Save/rewind mechanic  
- Stage manager and transitions  
- Level design (Blender) and character animation (Mixamo)  

## Framework Note

The base engine framework (renderer scaffolding and subsystems) was provided as part of a university course at Universitat Pompeu Fabra.

> The framework is university intellectual property, so the full source code is not publicly available. This repository documents the work built on top of it.

## Tech Stack

- C++  
- Custom game on partial UPF engine framework  
- Blender (level design)  
- Mixamo (animation)  

## Documentation

- [Game Design Document (GDD)](https://github.com/JordiFabregat01/Device-Bound/blob/main/GDD_DeviceBound.pdf)
