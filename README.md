<div align="center">
  <h1>🏠 EverydayOS</h1>
  <p><em>Your intelligent assistant for everyday digital life</em></p>
  
  [![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
  [![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](CONTRIBUTING.md)
  [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
</div>

---

## 🌟 What is EverydayOS?

**EverydayOS** is a growing collection of intelligent, privacy-first tools for your daily digital life. Think of it as an operating system for your everyday tasks — but open source, local-first, and built by the community.

### 🧰 Available Tools

| Tool | Status | Description |
|------|--------|-------------|
| 📁 **Sortify** | ✅ v1.0 | Intelligent file organizer |
| 🔐 **Vault** | 🚧 Planned | Password manager |
| ✅ **Focus** | 🚧 Planned | Smart to-do with AI prioritization |
| 🔄 **Convert** | 🚧 Planned | Universal converter (units, currencies, formats) |
| 🧹 **Clean** | 🚧 Planned | Safe disk cleaner |
| 📝 **Note** | 🚧 Planned | Quick note taker |

---

## 📁 Sortify — File Organizer

### The Problem

We all have that folder. You know the one. **Downloads**. **Desktop**. The digital junk drawer with 847 files from who-knows-when, mixing work documents with vacation photos and random memes.

### The Solution

Sortify watches your folders and keeps them organized — automatically, intelligently, and safely.

### ✨ Key Features

- **🔄 Smart Organization** — Sort files by type, date, or custom rules
- **👁️ Preview Mode** — See what will happen before moving anything (`--dry-run`)
- **↩️ Undo** — Changed your mind? One command reverts everything
- **🎨 Content Detection** — Recognizes files by content, not just extension
- **⚙️ Custom Rules** — Your folders, your rules (YAML configuration)
- **📊 Visual Reports** — See exactly what was organized
- **🛡️ Safe by Default** — No file is ever deleted, only organized

### 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/EverydayOS.git
cd EverydayOS

# Install
pip install -e .

# Organize your Downloads (with preview first!)
everydayos sortify organize ~/Downloads --dry-run

# Looks good? Run it for real
everydayos sortify organize ~/Downloads

# Need to undo?
everydayos sortify undo ~/Downloads