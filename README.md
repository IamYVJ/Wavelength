# Wavelength

**Play now → [iamyvj.github.io/Wavelength](https://iamyvj.github.io/Wavelength/)**

A browser-based take on the party game *Wavelength* — read your teammates' minds across a spectrum. Single static HTML page, no build step, no dependencies.

## How to play

1. Pick a points-to-win target (7 / 10 / 15) and hit **Start Game**.
2. Each round one player is the **Psychic**:
   - Tap **Peek at Target** to reveal a hidden zone on the dial (only the Psychic should look).
   - Hide it again, then give a **one-word clue** that points the team toward that zone along the spectrum (e.g. *Hot ↔ Cold*).
3. The team tap-drags or nudges the needle to where they think the target sits.
4. **Lock In** to score:
   - **Bullseye** → 4 pts
   - **Close** → 3 pts
   - **Decent** → 2 pts
   - **Miss** → 0 pts
5. Teams alternate. First to the goal wins.

## Features

- 40 built-in spectrum cards, shuffled without immediate repeats
- Touch + mouse dial control, plus fine-nudge buttons (±5° / ±15°)
- Mobile-friendly responsive layout
- Pure HTML/CSS/JS in a single file — drop on any static host

## Run locally

```bash
git clone https://github.com/IamYVJ/Wavelength.git
cd Wavelength
python -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` directly.

## Deploy

Hosted via **GitHub Pages** from the repo root on `main`. Any push updates the live site.

## License

MIT — see [LICENSE](LICENSE).
