# 🎯 Tactical Strike

> HTML5 tactical shooter · version-driven development · automated releases

![Status](https://img.shields.io/badge/status-in%20development-fbbf24)
![Version](https://img.shields.io/badge/version-v0.1.0-38bdf8)
![Technology](https://img.shields.io/badge/technology-HTML%20CSS%20JavaScript-0f172a)
![License](https://img.shields.io/badge/license-MIT-34d399)

Tactical Strike is a browser-based tactical shooter inspired by the intensity of competitive shooters. The project is designed to deliver fast, technical, and replayable gameplay while growing through carefully documented versions, new weapons, maps, systems, and game modes.

> ⚠️ This is an independent project inspired by the shooter genre. It does not use assets, trademarks, or code from other games.

## 🎮 Game objective

- Survive increasingly difficult enemy waves.
- Aim accurately and react quickly.
- Build the highest score possible.
- Master movement and positioning.
- Keep improving with every new version.

## 🕹️ How to play

1. Open `version/v0.1.0/index.html` for the current playable build, or use the main entry point when available.
2. Move with `WASD` or the arrow keys.
3. Aim with the mouse.
4. Shoot with the left mouse button or `Space`.
5. Survive enemy waves and earn points.

```bash
cd version/v0.1.0
python3 -m http.server 8000
```

Then visit [`http://localhost:8000`](http://localhost:8000).

## 🚀 Releases and downloads

Download a version from the official GitHub Releases page. Each release includes a ZIP package containing the corresponding playable build.

| Version | Status | Release page | Play from source |
|---|---|---|---|
| **v0.1.0 — First Contact** | Current | [![Download v0.1.0](https://img.shields.io/badge/Download-v0.1.0-38bdf8?style=for-the-badge)](https://github.com/MitNak25/tactical-strike/releases/tag/v0.1.0) | [`version/v0.1.0`](./version/v0.1.0) |
| **Latest release** | Always updated | [![Latest release](https://img.shields.io/badge/See_latest_release-34d399?style=for-the-badge)](https://github.com/MitNak25/tactical-strike/releases/latest) | — |

> If a release link is not available yet, the version can still be played directly from its folder. Release packages are generated when a version tag is published.

[**View all Tactical Strike releases →**](https://github.com/MitNak25/tactical-strike/releases)

## ✨ Current features

- Real-time arcade combat rendered with HTML5 Canvas.
- Direct mouse aiming and responsive shooting.
- Enemies that spawn from the edges and chase the player.
- Progressive waves with increasing difficulty.
- Health, score, particles, and game-over screen.
- Responsive interface for different screen sizes.
- No external dependencies: pure HTML, CSS, and JavaScript.
- Version snapshots and downloadable GitHub Releases.

## 📁 Project structure

```text
Tactical Strike/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       ├── pages.yml              # Automatic GitHub Pages deployment
│       └── release.yml            # Automatic ZIP release for v*.*.* tags
├── assets/
│   └── README.md                  # Guide for future images and audio
├── docs/
│   └── RELEASE_CHECKLIST.md       # Maintainer checklist
├── releases/
│   └── README.md                  # Release and download guide
├── version/
│   ├── README.md                  # Version catalog
│   └── v0.1.0/
│       ├── README.md              # Release notes
│       ├── index.html             # Playable build
│       ├── style.css
│       └── game.js
├── LICENSE
├── README.md
└── .gitignore
```

## 🧭 Roadmap

### v0.1.0 · First Contact ✅

Basic movement, aiming, shooting, enemies, score, health, waves, particles, and the first playable combat loop.

### v0.2.0 · Tactical Pressure 🚧

Improved balancing, a start menu, obstacles, new enemy types, and sound effects.

### v0.3.0 · Arsenal 🚧

Multiple weapons, ammunition, reloading, weapon identities, and unlockable upgrades.

### v0.4.0 · The Operation 🔭

Cover-based maps, round objectives, extraction zones, and mission-focused gameplay.

### v1.0.0 · Tactical Strike Stable 🔭

A polished experience with local saves, statistics, accessibility improvements, and additional game modes.

## 📦 Versioning

This project uses [Semantic Versioning](https://semver.org/):

- `v0.1.0` — first playable build
- `v0.2.0` — gameplay improvements
- `v0.3.0` — new weapons and systems
- `v1.0.0` — stable public release

Every historical version is stored in `version/` with its own release notes and snapshot. Published versions should not be modified; new changes belong in a new version folder.

To publish a new release:

```bash
git add .
git commit -m "feat: prepare Tactical Strike v0.2.0"
git tag v0.2.0
git push origin main --tags
```

The `release.yml` workflow detects the tag, creates a ZIP package, and publishes a downloadable GitHub Release automatically.

## 🧑‍💻 Development

No Node.js installation or build process is required. Edit the files and refresh the browser. For the most reliable local experience, use a static server:

```bash
python3 -m http.server 8000
```

The current game is intentionally built with native browser technologies to keep the project lightweight, accessible, and easy to extend.

## 🤝 Contributing

Issues, ideas, and improvements are welcome:

1. Open an issue describing the proposal or problem.
2. Include reproduction steps for bug reports.
3. Keep changes focused and easy to review.
4. Test the game in an up-to-date browser.
5. Document changes that affect controls, balance, or gameplay.

## 📜 License

Tactical Strike is released under the **MIT License**. See [`LICENSE`](LICENSE) for the complete terms.

<p align="center">
  <strong>Aim. React. Survive.</strong><br>
  <sub>Tactical Strike — every round counts.</sub>
</p>
