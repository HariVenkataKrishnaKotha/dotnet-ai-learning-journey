# Contributing to .NET + AI + Azure Architect Roadmap

First off, thank you for considering contributing to this project! 🎉

It's people like you that make this roadmap a great resource for the community. We welcome contributions from everyone, whether you're fixing a typo, adding a resource, or proposing a major change.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [Style Guide](#style-guide)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Pull Request Process](#pull-request-process)

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all. Please be respectful and constructive in your interactions.

### Our Standards

**Positive behavior includes:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

**Unacceptable behavior includes:**
- Harassment, trolling, or discriminatory comments
- Publishing others' private information
- Spam or promotional content
- Any conduct which could reasonably be considered inappropriate

## 🤝 How Can I Contribute?

### 🐛 Reporting Bugs or Issues

If you find any errors, broken links, or outdated information:

1. Check if the issue already exists in [Issues](../../issues)
2. If not, create a new issue with:
   - **Clear title**: Describe the issue concisely
   - **Description**: Provide detailed information
   - **Location**: Specify where the issue is (phase, module, line)
   - **Expected vs Actual**: What should be vs what is
   - **Screenshots**: If applicable

**Example Issue Title:**
```
Broken link in Phase 3, Module 3.2, Azure AI Services section
```

### 💡 Suggesting Enhancements

Have ideas for new content or improvements?

1. Check [existing issues](../../issues) to avoid duplicates
2. Create a new issue with the `enhancement` label
3. Clearly describe:
   - The enhancement or feature
   - Why it would be valuable
   - How it fits into the roadmap
   - Any relevant examples or resources

**Example Enhancement:**
```
Add section on Blazor WebAssembly integration with Azure OpenAI
- Would help full-stack developers
- Growing demand for Blazor skills
- Could include sample project
```

### 📝 Adding Content

Want to contribute new sections, resources, or projects?

**Great additions include:**
- New learning resources (books, courses, articles)
- Additional practice projects
- Industry-specific examples
- Tools and utilities
- Best practices and tips
- Updated information on technologies
- Alternative learning paths
- Career advice and interview preparation

### 🌍 Translations

We welcome translations to make this roadmap accessible globally!

1. Create a new directory: `translations/[language-code]/`
2. Translate `LEARNING_ROADMAP.md` and `README.md`
3. Maintain original structure and formatting
4. Update links to point to translated versions where applicable
5. Add your translation to the main README

### 🎨 Design Improvements

Help improve the visual presentation:
- Better formatting and markdown structure
- Diagrams and visual aids
- Icons and badges
- README design improvements
- Project templates and boilerplates

## 🚀 Getting Started

### For First-Time Contributors

1. **Fork the repository**
   - Click the "Fork" button at the top right

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
   cd REPO_NAME
   ```

3. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes**
   - Edit files using your preferred text editor
   - Follow the style guide below

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of changes"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill out the PR template

### For Returning Contributors

If you've contributed before:

1. **Sync your fork**
   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. **Create a new branch** and follow the process above

## 📐 Contribution Guidelines

### ✅ What We Accept

#### High Priority
- **Corrections**: Typos, grammatical errors, broken links
- **Updates**: Outdated information, deprecated technologies
- **Resources**: High-quality learning materials
- **Projects**: Practical, well-documented project ideas
- **Best Practices**: Industry-standard approaches

#### Medium Priority
- **Enhancements**: Improved explanations and clarifications
- **Alternative Paths**: Different approaches to learning topics
- **Tools**: Useful development tools and utilities
- **Tips**: Study tips and learning strategies

#### Lower Priority (but still welcome!)
- **Formatting**: Improved markdown formatting
- **Organization**: Better structure suggestions
- **Examples**: Code snippets and examples

### ❌ What We Don't Accept

- Promotional content or advertisements
- Paid resources without free alternatives
- Pirated content or copyright violations
- AI-generated content without human review
- Low-effort or spam submissions
- Duplicate content already in the roadmap
- Controversial or non-technical discussions

### 📋 Content Standards

All contributions should:

1. **Be Accurate**
   - Verify information before submitting
   - Include sources and references
   - Test code examples and links

2. **Be Clear**
   - Use simple, understandable language
   - Explain technical terms
   - Provide context and examples

3. **Be Relevant**
   - Fit within the roadmap's scope
   - Target the appropriate skill level
   - Align with modern best practices

4. **Be Accessible**
   - Consider beginners' perspective
   - Avoid unnecessary jargon
   - Include learning resources

5. **Be Well-Formatted**
   - Follow markdown conventions
   - Use consistent styling
   - Include proper headings and lists

## 🎨 Style Guide

### Markdown Formatting

#### Headings
```markdown
# H1 - Main Title (used once per document)
## H2 - Major Sections
### H3 - Subsections
#### H4 - Minor Subsections
```

#### Lists
```markdown
- Use `-` for unordered lists
- Keep items consistent
  - Use proper indentation for nested items

1. Use numbers for ordered lists
2. Lists should be logical
3. Each item should be clear
```

#### Checkboxes
```markdown
- [ ] Uncompleted task
- [x] Completed task
```

#### Links
```markdown
[Link Text](URL)
[Microsoft Documentation](https://docs.microsoft.com)
```

#### Code
```markdown
Inline code: `variable` or `function()`

Code blocks:
\`\`\`csharp
public class Example {
    // Your code here
}
\`\`\`
```

#### Emphasis
```markdown
*Italic text*
**Bold text**
***Bold and italic***
```

### Content Style

#### Learning Resources
```markdown
**Resources:**
- [Resource Name](URL) - Brief description
- [Another Resource](URL) - What makes it useful
```

#### Projects
```markdown
**Practice:**
- [ ] Project name with clear description
- [ ] Another project explaining the learning goal
```

#### Hands-on Activities
```markdown
**Hands-on:**
- [ ] Specific task to complete
- [ ] Expected outcome or deliverable
```

### Language and Tone

- **Use active voice**: "Create a function" not "A function should be created"
- **Be encouraging**: "You'll learn" not "Students will be taught"
- **Be specific**: "Build a REST API with authentication" not "Make an API"
- **Be inclusive**: Use "they/them" or "you" instead of "he/she"

## 📝 Commit Message Guidelines

### Format
```
Type: Brief description (50 chars or less)

Detailed explanation if necessary (wrap at 72 chars).
Include motivation for change and contrast with previous behavior.

Resolves: #123
See also: #456, #789
```

### Types
- **Add**: New content, resources, or features
- **Update**: Changes to existing content
- **Fix**: Corrections and bug fixes
- **Remove**: Deprecated or incorrect content
- **Docs**: Documentation only changes
- **Style**: Formatting, whitespace, etc.
- **Refactor**: Reorganization without content changes

### Examples

**Good commit messages:**
```
Add: Azure OpenAI fine-tuning section to Phase 4

Update: Entity Framework Core version to EF Core 8

Fix: Broken link to Microsoft Learn in Phase 2

Remove: Outdated LUIS references, replaced with CLU
```

**Bad commit messages:**
```
update stuff
fixed things
added content
changes
```

## 🔄 Pull Request Process

### Before Submitting

1. **Review your changes**
   - Read through all modifications
   - Check for typos and errors
   - Test all links

2. **Update related files**
   - If adding major content, update README
   - If changing structure, update navigation
   - Update CHANGELOG.md with your changes

3. **Test locally**
   - Preview markdown rendering
   - Verify all checkboxes work
   - Ensure formatting is correct

### PR Title Format

Use the same format as commit messages:
```
Type: Brief description
```

**Examples:**
```
Add: Computer Vision advanced techniques section
Update: Azure pricing information for 2025
Fix: Typos in Phase 3 certification preparation
```

### PR Description Template

```markdown
## Description
Brief explanation of what this PR does and why.

## Type of Change
- [ ] Bug fix (typo, broken link, error)
- [ ] New content (section, resource, project)
- [ ] Update (existing content improvement)
- [ ] Documentation (README, CONTRIBUTING, etc.)

## Changes Made
- Specific change 1
- Specific change 2
- Specific change 3

## Checklist
- [ ] I have read the CONTRIBUTING guidelines
- [ ] My changes follow the style guide
- [ ] I have tested all links
- [ ] I have updated related documentation
- [ ] My commit messages are clear and descriptive

## Screenshots (if applicable)
Add screenshots showing before/after, if relevant.

## Additional Context
Any other information that reviewers should know.
```

### Review Process

1. **Automated Checks**: PRs will be checked for basic formatting
2. **Maintainer Review**: A maintainer will review your contribution
3. **Community Feedback**: Other contributors may provide input
4. **Revisions**: Make requested changes if needed
5. **Approval**: Once approved, PR will be merged
6. **Recognition**: You'll be added to contributors list!

### After Your PR is Merged

- 🎉 Celebrate! You're now a contributor!
- ⭐ Star the repo if you haven't already
- 📢 Share your contribution on social media
- 👀 Watch the repo for future discussions
- 🤝 Help review other PRs

## 🏆 Recognition

### Contributors Hall of Fame

All contributors are recognized in:
- README.md contributors section
- Special mentions for significant contributions
- Quarterly contributor highlights

### Contribution Badges

Based on your contributions, you may earn:
- 🥉 Bronze: 1-5 contributions
- 🥈 Silver: 6-15 contributions  
- 🥇 Gold: 16+ contributions
- 💎 Diamond: Exceptional contributions or ongoing maintenance

## 💬 Communication

### Where to Ask Questions

1. **General Questions**: [GitHub Discussions](../../discussions)
2. **Contribution Help**: Comment on relevant issue or PR
3. **Private Matters**: Email maintainers directly
4. **Quick Questions**: Ask in PR/Issue comments

### Response Time

- **Issues**: We aim to respond within 48 hours
- **PRs**: Initial review within 3-5 days
- **Discussions**: Community-driven, varying response times

### Getting Help

Stuck on something? Don't hesitate to ask!
- Comment on your PR with specific questions
- Tag maintainers with `@username`
- Join community discussions
- Provide context about what you tried

## 📚 Resources for Contributors

### Learning Git & GitHub
- [GitHub Guides](https://guides.github.com/)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Skills](https://skills.github.com/)

### Markdown Resources
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Markdown](https://guides.github.com/features/mastering-markdown/)

### Open Source Contribution
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [First Contributions](https://github.com/firstcontributions/first-contributions)

## 🙏 Thank You!

Every contribution, no matter how small, makes a difference. Thank you for helping make this roadmap better for everyone!

---

**Questions?** Open an issue or start a discussion. We're here to help!

**Ready to contribute?** Check out our [good first issues](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)!
