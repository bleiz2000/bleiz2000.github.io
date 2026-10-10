# ꗝ || B L E I Z (!) — personal site

Pixel-cyberpunk portfolio: terminal with easter eggs, GitHub repos feed, contacts and an arcade Snake.

**Stack:** single `index.html`, Tailwind (CDN), vanilla JS, no build step.

## Arcade Snake

- Arrows / WASD on desktop, D-Pad on mobile.
- **Demo mode:** until the player touches any control, the snake plays itself —
  a BFS autopilot hunts tokens and avoids self-trapping.
- **Wrap-around walls:** leaving the field puts the head on the opposite side;
  only self-collision ends the game.
- Tokens are tech brands: apple, python, c++, tsmc, intel, amd, linux, microsoft.
- Best score is kept in `localStorage`.

## Run locally

```sh
python3 -m http.server 8000
# http://localhost:8000
```

## Deploy

Hosted on GitHub Pages from the `main` branch:
<https://bleiz2000.github.io>
