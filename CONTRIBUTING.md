# Contributing to iFarouqCSS

First off, thank you for considering contributing to iFarouqCSS! 🎉

## How Can I Contribute?

### Reporting Bugs 🐛

Before creating bug reports, please check existing issues. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples**
- **Describe the behavior you observed and what you expected**
- **Include screenshots if possible**
- **Specify your browser and OS**

### Suggesting Enhancements ✨

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **List examples of how it would be used**

### Pull Requests 🔧

1. **Fork the repository** and create your branch from `main`:
   ```bash
   git checkout -b feature/amazing-feature
   ```

2. **Make your changes**:
   - Follow the existing code style
   - Add comments for complex logic
   - Update documentation if needed

3. **Test your changes**:
   - Ensure CSS compiles without errors
   - Test in multiple browsers
   - Check responsive behavior

4. **Commit your changes**:
   ```bash
   git commit -m "Add amazing feature"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/amazing-feature
   ```

6. **Open a Pull Request**

### Coding Standards

#### CSS/SCSS Guidelines

- Use **2 spaces** for indentation
- Use **kebab-case** for class names
- Keep selectors **simple and specific**
- Add **comments** for complex styles
- Follow **BEM methodology** where applicable
- Ensure **cross-browser compatibility**

#### File Organization

```
scss/iFarouqCSS/
├── _components.scss     # UI components
├── _maps.scss           # Gradient & Color mapping with all shades
├── _mixins.scss         # Grouping Reusable CSS Declations (Utilities)
├── _utilities.scss      # Utility classes
├── _variables.scss      # SCSS variables
└── iFarouqCSS.scss      # SCSS Compilation
```

#### Naming Conventions

- **Components**: `.btn`, `.card`, `.navbar`
- **Utilities**: `.p-4`, `.m-2`, `.flex`
- **Colors**: `.bg-primary`, `.text-success`
- **Gradients**: `.bg-gradient-sunset`

### Commit Message Guidelines

Use clear and meaningful commit messages:

- **feat**: New feature
- **fix**: Bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting)
- **refactor**: Code refactoring
- **test**: Adding tests
- **chore**: Maintenance tasks

Examples:
```
feat: add dark mode support
fix: button hover state in Safari
docs: update installation guide
style: format spacing utilities
```

### Testing Checklist

Before submitting your PR, ensure:

- [ ] CSS compiles without errors
- [ ] No console warnings
- [ ] Tested in Chrome, Firefox, Safari
- [ ] Tested on mobile devices
- [ ] Documentation updated
- [ ] CHANGELOG.md updated
- [ ] No breaking changes (or clearly documented)

### Development Setup

```bash
# Clone your fork
git clone https://github.com/your-username/ifarouqcss.git

# Navigate to directory
cd ifarouqcss

# Create a branch
git checkout -b feature/my-feature

# Make your changes...

# Build (if applicable)
npm run build
```

### Questions?

Feel free to ask questions by:
- Opening an issue with the `question` label
- Reaching out via email: your.email@example.com

## Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all.

### Our Standards

- **Be respectful** and considerate
- **Be collaborative** and helpful
- **Be patient** with beginners
- **Accept constructive criticism** gracefully
- **Focus on what's best** for the community

### Unacceptable Behavior

- Harassment or discriminatory language
- Personal attacks or trolling
- Public or private harassment
- Publishing others' private information

## Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

Thank you for making iFarouqCSS better! 🚀
