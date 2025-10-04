# Contributing to TransitFlow

Thank you for your interest in contributing to TransitFlow! This document explains how to contribute code, data (routes/stages), documentation, and bug reports.

## Getting started (developer)

1. Fork the repository and clone your fork:

   git clone https://github.com/Marci-design>/transitflow.git

2. Create a branch for your change:

   git checkout -b feature/your-feature-name

3. Install dependencies and run locally (example placeholders — replace with your project's actual commands):

   - Backend (Node.js example):
     - `cd backend`
     - `npm install`
     - `npm run dev`

   - Mobile (React Native example):
     - `cd mobile`
     - `npm install`
     - `npx react-native run-android` or `npx react-native run-ios`

4. Add tests for new features and run the test suite.

## Code style & best practices

- Follow the existing code style. If the project uses linters (ESLint, Prettier), run them before committing.
- Write clear, focused commits. Use conventional commits if the project follows them (e.g., `feat:`, `fix:`, `chore:`).
- Keep pull requests small and focused. Include a clear description of what changed and why.

## Submitting changes

1. Push your branch to your fork:

   git push origin feature/your-feature-name

2. Open a pull request against the project's `main` branch.
3. Describe the purpose of the change, list any breaking changes, and include relevant screenshots or logs.

## Reporting bugs

- Open an issue with a descriptive title and steps to reproduce.
- Include environment information (OS, device, app version) and logs if available.

## Adding or updating route/stage data

- If you have local route or stage data, please add it in the appropriate data folder (e.g., `data/routes/`) following the existing data format.
- Include metadata: city, route name/number, common stops, coordinates, and any notes about variability.
- If possible, include a small sample and verification notes.

## Security

If you discover a security vulnerability, please contact the maintainers privately (support@transitflow.com) instead of opening a public issue.

## Code of conduct

By participating, you agree to follow the project's Code of Conduct. Please be respectful and constructive in reviews and discussions.

---

If you'd like, I can adapt this `CONTRIBUTING.md` to match your actual repository structure and add templates (issue/PR), or wire up checks (CI) — tell me which you'd prefer.