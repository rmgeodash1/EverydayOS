# Contributing to EverydayOS

First off, thank you for considering contributing! 🎉 EverydayOS is better with you.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior.

## How Can I Contribute?

### 🐛 Reporting Bugs

**Before submitting a bug report:**
- Check the [issues page](https://github.com/rmgeodash1/EverydayOS/issues) for existing reports
- Make sure you're using the latest version

**When submitting, include:**
- A clear, descriptive title
- Steps to reproduce the issue
- What you expected to happen
- What actually happened
- Your OS and Python version (`python --version`)
- Any error messages or screenshots

### 💡 Suggesting Enhancements

We love new ideas! When suggesting features:

1. **Explain the problem** — What's the pain point you're solving?
2. **Describe the solution** — How would you like it to work?
3. **Consider alternatives** — Any other approaches you've thought about?
4. **Provide examples** — Screenshots, mockups, or references to other tools

### 🔧 Your First Code Contribution

#### Setting Up Development Environment

```bash
# Fork and clone
git clone https://github.com/rmgeodash1/EverydayOS.git
cd EverydayOS

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install with dev dependencies
pip install -e ".[dev]"

# Verify everything works
pytest