# Spin Cycle

A playful chore wheel — add the chores you've been putting off, give it a spin, and let the wheel decide what you do next. Knock it out, mark it done, spin again.

**Live demo:** https://spin-cycle-chores.netlify.app/

<img width="1436" height="773" alt="Screenshot 2026-06-21 at 5 24 18 PM" src="https://github.com/user-attachments/assets/a0f9d313-f478-4953-958e-67e0c1c9eb5b" />


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
