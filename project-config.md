# Project Configuration

This document outlines the configuration settings for the Roller Ball Unity project.

## 🎮 Unity Project Settings

### Version Information
- **Unity Version**: 2022.3 LTS
- **Target Platform**: Standalone (Windows, macOS, Linux)
- **Graphics API**: DirectX 11 (Windows), Metal (macOS), OpenGL (Linux)
- **Scripting Backend**: Mono

### Build Settings

#### Scenes in Build
1. `Assets/Scenes 1/Lvl1.unity` - Main menu and first level
2. `Assets/Scenes 1/lvl2.unity` - Second level

#### Platform Settings
- **Resolution**: 1920x1080 (16:9)
- **Fullscreen Mode**: Windowed by default
- **VSync**: Enabled
- **Anti-aliasing**: 4x MSAA

### Quality Settings
- **Quality Level**: High
- **Texture Quality**: Full Res
- **Anisotropic Textures**: Per Texture
- **Soft Particles**: Enabled
- **Realtime Reflection Probes**: Disabled
- **Billboards Face Camera Position**: Enabled

## 📁 Asset Organization

### Folder Structure
```
Assets/
├── Scripts/           # C# game logic
├── Scenes 1/         # Game levels
├── Materials/         # 3D materials
├── Prefabs/          # Reusable objects
└── Meta files        # Unity metadata
```

### Naming Conventions
- **Scripts**: PascalCase (e.g., `PlayerMovement.cs`)
- **Scenes**: PascalCase with descriptive names (e.g., `Lvl1.unity`)
- **Materials**: lowercase with hyphens (e.g., `box.mat`)
- **Prefabs**: PascalCase with descriptive names (e.g., `Cube.prefab`)

## ⚙️ Script Configuration

### Player Movement Settings
- **Forward Force**: 2000f
- **Sideways Force**: 500f
- **Fall Threshold**: -1f (Y position)

### Game Settings
- **Restart Delay**: 1 second
- **Score Increment**: Per collision (configurable)

### Camera Settings
- **Follow Distance**: Fixed offset
- **Follow Smoothing**: Linear following
- **Target**: Player object

## 🎯 Performance Settings

### Physics
- **Fixed Timestep**: 0.02 (50 FPS)
- **Max Angular Velocity**: 7
- **Solver Iterations**: 6
- **Solver Velocity Iterations**: 1

### Rendering
- **Shadow Distance**: 150
- **Shadow Resolution**: High
- **Shadow Cascades**: 4
- **LOD Bias**: 2

### Audio
- **Sample Rate**: 48000 Hz
- **DSP Buffer Size**: Best Performance
- **Virtual Voices**: 32
- **Real Voices**: 32

## 🔧 Development Tools

### IDE Integration
- **Visual Studio Code**: Enabled
- **Rider**: Enabled
- **Visual Studio**: Disabled

### Version Control
- **Mode**: Visible Meta Files
- **Asset Serialization**: Force Text
- **Version Control Mode**: Perforce (if applicable)

## 📱 Platform-Specific Settings

### Windows
- **Architecture**: x86_64
- **Minimum OS Version**: Windows 7
- **Graphics API**: DirectX 11

### macOS
- **Architecture**: x86_64, ARM64
- **Minimum OS Version**: 10.13
- **Graphics API**: Metal

### Linux
- **Architecture**: x86_64
- **Minimum OS Version**: Ubuntu 18.04
- **Graphics API**: OpenGL 3.2

## 🚀 Build Pipeline

### Pre-build Steps
1. Asset validation
2. Scene optimization
3. Texture compression
4. Script compilation check

### Post-build Steps
1. File size verification
2. Basic functionality test
3. Performance profiling
4. Documentation update

## 🔍 Debug Configuration

### Development Builds
- **Script Debugging**: Enabled
- **Profiler**: Enabled
- **Development Console**: Enabled
- **Crash Reporting**: Disabled

### Release Builds
- **Script Debugging**: Disabled
- **Profiler**: Disabled
- **Development Console**: Disabled
- **Crash Reporting**: Enabled

## 📊 Analytics and Monitoring

### Performance Metrics
- **Frame Rate Target**: 60 FPS
- **Memory Usage**: < 512MB
- **Load Time**: < 10 seconds
- **Build Size**: < 100MB

### Quality Gates
- **No Compiler Errors**: Required
- **No Missing References**: Required
- **Texture Memory**: < 256MB
- **Audio Memory**: < 64MB

---

*This configuration is maintained by the development team and updated with each major release.* 