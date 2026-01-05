# Contributing to Skill Slots Game

Thank you for your interest in contributing to the Skill Slots Game project! We welcome contributions from the community and appreciate your efforts to help improve this project.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Testing Guidelines](#testing-guidelines)
- [Documentation](#documentation)
- [Reporting Issues](#reporting-issues)
- [Community Standards](#community-standards)

## Code of Conduct

We are committed to providing a welcoming and inclusive environment for all contributors. Please adhere to the following principles:

- **Be Respectful**: Treat all community members with respect and kindness.
- **Be Inclusive**: Welcome diverse perspectives and experiences.
- **Be Professional**: Maintain a professional tone in all communications.
- **Be Collaborative**: Work together constructively to solve problems.
- **Zero Tolerance**: We have zero tolerance for harassment, discrimination, or abusive behavior.

Any violations of this code of conduct should be reported to the project maintainers immediately.

## Getting Started

1. **Fork the Repository**: Click the "Fork" button on the repository page to create your own copy.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
   ```bash
   git clone https://github.com/YOUR-USERNAME/skill-slots-game.git
   cd skill-slots-game
   ```
3. **Add Upstream Remote**: Add the original repository as an upstream remote.
   ```bash
   git remote add upstream https://github.com/lickfooloo-a11y/skill-slots-game.git
   ```

## Development Setup

1. **Install Dependencies**: Follow the project's README for installation instructions.
2. **Create a Feature Branch**: Create a new branch for your work.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Set Up Your Environment**: Ensure your development environment is properly configured.
4. **Run Tests**: Verify that existing tests pass before making changes.

## How to Contribute

### Types of Contributions

We welcome the following types of contributions:

- **Bug Fixes**: Fix identified issues in the codebase.
- **Features**: Add new functionality to the project.
- **Documentation**: Improve or expand project documentation.
- **Tests**: Add or improve unit and integration tests.
- **Performance Improvements**: Optimize code performance.
- **Accessibility Enhancements**: Improve accessibility features (a11y).

### Before You Start

1. **Check Existing Issues**: Review open issues and pull requests to avoid duplicating work.
2. **Create an Issue**: For significant changes, open an issue to discuss your proposed changes.
3. **Get Feedback**: Wait for feedback from maintainers before starting major work.

## Pull Request Process

1. **Keep Your Branch Updated**: Sync with the upstream repository before submitting your PR.
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Push Your Changes**: Push your branch to your forked repository.
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request**: Open a PR against the main repository with a clear title and description.

4. **PR Description Should Include**:
   - A clear description of the changes made
   - Reference to any related issues (e.g., "Closes #123")
   - Screenshots or demos (if applicable)
   - Any breaking changes or migration steps

5. **Address Feedback**: Be responsive to review comments and make requested changes.

6. **Sign Off**: Ensure all commits are properly signed (if required by the project).

7. **Merge**: Once approved, a maintainer will merge your PR.

## Coding Standards

### General Guidelines

- **Language**: Follow the language conventions of the project (JavaScript, HTML, CSS, etc.)
- **Formatting**: Use consistent indentation (typically 2 or 4 spaces)
- **Line Length**: Keep lines reasonably short (aim for 80-120 characters)
- **Naming**: Use clear, descriptive names for variables, functions, and classes

### JavaScript Standards

- Use `const` by default, `let` if reassignment is needed, avoid `var`
- Use arrow functions where appropriate
- Follow ES6+ conventions
- Add JSDoc comments for public functions and classes
- Use meaningful variable names (avoid single letters except for loop counters)

### CSS Standards

- Use semantic class naming (BEM methodology is preferred)
- Group related properties together
- Use meaningful comments for complex styles
- Avoid inline styles

### HTML Standards

- Use semantic HTML5 elements
- Ensure proper accessibility (ARIA labels, alt text for images)
- Maintain valid HTML structure
- Use meaningful class and ID names

## Commit Message Guidelines

Follow these guidelines when writing commit messages:

- **Use Imperative Mood**: "Add feature" not "Added feature"
- **Start with a Type**: Use conventional commits format
  - `feat:` for features
  - `fix:` for bug fixes
  - `docs:` for documentation
  - `style:` for formatting
  - `refactor:` for code refactoring
  - `test:` for test additions
  - `chore:` for build/dependency updates
  - `a11y:` for accessibility improvements

- **Example**: `feat: add user authentication module`
- **Keep It Concise**: First line should be 50 characters or less
- **Provide Context**: Add a blank line followed by more details if needed
- **Reference Issues**: Mention related issue numbers (e.g., "Fixes #123")

## Testing Guidelines

### Test Coverage

- Aim for meaningful test coverage (typically 70%+)
- Write tests for new features before or alongside implementation
- Update tests when modifying existing functionality

### Test Types

- **Unit Tests**: Test individual functions and components
- **Integration Tests**: Test interactions between components
- **E2E Tests**: Test user workflows end-to-end (if applicable)

### Running Tests

Ensure all tests pass locally before submitting a PR:
```bash
npm test
```

## Documentation

- Update README.md if your changes affect usage
- Add comments to complex logic
- Update or create documentation files for new features
- Use clear, concise language
- Include examples when helpful
- Update the table of contents in documentation as needed

## Reporting Issues

When reporting bugs or requesting features:

1. **Check for Duplicates**: Search existing issues first
2. **Use Clear Titles**: Be specific about the problem
3. **Provide Details**:
   - Steps to reproduce (for bugs)
   - Expected vs. actual behavior
   - Environment information (OS, browser, etc.)
   - Screenshots or error logs (if applicable)
4. **Be Constructive**: Provide helpful context and suggestions

## Community Standards

### Expectations

- **Respect Diversity**: We value contributors from all backgrounds
- **Listen Actively**: Consider different perspectives and viewpoints
- **Be Humble**: Be open to learning and feedback
- **Give Credit**: Acknowledge contributions and ideas from others
- **Stay On Topic**: Keep discussions relevant to the project

### Communication

- Use clear, respectful language
- Assume good intent in others' communications
- Ask clarifying questions rather than making assumptions
- Avoid personal attacks or inflammatory language

### Contribution Recognition

We recognize and appreciate all contributions to the project. Contributors may be added to:
- The project README
- The CONTRIBUTORS file
- Project release notes (for significant contributions)

## Questions?

If you have questions about contributing:

1. Check the project's README and existing documentation
2. Search existing issues for similar questions
3. Open a new issue with your question
4. Contact the project maintainers directly if appropriate

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project.

---

**Thank you for contributing to Skill Slots Game! Your efforts help make this project better for everyone.** 🎮✨
