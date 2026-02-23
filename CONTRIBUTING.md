# Contributing to Readmigo

Thank you for your interest in contributing to Readmigo! This guide applies to all repositories in the Readmigo organization.

## Getting Started

1. Fork the repository
2. Clone your fork locally
3. Create a feature branch from `main`: `git checkout -b feature/your-feature`
4. Make your changes
5. Push to your fork and submit a Pull Request

## Development Setup

Each repository has its own setup instructions in its README. Common requirements:

| Project Type | Prerequisites |
|-------------|---------------|
| TypeScript (API, Web, Dashboard) | Node.js 20+, pnpm |
| iOS | Xcode 16+, Swift 5.9+ |
| Android | Android Studio, Kotlin 1.9+ |
| Flutter | Flutter 3.x, Dart 3.x |
| C++ (Typesetting) | CMake 3.20+, C++17 compiler |
| Python (NLP) | Python 3.11+, pip |

## Code Style

- Follow the existing code style in each repository
- Use the project's configured linter and formatter
- TypeScript: ESLint + Prettier
- Swift: SwiftLint conventions
- Kotlin: ktlint conventions
- Python: Black + Ruff

## Commit Messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <short description>

[optional body]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `chore`, `ci`

Examples:
- `feat(reader): add page curl animation`
- `fix(auth): handle expired refresh tokens`
- `docs(api): update endpoint documentation`

## Pull Request Process

1. Update documentation if your change affects public APIs or user-facing behavior
2. Add tests for new functionality
3. Ensure all existing tests pass
4. Keep PRs focused — one feature or fix per PR
5. Fill out the PR template completely

## Reporting Issues

- Use the issue templates provided (Bug Report or Feature Request)
- Search existing issues before creating a new one
- Include reproduction steps for bugs
- One issue per report

## Code of Conduct

Be respectful and constructive. We welcome contributors of all experience levels.

## License

By contributing, you agree that your contributions will be licensed under the same license as the project you're contributing to. See each repository's LICENSE file for details.

## Questions?

Open a [Discussion](https://github.com/orgs/readmigo/discussions) for general questions.
