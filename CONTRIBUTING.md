# 🤝 Contributing to Vortex Mod Manager

Thank you for your interest in contributing to the Vortex Mod Manager Offline Setup Assistant! We welcome contributions from the gaming and modding community.

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create** a feature branch
4. **Make** your changes
5. **Test** thoroughly
6. **Submit** a pull request

## 📋 Ways to Contribute

### 🐛 Bug Reports
Found a bug? Help us fix it!

- Check existing issues first
- Use the bug report template
- Include system information
- Provide reproduction steps
- Attach relevant logs/screenshots

### 💡 Feature Requests
Have an idea for improvement?

- Check existing feature requests
- Use the feature request template
- Explain the use case clearly
- Describe expected behavior
- Consider implementation complexity

### 📝 Documentation
Help improve our docs!

- Fix typos and grammar
- Add missing information
- Create new guides
- Improve existing tutorials
- Update outdated content

### 🔧 Code Contributions
Ready to code?

- Follow our coding standards
- Add appropriate tests
- Update documentation
- Keep commits focused
- Write clear commit messages

## 🛠️ Development Setup

### Prerequisites
- Windows 10/11 development environment
- Visual Studio 2022 or Visual Studio Code
- .NET Framework 4.8 or .NET 6+
- Git for version control

### Local Development
```bash
# Clone your fork
git clone https://github.com/your-username/vortexmod.git
cd vortexmod

# Create feature branch
git checkout -b feature/your-feature-name

# Install dependencies (if applicable)
# Setup development environment

# Make your changes
# Test your changes

# Commit and push
git add .
git commit -m "feat: your feature description"
git push origin feature/your-feature-name
```

## 📏 Coding Standards

### General Guidelines
- Use clear, descriptive variable names
- Write self-documenting code
- Add comments for complex logic
- Keep functions small and focused
- Follow SOLID principles

### C# Conventions
```csharp
// Use PascalCase for public members
public class VortexInstaller
{
    // Use camelCase for private fields
    private readonly string installPath;
    
    // Use descriptive method names
    public bool InstallVortexOffline(string targetPath)
    {
        // Clear, readable implementation
    }
}
```

### Documentation
- Use XML documentation comments
- Explain the "why" not just "what"
- Include examples where helpful
- Keep documentation up to date

## 🧪 Testing

### Before Submitting
- [ ] Code compiles without warnings
- [ ] All existing tests pass
- [ ] New functionality has tests
- [ ] Manual testing completed
- [ ] Documentation updated

### Test Types
- **Unit Tests**: Individual component testing
- **Integration Tests**: End-to-end workflows
- **Manual Tests**: UI and user experience
- **Compatibility Tests**: Different Windows versions

## 📝 Commit Guidelines

### Commit Message Format
```
type(scope): description

[optional body]

[optional footer]
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting, missing semicolons, etc.
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```bash
feat(installer): add silent installation mode
fix(config): resolve path detection on Windows 11
docs(readme): update installation instructions
test(integration): add Skyrim mod installation test
```

## 🔍 Code Review Process

### What We Look For
- **Functionality**: Does it work as expected?
- **Code Quality**: Is it well-written and maintainable?
- **Performance**: Any performance implications?
- **Security**: Are there security considerations?
- **Documentation**: Is it properly documented?

### Review Timeline
- Initial review within 48 hours
- Follow-up reviews within 24 hours
- Maintainer approval required for merge

## 🎯 Specific Areas for Contribution

### High Priority
- 🎮 **Game Support**: Add support for new games
- 🔧 **Bug Fixes**: Fix existing issues
- 📖 **Documentation**: Improve guides and tutorials
- 🔒 **Security**: Enhance security features

### Medium Priority
- ⚡ **Performance**: Optimize installation speed
- 🌐 **Localization**: Add language support
- 🎨 **UI/UX**: Improve user interface
- 🧪 **Testing**: Expand test coverage

### Future Enhancements
- 🐧 **Linux Support**: Wine compatibility
- 📱 **Mobile Tools**: Companion apps
- 🤖 **Automation**: CI/CD improvements
- 📊 **Analytics**: Usage statistics

## 🏷️ Issue Labels

### Type Labels
- `bug`: Something isn't working
- `enhancement`: New feature or improvement
- `documentation`: Documentation changes
- `question`: General questions
- `help wanted`: Extra attention needed

### Priority Labels
- `priority: high`: Critical issues
- `priority: medium`: Important improvements
- `priority: low`: Nice to have features

### Status Labels
- `status: reviewing`: Under review
- `status: in-progress`: Being worked on
- `status: blocked`: Waiting for something
- `status: ready`: Ready for implementation

## 🤔 Questions?

### Where to Get Help
- 💬 **GitHub Discussions**: General questions and ideas
- 🐛 **GitHub Issues**: Bug reports and feature requests
- 📧 **Email**: enterprise@vortex-mods.com for business inquiries

### Community Guidelines
- Be respectful and inclusive
- Help others learn and grow
- Share knowledge and experiences
- Follow our Code of Conduct

## 🎉 Recognition

### Contributors
We recognize all contributors in:
- README.md contributors section
- Release notes
- Special mentions in documentation

### Hall of Fame
Outstanding contributors may be invited to:
- Join the core team
- Participate in decision making
- Help shape the project roadmap

---

## 📜 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

---

**Thank you for contributing to Vortex Mod Manager! Together, we're making modding more accessible for everyone.** 🎮✨ 