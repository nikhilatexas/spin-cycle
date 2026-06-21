# Spin Cycle

A playful chore wheel — add the chores you've been putting off, give it a spin, and let the wheel decide what you do next. Knock it out, mark it done, spin again.

**Live demo:** https://spin-cycle-chores.netlify.app/

![Spin Cycle — a colorful wheel of chores with a spin button](screenshot.png)

## Demo

![Spin Cycle in action — the wheel spins, lands on a chore, and confetti bursts](demo.gif)

> Don't have a GIF yet? Record a 3–5 second spin and save it as `demo.gif` in the repo root.
> On macOS, [Kap](https://getkap.co/) exports straight to GIF; on Windows, [ScreenToGif](https://www.screentogif.com/) does the same. Keep it short and looping for the best effect.

## Why

Deciding which chore to do is half the friction. Spin Cycle turns it into a game: you don't choose, the wheel does. It's a single self-contained HTML file with no build step and no backend.

## Features

- **Spin to pick** — a weighted-random wheel lands on one of your chores
- **Add & remove** chores on the fly, each with its own colored slice
- **Mark it done** — clears the chore off the wheel and bumps your daily counter
- **Sound effects** — a ratcheting tick that slows with the wheel, a ding on landing, and a confetti burst to celebrate
- **Mute toggle** — silence the audio anytime; your preference is remembered
- **Saves automatically** — your list, daily count, and mute setting persist in the browser via `localStorage`
- **Responsive** — works on desktop and mobile, with touch support
- **Accessible** — keyboard-friendly and respects `prefers-reduced-motion`
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript in one file

## Run it locally

No install needed — just open the file in a browser:

```bash
# clone the repo
git clone https://github.com/YOUR-USERNAME/spin-cycle.git
cd spin-cycle

# open it (macOS)
open index.html
# or on Windows
start index.html
# or just double-click index.html in your file explorer
```

## Tech

- HTML, CSS, vanilla JavaScript — no framework, no build tooling
- SVG for the wheel and labels
- `localStorage` for persistence
- Web Audio API for a small "ding" when the wheel stops
- Fonts: Bricolage Grotesque + Inter (Google Fonts)

## Hosting

It's a static site, so it'll run on any static host. This copy is deployed on Netlify by dragging `index.html` onto [Netlify Drop](https://app.netlify.com/drop). It works equally well on GitHub Pages, Cloudflare Pages, or Vercel.

## License

MIT — do whatever you like with it.
