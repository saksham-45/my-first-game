# 🎮 Roller Ball - 3D Platformer Game

A 3D platformer game built with Unity where players control a rolling ball through challenging levels, collecting points and avoiding obstacles.

## 🎯 Game Overview

**Roller Ball** is a physics-based 3D platformer where you control a rolling ball through increasingly difficult levels. The goal is to reach the end of each level while collecting as many points as possible and avoiding falling off the platforms.

### 🎮 Gameplay Features
- **Physics-based movement** with realistic ball rolling mechanics
- **Multiple levels** with increasing difficulty
- **Score system** for competitive gameplay
- **Smooth camera following** for optimal viewing angles
- **Level completion** system with UI feedback
- **Game over and restart** mechanics

## 🚀 Getting Started

### Prerequisites
- **Unity 2022.3 LTS** or later
- Basic knowledge of Unity Editor
- Git for version control

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/roller-ball-game.git
   cd roller-ball-game
   ```

2. **Open in Unity**
   - Launch Unity Hub
   - Click "Open" and select the project folder
   - Wait for Unity to import all assets

3. **Run the game**
   - Open the `Lvl1` scene from `Assets/Scenes 1/`
   - Click the Play button in Unity Editor

## 🎮 Controls

- **WASD Keys**: Move the ball
  - **W**: Forward movement (automatic)
  - **A**: Move left
  - **D**: Move right
  - **S**: No specific function (ball moves forward automatically)

## 🏗️ Project Structure

```
Assets/
├── Scripts/           # C# game logic scripts
├── Scenes 1/         # Game levels and scenes
├── Materials/         # 3D materials and textures
├── Prefabs/          # Reusable game objects
└── Meta files        # Unity metadata (auto-generated)
```

### 📁 Scripts Overview

| Script | Purpose |
|--------|---------|
| `PlayerMovement.cs` | Handles ball physics and input |
| `GameManager.cs` | Manages game state and level progression |
| `PlayerCollision.cs` | Handles collision detection and scoring |
| `Score.cs` | Manages score display and updates |
| `EndTrigger.cs` | Detects level completion |
| `FollowPlayer.cs` | Camera follow behavior |
| `LevelComplete.cs` | Level completion logic |

## 🎨 Game Design

### Core Mechanics
- **Continuous forward movement** - The ball automatically moves forward
- **Lateral control** - Players can move left and right to avoid obstacles
- **Physics-based gameplay** - Realistic ball rolling and collision
- **Progressive difficulty** - Each level introduces new challenges

### Level Design
- **Level 1**: Introduction to basic mechanics
- **Level 2**: Increased complexity with more obstacles

## 🛠️ Development

### Adding New Levels
1. Create a new scene in `Assets/Scenes 1/`
2. Design your level layout
3. Add the `EndTrigger` object for level completion
4. Update the build settings to include the new scene

### Modifying Gameplay
- **Movement speed**: Adjust `forwardForce` and `sidewaysForce` in `PlayerMovement.cs`
- **Scoring**: Modify the scoring system in `PlayerCollision.cs`
- **Level progression**: Update `GameManager.cs` for custom level flow

## 🚧 Known Issues & Limitations

- Ball may occasionally get stuck on certain geometry
- Camera follows at a fixed distance (could be improved with dynamic zooming)
- Limited level variety in current version

## 🔮 Future Enhancements

- [ ] **Power-ups** (speed boost, jump ability)
- [ ] **Multiple ball types** with different physics properties
- [ ] **Level editor** for community-created content
- [ ] **Sound effects and music**
- [ ] **Particle effects** for visual polish
- [ ] **Mobile support** with touch controls
- [ ] **Leaderboard system**

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Contribution Guidelines
- Follow Unity coding standards
- Add comments to complex logic
- Test your changes thoroughly
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with Unity 2022.3 LTS
- Inspired by classic 3D platformer games
- Community feedback and testing

## 📞 Support

If you encounter any issues or have questions:
- Create an issue on GitHub
- Check the Unity documentation
- Review the script comments for implementation details

---

**Happy Gaming! 🎮✨**