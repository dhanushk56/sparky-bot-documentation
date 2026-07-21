
---

## 📄 `CONTRIBUTING.md`

# 🤝 Contributing to SparkyBot

Thank you for your interest in contributing to SparkyBot! This document provides guidelines for contributing to the project.

---

## 📋 Table of Contents

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Reporting Issues](https://discord.gg/Yw4TQvfBcy)
- [Feature Requests](https://discord.gg/Yw4TQvfBcy)

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

---

## 🛠️ Setting Up Development Environment

### Prerequisites

- Python 3.11 or higher
- Git
- FFmpeg
- Discord Bot Token

### Setup Steps


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

# 5. Run the bot
python bot.py
