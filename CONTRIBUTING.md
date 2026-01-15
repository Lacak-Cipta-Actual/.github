# Contributing to Lacak

Thank you for your interest in contributing to Lacak! This document provides guidelines and information for contributors.

## Getting Started

### Development Environment

1. Fork the repository
2. Clone your fork locally
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Test your changes thoroughly
6. Submit a pull request

### Code Style

Follow the existing code style and conventions in the project. Most projects use automated linting and formatting tools.

## Branching Strategy

- `main` - Always deployable, represents production
- `feature/*` - Feature development
- `release/*` - Release preparation
- `hotfix/*` - Critical fixes for production

## Pull Request Process

### Before Submitting

- Ensure your code follows the project's coding standards
- Add tests for new functionality
- Update documentation as needed
- Run the test suite locally

### PR Title Format

Use conventional commit format:
- `feat(scope): description` - New features
- `fix(scope): description` - Bug fixes
- `docs(scope): description` - Documentation changes
- `style(scope): description` - Code style changes
- `refactor(scope): description` - Refactoring
- `test(scope): description` - Test changes
- `chore(scope): description` - Maintenance tasks

### PR Description

Include:
- Clear description of changes
- Motivation for the change
- Testing performed
- Any breaking changes
- Screenshots if applicable (for UI changes)

## Testing

- Write unit tests for new functionality
- Ensure existing tests pass
- Add integration tests when appropriate
- Test edge cases and error conditions

## Code Review

All contributions require code review. Reviewers will check for:
- Code quality and style
- Test coverage
- Performance implications
- Security considerations
- Documentation completeness

## Security

If you discover a security vulnerability, please do not open a public issue. Contact us privately through https://lacak.io.

## Questions?

If you have questions about contributing, please:
- Check existing issues and discussions
- Review the project documentation
- Contact us through https://lacak.io

Thank you for contributing to Lacak!
