# Device Bound

**Device Bound** is a first-person puzzle-platformer I built solo in C++ on top of a partial game-engine framework from Universitat Pompeu Fabra, over a few weeks in early 2025, for the Video Games course (grade 9.0). You escape an underground weapons facility with an experimental device: a ball that teleports you to wherever it lands.

**[▶ Walkthrough video](https://youtu.be/bmbzjY5y9Wg)** · **[itch.io page](https://realsria.itch.io/device-bound)** · **[Game Design Document (PDF)](GDD_DeviceBound.pdf)**

## Overview

You play a scientist with a prototype teleportation ball. Throw it; wherever it lands, you are. After a short tutorial the game opens into a series of puzzle areas, each built around a different use of the throw.

## Features

- **Throw to teleport:** three throw strengths (slow, base, fast) for different distances and arcs
- **Save and rewind:** `G` saves your position (a 15-second snapshot) and `R` returns you to it, so a missed throw costs nothing
- **A tutorial, then a series of puzzle areas**, with levels modelled in Blender

## What I built

On top of the course framework (renderer scaffolding and subsystem stubs) I designed and built:

- the game design, the mechanics and the level content
- the player controller, the throw/teleport system, the ball, save/rewind and the stage manager
- renderer extensions: **frustum culling** and distance culling, and **Phong shading with distance fog** in GLSL
- the level models in Blender; the character is animated with Mixamo

## Why there's no code here

The framework is Universitat Pompeu Fabra's course material and remains university IP, so the source can't be published. This repository holds the Game Design Document; the video shows the game running.

## Tech

C++ · OpenGL · GLSL · SDL · Blender · Mixamo
