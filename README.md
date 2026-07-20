# Mimic City

**A 26now multiplayer social deduction game set in a living AI-driven city.**

** Game Director : Prithvi Singh **
---

## Project Overview

Mimic City is an online multiplayer social deduction game where detectives investigate a living city while hidden Mimic players blend seamlessly into hundreds of AI-controlled civilians.

Unlike traditional social deduction games, Mimics are not pretending to be other players—they are pretending to be ordinary citizens.

---

## Tagline

> **One of these civilians is a real player. Find them before they disappear into the crowd.**

---

## Problem Statement

Most social deduction games confine players to a small room with a limited number of suspects. This restricts observation, movement, and emergent storytelling.

Players who enjoy detective work, stealth, and psychological gameplay often lack a multiplayer experience that feels like investigating a real city rather than participating in a scripted role game.

---

## Solution

Mimic City transforms an entire city into the gameplay space.

* **Detectives** gather evidence, analyze behavior, and coordinate investigations.
* **Mimics** blend into civilian life, complete secret objectives, and escape before enough evidence is collected.

The result is a dynamic detective experience driven by observation, deception, teamwork, and procedural city events.

---

## Core Game Loop

### Detectives

* Patrol districts
* Investigate crime scenes
* Analyze CCTV and witness reports
* Track suspicious civilians
* Coordinate with teammates
* Arrest Mimics before they escape

### Mimics

* Receive a civilian identity
* Follow believable routines
* Complete hidden objectives
* Avoid attracting attention
* Merge into crowds
* Escape the city undetected

---

## Tech Stack (Planned)

### Game Engine

* **Unity 6 / Unity LTS**

### Networking

* **Photon Fusion** or **Netcode for GameObjects**

### Backend

* **Node.js**
* **Express.js**
* **MongoDB**

### AI Systems

* Utility AI
* Behavior Trees
* Navigation Mesh (NavMesh)

### Tools

* Blender
* Figma
* GitHub
* VS Code

---

## System Architecture

Player Clients (Unity)
↓
Multiplayer Networking Layer
↓
Matchmaking Service
↓
Game Server
↓
AI Civilian Simulation
↓
Evidence & Investigation System
↓
MongoDB Backend

**System architecture diagram:** *Coming soon*

---

## Match Structure

| Total Players | Mimics | Detectives |
| ------------- | -----: | ---------: |
| 2             |      1 |          1 |
| 3             |      1 |          2 |
| 4             |      2 |          2 |
| 5             |      2 |          3 |
| 6             |      2 |          4 |
| 7             |      3 |          4 |
| 8             |      3 |          5 |

---

## World Design

Each match takes place in a colorful low-poly city containing approximately **80–200 AI civilians**.

Civilian routines include:

* Going to work
* Shopping
* Waiting for buses
* Visiting cafés
* Reading newspapers
* Walking dogs
* Exercising
* Watching street performers

The city is not a backdrop—the city is the gameplay.

---

## Dynamic City Events

Procedurally generated events may include:

* Heavy rain reducing visibility
* Street festivals creating large crowds
* Power outages disabling cameras
* Rush hour traffic
* Construction blocking roads
* Police checkpoints
* Fire drills evacuating buildings

These events force both teams to adapt their strategies in real time.

---

## Investigation Systems

### Detective Tools

* Drone
* Motion Sensor
* Thermal Scanner
* Evidence Analyzer
* Surveillance Camera Network

### Evidence Sources

* Witness statements
* CCTV footage
* Footprints
* Suspicious movement patterns
* Crime scenes
* Civilian reports

---

## Mimic Gadgets

* Portal Gun
* Smoke Bomb
* Pogo Stick
* Speed Shoes
* Cardboard Box
* Banana Trap
* Confetti Bomb
* Fake Witness Device

These gadgets are designed for memorable, emergent gameplay rather than realistic combat.

---

## Art Direction

Mimic City uses a **colorful low-poly art style** with a modular character system.

Each civilian is generated from interchangeable:

* Hairstyles
* Hats
* Glasses
* Clothing
* Shoes
* Backpacks
* Accessories

This creates thousands of unique-looking NPCs while keeping silhouettes readable for detective gameplay.

---

## Folder Structure

```text
mimic-city/
├── Assets/
├── Scripts/
│   ├── AI/
│   ├── Networking/
│   ├── Gameplay/
│   ├── Investigation/
│   ├── UI/
│   └── Utilities/
├── Backend/
├── Docs/
│   ├── Vision/
│   ├── Architecture/
│   ├── Gameplay/
│   └── Art/
├── Builds/
├── README.md
└── LICENSE
```

---

## Planned Gameplay Features

* Online multiplayer matchmaking
* AI civilian simulation
* Procedural investigations
* Evidence collection system
* District lockdown mechanics
* Dynamic weather and events
* Spectator and replay system
* Cross-platform support
* Cosmetic progression
* Party matchmaking

---

## Long-Term Progression

Players unlock **cosmetic-only** rewards:

* Outfits
* Hats
* Emotes
* Victory poses
* Backpacks
* Pets
* Footstep effects
* Player titles

No gameplay advantages are tied to progression.

---

## Development Roadmap

### Phase 1 — Prototype

* Basic city map
* AI civilian movement
* Player movement
* Mimic identity system
* Detective accusation mechanic

### Phase 2 — Multiplayer Alpha

* Networking
* Matchmaking
* Evidence system
* CCTV system
* Crowd blending

### Phase 3 — Vertical Slice

* Full art direction
* Dynamic events
* Gadgets
* Audio and UI polish
* Playtesting

### Phase 4 — Public Beta

* Progression system
* Cosmetics
* Analytics
* Server scaling
* Community features

---

## Local Setup (Planned)

```bash
# Clone repository
git clone https://github.com/26now/mimic-city.git

# Open Unity project
# Launch backend service
cd Backend && npm install && npm run dev
```

---

## Vision Statement

Mimic City is not about having the strongest weapon.

It is about creating unforgettable moments where detectives slowly piece together a mystery while one player desperately tries to remain just another face in the crowd.

The defining moment of the game is when a detective points at a completely ordinary civilian and says:

> **“That’s not an NPC.”**

—and they are right.

---

## Author

**Vaibhav Joshi**

**GitHub:** https://github.com/VjTbh

**Organization:** https://github.com/26now

---

## License & Copyright

Copyright (c) 2026 Vaibhav Joshi

All rights reserved.

This repository contains proprietary game design documents, gameplay systems, architecture, AI simulation concepts, networking design, visual assets, and source code for the **Mimic City** platform.

Unauthorized copying, redistribution, modification, commercial use, or creation of derivative works based on this project is prohibited without prior written permission from the author.

All gameplay concepts, investigation systems, procedural city simulation mechanics, and associated documentation are protected as proprietary intellectual property of the project owner.
