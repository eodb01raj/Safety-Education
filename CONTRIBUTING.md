# Contributing to Fire Safety Training App

Thank you for your interest in contributing to the Fire Safety Training App! This document provides guidelines for contributing to this educational project.

## 🚨 Important Notice

**This project is for educational purposes only.** All contributions must maintain this educational focus and include appropriate disclaimers about consulting official regulations and certified professionals.

## 📋 Code of Conduct

- Be respectful and inclusive
- Focus on educational value
- Ensure accuracy of fire safety information
- Include proper disclaimers for regulatory content
- Test changes across different browsers

## 🛠️ Development Setup

1. Fork the repository
2. Clone your fork locally
3. Open `index.html` in a modern web browser
4. Make your changes
5. Test thoroughly

## 📝 Contribution Guidelines

### Types of Contributions Welcome

1. **Content Improvements**
   - Additional fire safety training topics
   - Completion of fire exit rules (sections i-nn)
   - Enhanced explanations and key points
   - Improved SVG illustrations

2. **Technical Enhancements**
   - Bug fixes
   - Performance improvements
   - Accessibility improvements
   - Mobile responsiveness enhancements
   - Cross-browser compatibility fixes

3. **Documentation**
   - README improvements
   - Code comments
   - User guides
   - API documentation

### Content Standards

- **Accuracy**: Ensure all fire safety information is accurate and up-to-date
- **Educational Focus**: Content should be educational, not prescriptive
- **Disclaimers**: Include appropriate disclaimers about consulting official sources
- **Clarity**: Use clear, simple language appropriate for training purposes
- **Visual**: Include relevant SVG illustrations where helpful

### Technical Standards

- **HTML5**: Use semantic HTML5 elements
- **CSS3**: Modern CSS with mobile-first responsive design
- **JavaScript**: Vanilla JavaScript (no frameworks)
- **SVG**: Scalable vector graphics for all illustrations
- **Accessibility**: Follow WCAG guidelines
- **Browser Support**: Test in Chrome, Firefox, Safari, Edge

## 🔄 Pull Request Process

1. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make Changes**
   - Follow existing code style
   - Add appropriate comments
   - Test thoroughly

3. **Commit Changes**
   ```bash
   git commit -m "Add: Brief description of changes"
   ```

4. **Push to Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create Pull Request**
   - Provide clear description of changes
   - Reference any related issues
   - Include screenshots for UI changes
   - Ensure all checks pass

### Pull Request Checklist

- [ ] Code follows existing style and structure
- [ ] Changes tested in multiple browsers
- [ ] Documentation updated if needed
- [ ] Educational disclaimers included where appropriate
- [ ] SVG graphics are accessible and scalable
- [ ] No breaking changes to existing functionality
- [ ] Commit messages are clear and descriptive

## 🐛 Bug Reports

When reporting bugs, please include:

- **Browser and version**
- **Operating system**
- **Steps to reproduce**
- **Expected behavior**
- **Actual behavior**
- **Screenshots if applicable**

## 💡 Feature Requests

For feature requests, please provide:

- **Clear description** of the proposed feature
- **Educational value** and how it helps users learn
- **Use cases** and examples
- **Implementation suggestions** if you have them

## 📚 Adding Fire Exit Rules

To add missing fire exit rules (sections i-nn):

1. **Follow the existing pattern** in the HTML structure
2. **Create a new section** with appropriate ID
3. **Include content text** with the regulation details
4. **Add key features** with editable functionality
5. **Create SVG illustration** that visualizes the concept
6. **Update the sections array** in JavaScript
7. **Test navigation** and search functionality

### Example Structure
```html
<div class="section" id="rule-name">
    <h1>Rule Title</h1>
    <div class="content-text">
        Regulation text here...
    </div>
    <div class="key-features">
        <h3>Key Requirements:</h3>
        <ul>
            <!-- Editable key points -->
        </ul>
    </div>
    <div class="svg-container">
        <!-- SVG illustration -->
    </div>
</div>
```

## 🎨 SVG Guidelines

- Use **semantic elements** and proper structure
- Include **accessibility attributes** (titles, descriptions)
- Keep **file sizes reasonable**
- Use **consistent color scheme** (fire safety colors)
- Ensure **scalability** at different sizes
- Add **meaningful labels** and annotations

## 📖 Documentation Standards

- Use **clear, concise language**
- Include **code examples** where helpful
- Add **screenshots** for UI features
- Maintain **consistent formatting**
- Update **version information** appropriately

## ⚖️ Legal Considerations

- All contributions must be **original work** or properly attributed
- Include **educational disclaimers** for regulatory content
- Ensure **compliance** with open source license
- **No liability** for accuracy of fire safety information
- **Educational use only** - not for compliance purposes

## 🤝 Community

- Be **respectful** and **constructive** in discussions
- Help **newcomers** get started
- Share **knowledge** and **best practices**
- Focus on **educational value** and **user safety**

## 📞 Questions?

If you have questions about contributing:

- Open an issue for discussion
- Check existing documentation
- Review the code structure and comments
- Look at recent pull requests for examples

---

**Remember: This is an educational project. All contributions should maintain focus on learning and include appropriate disclaimers about consulting official regulations and certified professionals.**