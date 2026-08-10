# 🎆 Firework Gunner (Chromatic Barrage)

A fast, colorful arcade shooter built with plain HTML5 Canvas + JavaScript — no engine, no build step, just one self-contained `index.html`. Match colors, chain combos, and keep the sky from filling up with misses.

**▶️ Play it here:** [g-c-3.github.io/firework-gunner](https://g-c-3.github.io/firework-gunner/)

## How to Play

- Targets fall from the top of the screen — match your firework's **color** to the target's color for **+100 points** (with a chance of a bonus multiplier up to **×10**).
- Hitting the **wrong color** still bursts the target, but costs you **-10 points**.
- Letting a target reach the bottom without hitting it costs you even more.
- Bullets **bounce off the walls** instead of disappearing, so ricochets can still score.
- **Pick a color** from the swatches in the bottom-left corner.
- **Aim** by dragging the dot on the slider near the fire button.
- **Fire** by pressing (or holding, for continuous fire) the FIRE button.
- **Tap the gun** to open the weapon picker — each weapon has a different fire pattern and reload speed.

## Features

- Multiple weapon styles (single shot, spread, shotgun, and more), each with unique reload timing and burst pattern
- Color-matching combo scoring with bonus multipliers
- Bouncing projectile physics
- Touch and mouse/pointer support, built for mobile and desktop
- Zero dependencies — runs entirely client-side in a single HTML file

## Running Locally

No build tools or installation required.

```bash
git clone https://github.com/g-c-3/firework-gunner.git
cd firework-gunner
```

Then just open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Tech Stack

- HTML5 Canvas for rendering
- Vanilla JavaScript (no frameworks or libraries)
- CSS for HUD/UI overlays

## Contributing

Issues and pull requests are welcome. If you spot a bug or have an idea for a new weapon or mode, feel free to open an issue.

## License

Released under the [MIT License](LICENSE).
