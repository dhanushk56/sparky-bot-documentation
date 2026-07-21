
---

## 📄 `CONTRIBUTING.md`

# 🤝 Contributing to SparkyBot

Thank you for your interest in contributing to SparkyBot! This document provides guidelines for contributing to the project.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Setting Up Development Environment](#setting-up-development-environment)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)
- [Feature Requests](#feature-requests)

---

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please report unacceptable behavior to the project maintainers.

---

## 🤔 How Can I Contribute?

### 🐛 Reporting Bugs

- Check if the issue already exists in [GitHub Issues](https://github.com/yourusername/sparkybot/issues)
- Use the bug report template when creating a new issue
- Include steps to reproduce, expected behavior, and actual behavior
- Include your Python version, OS, and bot version

### 💡 Suggesting Features

- Check if the feature already exists or is planned
- Use the feature request template
- Explain the problem this feature solves
- Provide examples of how it would work

### 💻 Contributing Code

1. Fork the repository
2. Create a new branch for your feature/fix
3. Write your code following our standards
4. Test your changes thoroughly
5. Submit a pull request

---

## 🛠️ Setting Up Development Environment

### Prerequisites

- Python 3.11 or higher
- Git
- FFmpeg
- Discord Bot Token

### Setup Steps

```bash
# 1. Fork and clone the repository
git clone https://github.com/yourusername/sparkybot.git
cd sparkybot

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt
pip install -r requirements-dev.txt  # Development dependencies

# 4. Copy and configure the config file
cp config.example.py config.py
# Edit config.py with your settings

# 5. Run the bot
python bot.py
