# Contributing to xPlugins

Thank you for your interest in contributing to xPlugins! 🎉  
We welcome bug fixes, improvements, and new ideas from the community.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Report Bugs](#how-to-report-bugs)
- [How to Request Features](#how-to-request-features)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Code Style Guidelines](#code-style-guidelines)
- [Getting Help](#getting-help)

---

## 📜 Code of Conduct

By contributing, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before participating.

---

## 🚀 Getting Started

1. **Fork** the repository you want to contribute to
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/PLUGIN_NAME.git
   ```
3. **Create a new branch** for your changes:
   ```bash
   git checkout -b fix/your-fix-name
   # or
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes**, test them on a local server
5. **Commit** with a clear message (see commit conventions below)
6. **Push** and open a Pull Request

---

## 🐛 How to Report Bugs

Use the **Bug Report** issue template and fill in all required fields:
- Plugin name and version
- Minecraft and server version
- Steps to reproduce
- Error logs

---

## ✨ How to Request Features

Use the **Feature Request** issue template and describe:
- The feature you'd like
- The problem it solves
- Any alternatives you've considered

---

## 🔀 Submitting a Pull Request

- Make sure your PR targets the `main` (or `dev`) branch
- Reference any related issue: `Closes #123`
- Keep PRs focused — one fix or feature per PR
- Update `CHANGELOG.md` if your change affects behavior
- All PRs must pass review by **jn_willfrydev** before merging

---

## 🎨 Code Style Guidelines

- Follow standard **Java conventions** for Minecraft plugins
- Use **4 spaces** for indentation (no tabs)
- Name variables and methods clearly and in **camelCase**
- Add comments for non-obvious logic
- Keep methods short and focused on a single responsibility
- Do not commit unused imports or debug print statements

### Commit Message Convention

```
type: short description

Examples:
fix: resolve NPE when player logs out during jump pad
feat: add configurable jump height per pad
docs: update README with new commands
refactor: simplify database connection handling
```

Types: `fix`, `feat`, `docs`, `refactor`, `perf`, `chore`, `test`

---

## 💬 Getting Help

- Join our [Discord server](https://discord.com/invite/mNdxNVx6cU) and ask in the developer channel
- Check existing issues and PRs before opening a new one
- Tag `jn_willfrydev` if you need direct feedback

---

We appreciate every contribution, big or small. Thank you! 🧡
