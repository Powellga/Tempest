# Tempest 2025

A faithful HTML5 recreation of the classic 1981 Atari Tempest arcade game.

## About

Tempest 2025 brings the iconic vector arcade shooter to modern web browsers while preserving the authentic look, feel, and challenge of the original. Experience the same glowing neon graphics, pulsing synthesized sounds, and intense tube-crawling action that made Tempest a legend.

Play it here: https://powellga.github.io/Tempest/

## Features

- **Authentic Vector Graphics** — Glowing neon lines rendered on HTML5 Canvas, capturing the distinctive CRT aesthetic
- **All 16 Original Tube Shapes** — Circle, square, plus, bow-tie, and all the geometric variations from the arcade
- **Classic Enemy Types** — Face off against Flippers, Tankers, Spikers, Fuseballs, and Pulsars
- **Synthesized Sound Effects** — Web Audio API-powered sounds faithful to the original
- **Level Select System** — Start from different stages just like the arcade
- **Superzapper** — Your emergency screen-clearing weapon when things get overwhelming
- **High Score Persistence** — Your best scores saved locally between sessions
- **Progressive Difficulty** — Balanced enemy speeds for accessibility while maintaining authentic challenge

## How to Play

### Controls

| Key | Action |
|-----|--------|
| ← / A | Move counter-clockwise |
| → / D | Move clockwise |
| Space / Z | Fire |
| X | Superzapper |

### Objective

Defend your position at the outer edge of the tube. Destroy enemies as they crawl up from the center before they reach you. Clear all enemies to advance to the next level. Survive as long as you can and chase that high score.

### Enemies

- **Flippers** — Basic enemies that flip between lanes
- **Tankers** — Split into Flippers when destroyed
- **Spikers** — Leave deadly spikes along the tube walls
- **Fuseballs** — Travel along the tube edges
- **Pulsars** — Electrify entire tube segments

## Running the Game

Simply open the HTML file in any modern web browser:

```bash
# No build step required — just open directly
open tempest.html
```

Or serve locally:

```bash
python -m http.server 8000
# Then visit http://localhost:8000/tempest.html
```

## Technical Details

- **Single-file implementation** — No dependencies or build process
- **HTML5 Canvas** — Vector graphics rendering
- **Web Audio API** — Synthesized sound generation
- **localStorage** — High score persistence

## Browser Compatibility

Works in all modern browsers with HTML5 Canvas and Web Audio API support:
- Chrome
- Firefox
- Safari
- Edge

## Credits

Original Tempest © 1981 Atari, Inc. Designed by Dave Theurer.

This recreation is a fan project for educational and nostalgic purposes.

## License

MIT License — Feel free to learn from, modify, and share.
