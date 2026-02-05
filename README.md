# Rocket Duel

## Introduction
Rocket Duel is a portrait-oriented, physics-driven duel between a human pilot and an AI rival. The goal is not only to win the dogfight, but to destroy your opponent **and then land safely**. Reckless kills do not count: a round is only won when the killer touches down upright on a landing platform.

## Compatibility Notes
- Built as a single HTML file using Canvas 2D; no external libraries are required.
- Designed for mobile-first play in portrait orientation, but keyboard controls work on desktop browsers.
- Run the game by opening `index.html` directly or serving it from any static web server.

## Gameplay Instructions
### Objective
- Destroy the opponent's rocket.
- After the kill, land your rocket upright on a platform to secure the win.

If you crash after getting the kill, the round is a draw.

### Controls
**Keyboard (desktop)**
- **Left/Right Arrow:** rotate the rocket
- **Up Arrow:** thrust
- **Space:** fire (or reset after win/draw)

**Touch (mobile)**
- **Left side drag:** rotate left/right and push upward to thrust
- **Right side tap/hold:** fire

### Landing Rules (must be precise)
- Touch platforms from above only.
- Keep vertical and horizontal speed low.
- Stay nearly upright.

If any landing condition is missed, the rocket explodes.

## Development Guidelines
### Branching Rules
- Features must always be developed in a feature branch.
- Bug fixes must always be developed in a bugfix branch.
- Always PR into main.

### Branch Naming
- Use `feature/<short-description>` for new features.
- Use `bugfix/<short-description>` for fixes.

### Pull Request Checklist
- Summarize what changed and why.
- List tests run (or explain why tests were not run).
- Ensure at least one reviewer approves before merging.

### Commit Messages
- Use clear, action-oriented summaries (for example: `feat: add touch input hints`).

### Definition of Done
- Code reviewed and approved.
- Tests (if applicable) are passing.
- Documentation updated if behavior changes.
