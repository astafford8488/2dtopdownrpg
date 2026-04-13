<div align="center">

# 🎮 2D Top-Down RPG

### Unity RPG Engine

[![Unity](https://img.shields.io/badge/Unity-2D-000000.svg)](https://unity.com)
[![C#](https://img.shields.io/badge/C%23-.NET-239120.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)

*A Unity 2D top-down RPG with game state management, scene transitions, and audio system.*

</div>

---

## Features

- **Game State Machine** — MainMenu, Town, Dungeon, Paused, GameOver states
- **Scene Management** — Async scene loading with state transitions
- **Audio System** — Centralized AudioManager with singleton pattern
- **Singleton Architecture** — Persistent managers across scene loads

## Core Systems

```
Assets/Scripts/Core/
├── GameManager.cs      # Game state machine and scene management
└── AudioManager.cs     # Centralized audio control
```

## Tech Stack

- **Engine:** Unity 2D
- **Language:** C#
- **Pattern:** Singleton-based manager architecture

## Status

Early development — core systems (game state, audio, scene management) are implemented. Gameplay systems in progress.

## License

MIT
