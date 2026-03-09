# 🛸 UFO Cross — 飞碟过关

A browser-based HTML5 arcade game inspired by the classic *Frogger*.
Guide your UFO across deadly lanes of alien spacecraft and asteroids to reach the safety zones at the top!

## ▶ How to Play

Open `index.html` in any modern browser — no build step, no dependencies.

| Control | Action |
|---------|--------|
| `↑ ↓ ← →` / `W A S D` | Move the UFO one step |
| Swipe (mobile) | Move the UFO |
| On-screen D-pad (mobile) | Move the UFO |

## 🎯 Objective

- Reach all **5 goal pads** at the top of the screen to complete the level.
- Avoid colliding with alien fighters, space cruisers, and asteroids.
- Beat the countdown timer before time runs out.
- You have **3 lives** — lose them all and it's game over.

## 🗺 Levels

| Level | Name | Description |
|-------|------|-------------|
| 1 | 初探宇宙 | Slow ships — a gentle introduction |
| 2 | 星际加速 | Speeds increase, more obstacles |
| 3 | 小行星带 | Dense asteroid fields — tight gaps |
| 4 | 超高速穿越 | Fast lanes across almost every row |
| 5 | 终极决战 | Maximum speed, maximum density |

## ✨ Features

- Animated space background with twinkling stars
- Three obstacle types: **Alien Fighter**, **Space Cruiser**, **Asteroid**
- UFO with spinning coloured lights and glow effects
- Particle explosion effects on death and goal capture
- Screen shake on collision
- Score system with high-score saved to `localStorage`
- Time bonus + life bonus on level completion
- Web Audio API sound effects (no external files required)
- Fully responsive — works on desktop and mobile
