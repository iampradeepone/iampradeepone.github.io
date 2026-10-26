# Pradeep Kumar | Senior SRE & Creative Dev

> Architecting the unseen. Breathing life into code.

Personal portfolio of **Pradeep Kumar**, a Senior Site Reliability Engineer at Oracle, based in Bengaluru, India. By day I keep cloud and healthcare platforms reliable. By night I sculpt light and sound out of code.

**Live site:** https://iampradeepone.github.io/

---

## What's on the site

| Section | What you'll find |
| --- | --- |
| **01. Intro** | Hero with a live, generative `/dev/radio` player: a synthwave soundtrack made in your browser, with an animated night skyline that reacts to the music. |
| **02. My Story & Craft** | Background, the "one system, two lenses" reliability simulation, the **Journey Logs** career timeline, and My Daily Arsenal (skills). |
| **03. My Work** | An interactive 3D globe of projects, with a case study for each one. On phones and for reduced-motion users it becomes a simple list. |
| **04. Collaborate** | Ways to get in touch and start a conversation. |

## Tech

A single static `index.html`, with no build step and no backend.

- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN) and custom CSS
- **3D and motion:** [Three.js](https://threejs.org/) and [Anime.js](https://animejs.com/)
- **Audio:** the Web Audio API generates the music live, with no audio files
- **Icons and fonts:** [Lucide](https://lucide.dev/), Inter, JetBrains Mono and Oswald

## Run it locally

```bash
git clone https://github.com/iampradeepone/iampradeepone.github.io.git
cd iampradeepone.github.io
open index.html        # or double-click the file
```

An internet connection is needed because the libraries and fonts load from CDNs.

## Deployment

Hosted on **GitHub Pages**. The repo is named `iampradeepone.github.io`, so every push to the default branch is published at the root URL above.

## Accessibility and performance

- Project cards are keyboard-accessible buttons.
- The globe falls back to a plain list on small screens and when `prefers-reduced-motion` is on.
- Audio never plays until you press play.

## Connect

- Portfolio: https://iampradeepone.github.io/
- GitHub: [@iampradeepone](https://github.com/iampradeepone)

---

&copy; Pradeep Kumar. All rights reserved. Please don't copy the content or design without permission.
