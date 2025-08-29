# Quick Setup Guide 🚀

## 🎯 Getting Started in 5 Minutes

### Prerequisites Check
- [ ] Unity 2022.3 LTS installed
- [ ] Git installed
- [ ] Basic Unity knowledge

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/roller-ball-game.git
cd roller-ball-game
```

### 2. Open in Unity
1. Launch Unity Hub
2. Click "Open" → "Add project from disk"
3. Select the project folder
4. Wait for Unity to import (2-5 minutes)

### 3. Run the Game
1. In Unity, go to `Assets/Scenes 1/Lvl1.unity`
2. Click the Play button (▶️)
3. Use WASD keys to control the ball
4. Try to reach the end without falling!

## 🎮 Controls
- **W**: Forward (automatic)
- **A**: Move left
- **D**: Move right
- **S**: No function (ball moves forward automatically)

## 🔧 Development Setup

### Code Editor
- **VS Code**: Install Unity extension
- **Rider**: Unity support built-in
- **Visual Studio**: Unity tools available

### Project Structure
```
Assets/
├── Scripts/           # Your C# code here
├── Scenes 1/         # Game levels
├── Materials/         # 3D materials
└── Prefabs/          # Reusable objects
```

### First Steps
1. **Explore Scripts**: Check out `PlayerMovement.cs`
2. **Modify Values**: Try changing `forwardForce` in the inspector
3. **Add Objects**: Create new cubes in the scene
4. **Test Changes**: Play the scene to see your modifications

## 🚨 Common Issues

### Unity Won't Open Project
- Check Unity version (2022.3 LTS recommended)
- Verify project folder structure
- Try "Open project from disk" in Unity Hub

### Scripts Not Working
- Check Console for errors
- Verify script names match class names
- Ensure scripts are attached to GameObjects

### Performance Issues
- Check frame rate in Game view
- Use Unity Profiler for analysis
- Reduce object count in scenes

## 📚 Next Steps

### For Beginners
1. Read the [README.md](README.md)
2. Check [PROJECT_OVERVIEW.md](PROJECT_OVERVIEW.md)
3. Experiment with existing scripts
4. Try Unity's built-in tutorials

### For Developers
1. Review [CONTRIBUTING.md](CONTRIBUTING.md)
2. Check [project-config.md](project-config.md)
3. Set up your preferred IDE
4. Start with small modifications

### For Contributors
1. Read [CONTRIBUTING.md](CONTRIBUTING.md)
2. Check [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
3. Create a feature branch
4. Follow the PR template

## 🎯 Quick Wins

### Easy Modifications
- Change ball speed in `PlayerMovement.cs`
- Modify score increment in `PlayerCollision.cs`
- Adjust restart delay in `GameManager.cs`
- Change camera follow distance in `FollowPlayer.cs`

### Adding Features
- Create new materials in Materials folder
- Add new prefabs to Prefabs folder
- Create additional levels in Scenes 1
- Modify UI elements for different looks

## 🔍 Debugging Tips

### Unity Console
- Check for error messages
- Use `Debug.Log()` in your scripts
- Monitor performance metrics

### Scene View
- Use Scene view to position objects
- Check object hierarchies
- Verify component attachments

### Inspector
- Modify values in real-time
- Test different settings
- Debug component states

## 📞 Need Help?

### Resources
- [Unity Documentation](https://docs.unity3d.com/)
- [Unity Learn](https://learn.unity.com/)
- [Project Issues](https://github.com/yourusername/roller-ball-game/issues)
- [Community Discussions](https://github.com/yourusername/roller-ball-game/discussions)

### Getting Support
1. Check existing issues first
2. Create a new issue with details
3. Use the issue templates
4. Provide Unity version and platform info

---

**Happy coding! 🎮✨**

*This setup guide gets you running quickly. For detailed information, check the other documentation files.* 