# Marwan Hassan — Portfolio 🎬

A single-file animated portfolio where the hero cartoon plays like a short looping video.

## What's animated

- **Blinking eyes** with pupil drift and eyebrow raises
- **Typing hands** in a two-tap key-press cycle with arm sway
- **Breathing torso** and gentle head bobbing
- **Light sweep** gliding across the laptop screen
- **Swaying plant leaves** (5 leaves, staggered phases)
- **Rising mug steam** and **drifting code symbols** (`</>`, `{ }`, `=>`, `( )`)
- **Pointer + scroll parallax** — the character and the giant "MARWAN" ghost text move at different depths
- Soft ambient light gradient behind the scene

Everything respects `prefers-reduced-motion` (animations disable automatically).

## Run locally

Open `portfolio.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Tech

Plain HTML + CSS + JavaScript — no frameworks, no build step. Fonts via Google Fonts.
