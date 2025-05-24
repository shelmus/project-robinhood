# Project Robinhood

**Description**  
Project Robinhood is a Python 3-based interactive arcade target game system built primarily for use with Nerf-style foam dart games. It utilizes recycled mechanical keyboard switches as hit sensors connected to a Raspberry Pi via GPIO. The system supports addressable RGB feedback per key, multiple scoring modes, and is designed for future scalability including multi-target synchronization.

**Core Features**
- Written in Python 3
- Individual GPIO-mapped keyboard switches for hit detection
- Individually addressable RGB lighting per target
- Multiple game modes (time trial, accuracy, elimination, etc.)
- Modular architecture for easy expansion and additional game modes
- Potential for multi-target system synchronization across Pi units
- Real-time scoring and game logic

**Future Ideas**
- Web dashboard for score viewing and game configuration
- Companion mobile app for remote control or spectator display
- Sound/voice feedback through Pi audio output
- Modular target expansion via network protocol

**Current Status**
- GPIO input framework: [Not Started]
- RGB control integration: [Not Started]
- Game mode structure: [Planning]
- Scoring system: [Planning]

This project includes a memory continuity system under `docs/readme_MemoryUnit.md` to support multi-user development and AI-assisted progress tracking.