<div align="center">

# 🎮 2D Top-Down RPG

### Unity RPG Engine

[![Unity](https://img.shields.io/badge/Unity-2D-000000.svg)](https://unity.com)
[![C#](https://img.shields.io/badge/C%23-.NET-239120.svg)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

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

## Prerequisites

- **Unity** 2021.3 LTS or newer (2D template)
- **Git** (with [Git LFS](https://git-lfs.github.com/) recommended for asset files)

## Getting Started

```bash
# Clone the repository
git clone https://github.com/astafford8488/2dtopdownrpg.git

# Open in Unity
# 1. Launch Unity Hub
# 2. Click "Open" and select the cloned project folder
# 3. Open the main scene from Assets/Scenes/
# 4. Press Play to run the game in the editor
```

## Tech Stack

- **Engine:** Unity 2D
- **Language:** C#
- **Pattern:** Singleton-based manager architecture

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'feat: add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Status

Early development — core systems (game state, audio, scene management) are implemented. Gameplay systems in progress.

## License

MIT
