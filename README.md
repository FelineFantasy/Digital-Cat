# Digital Cat Game 🐱 v4.0.0

[![Python Version](https://img.shields.io/badge/python-3.10+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Website](https://img.shields.io/badge/website-online-brightgreen.svg)](https://felinefantasy.github.io/Digital-Cat/)

A virtual pet - cat simulator written in Python. Take care of your cat, play with it, buy treats, and monitor its health!

## 🌐 Website

The game has a website: **[felinefantasy.github.io/Digital-Cat](https://felinefantasy.github.io/Digital-Cat/)**

There you can:
- Download the game
- Visit the GitHub repository
- Check the version and author
- Feel the Windows Vista vibe

Hosted on GitHub Pages, retro-minimalist style.

## 📝 Description

**Digital Cat** is a console game where you adopt a virtual cat and take care of it. The cat has several stats:
- **Satiety** — the cat needs food
- **Happiness** — the cat wants to play
- **Energy** — the cat gets tired
- **Health** — the cat can get sick
- **Coins** — used to buy items
- **Love** — the cat grows attached to you

Random events happen every day — the cat may find coins, use the litter box, or just meow.

**Conditions:**
- 🏆 **Victory**: survive 100 days!
- 💀 **Defeat**: if any stat reaches 0

**Autosave:** the game saves after every action to `save.dat`.

**Logging:** the game writes logs to `log.txt` with levels INFO, DEBUG, WARNING, ERROR. If a player reports a bug, ask them to send this file.

## ⚙️ Installation & Launch

### Option 1: Download executable (easiest)
1. Go to [Releases](https://github.com/FelineFantasy/Digital-Cat/releases/tag/main)
2. Download `Digital-Cat.exe` (Windows) / `Digital-Cat` (Linux/macOS)
3. Run the file

### Option 2: Run from source (requires Python)
```bash
git clone https://github.com/FelineFantasy/Digital-Cat.git
cd Digital-Cat
python Digital-Cat.py
```

## 🎮 Controls

Main menu (options 0-11):
- Feed, pet, play
- Clean litter box, put to sleep
- Shop, outside, work
- Vet, stats, settings

## 🛠️ Settings

- Change cat's name
- Reset game (delete save)
- Change screen clear delay
- About

## 📁 Project Files

```text
Digital-Cat/
├── .github/
│   └── workflows/
│       └── build.yml
├── assets/
│   ├── cat.icns
│   ├── cat.ico
│   └── cat.png
├── .gitignore
├── Digital-Cat.py   # Game
├── LICENSE
├── README.md        # Documentation
├── index.html       # Website
├── style.css        # Website styles
├── save.dat         # Save file (auto-generated)
└── log.txt          # Game log (auto-generated)
```

## 👤 Author
- **FelineFantasy**
- **License**: MIT

---

## 📦 Changelog

### v4.0.0 (16.06.2026)
- removed the bugs that were added
- Improved game stability
- Fixed rare bugs
- Optimized code
- The cat is glad

### v3.0.0 (18.05.2026)
- Added logging system (INFO/DEBUG/WARNING/ERROR)
- Added settings menu
- Added `@log` decorator for automatic function logging
- Added before/after state logging for all actions
- Added screen clear delay setting
- Updated website for v3.0.0
- Extracted constants: `VERSION`, `AUTHOR`, `LICENSE`

### v2.0.0 (01.05.2026)
- Added save/load system (`save.dat`)
- Added veterinary clinic
- Added shop with items

### v1.0.0 (15.04.2026)
- Initial release
- Basic cat stats (satiety, happiness, energy, health)
- Feed, pet, play, clean, sleep actions
- Random events
