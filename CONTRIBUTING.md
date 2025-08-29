# Contributing to Roller Ball Game 🎮

Thank you for your interest in contributing to Roller Ball! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Types of Contributions We Welcome

- 🐛 **Bug fixes** - Report and fix issues
- ✨ **New features** - Add new gameplay elements
- 🎨 **UI/UX improvements** - Enhance the visual experience
- 📚 **Documentation** - Improve guides and comments
- 🧪 **Testing** - Test and report bugs
- 💡 **Ideas** - Suggest new features or improvements

### Before You Start

1. **Check existing issues** - Your idea might already be discussed
2. **Read the documentation** - Understand the current codebase
3. **Set up your development environment** - Unity 2022.3 LTS or later

## 🚀 Development Setup

### Prerequisites
- Unity 2022.3 LTS or later
- Git
- Basic knowledge of C# and Unity

### Local Development
1. Fork the repository
2. Clone your fork locally
3. Open the project in Unity
4. Create a new branch for your feature

## 📝 Code Style Guidelines

### C# Coding Standards
- Use **PascalCase** for class names and public methods
- Use **camelCase** for private fields and local variables
- Add **XML documentation** for public methods
- Keep methods under 20 lines when possible
- Use meaningful variable names

### Unity-Specific Guidelines
- Follow Unity naming conventions
- Use `[SerializeField]` for inspector-visible private fields
- Implement `MonoBehaviour` methods properly
- Use `Time.deltaTime` for frame-rate independent movement
- Cache component references in `Start()` or `Awake()`

### Example Code Structure
```csharp
using UnityEngine;

/// <summary>
/// Handles player movement and input processing
/// </summary>
public class PlayerMovement : MonoBehaviour
{
    [Header("Movement Settings")]
    [SerializeField] private float moveSpeed = 5f;
    [SerializeField] private float jumpForce = 10f;
    
    private Rigidbody rb;
    private bool isGrounded;
    
    private void Start()
    {
        rb = GetComponent<Rigidbody>();
    }
    
    private void Update()
    {
        HandleInput();
    }
    
    private void HandleInput()
    {
        // Input handling logic
    }
}
```

## 🎯 Feature Development Process

### 1. Planning
- Create an issue describing your feature
- Discuss the approach with maintainers
- Break down the feature into smaller tasks

### 2. Development
- Create a feature branch: `feature/your-feature-name`
- Implement the feature following the coding guidelines
- Add appropriate tests if applicable
- Update documentation

### 3. Testing
- Test your changes thoroughly
- Ensure no regressions in existing functionality
- Test on different Unity versions if possible

### 4. Submission
- Commit your changes with clear messages
- Push to your feature branch
- Create a pull request with detailed description

## 📋 Pull Request Guidelines

### PR Title Format
```
type(scope): brief description
```
Examples:
- `feat(movement): add double jump ability`
- `fix(collision): resolve ball sticking to walls`
- `docs(readme): update installation instructions`

### PR Description Template
```markdown
## Description
Brief description of what this PR accomplishes.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Code refactoring

## Testing
- [ ] Tested in Unity Editor
- [ ] Tested on different platforms
- [ ] No regressions introduced

## Screenshots/Videos
Add screenshots or videos if applicable.

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests added/updated
```

## 🐛 Bug Reports

### Bug Report Template
```markdown
## Bug Description
Clear description of the bug.

## Steps to Reproduce
1. Step 1
2. Step 2
3. Step 3

## Expected Behavior
What should happen.

## Actual Behavior
What actually happens.

## Environment
- Unity Version: [e.g., 2022.3.15f1]
- Platform: [e.g., Windows, macOS, Linux]
- Scene: [e.g., Lvl1, Lvl2]

## Screenshots/Videos
Add visual evidence if possible.

## Additional Context
Any other relevant information.
```

## 🎨 Asset Guidelines

### 3D Models
- Use low-poly models for performance
- Optimize mesh topology
- Include proper UV mapping
- Export in FBX format

### Textures
- Use power-of-2 dimensions (256x256, 512x512, etc.)
- Compress appropriately for target platform
- Include normal maps when beneficial

### Audio
- Use .ogg format for music, .wav for effects
- Keep file sizes reasonable
- Include proper licensing information

## 🔄 Release Process

### Version Numbering
We use [Semantic Versioning](https://semver.org/):
- **MAJOR.MINOR.PATCH**
- Example: 1.2.3

### Release Checklist
- [ ] All tests pass
- [ ] Documentation updated
- [ ] Changelog updated
- [ ] Version numbers updated
- [ ] Assets optimized
- [ ] Build tested

## 📞 Getting Help

### Communication Channels
- **GitHub Issues** - For bugs and feature requests
- **GitHub Discussions** - For questions and ideas
- **Pull Request Reviews** - For code feedback

### Resources
- [Unity Documentation](https://docs.unity3d.com/)
- [Unity Learn](https://learn.unity.com/)
- [C# Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)

## 🙏 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

## 📜 License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to Roller Ball! 🎮✨** 