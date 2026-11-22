# Звёздный рейд / Star Raid Arcade 🚀

A tiny retro space shooter, inspired by late-1980s arcade games. Runs entirely in a browser — no build, server, or dependencies.

## Play

Open the published Netlify site on iPhone, iPad, or desktop and press **Играть**.

- Touch and drag to steer on mobile; arrow keys or WASD on desktop.
- The ship fires automatically.
- Collect **P** for weapon upgrades, **R** for rapid fire, and **+** for an extra life.
- Score record is saved locally in your browser.

## Hosting

This repository is configured for [Netlify](https://www.netlify.com/): every push to `main` can trigger an automatic production deploy once the GitHub repository is linked to the Netlify project.

- **Production site:** https://star-raid-arcade.netlify.app
- **Project:** https://app.netlify.com/projects/star-raid-arcade
- **Branch:** `main`
- **Build command:** none
- **Publish directory:** `.` (repository root; configured in `netlify.toml`)

To test locally, open `index.html` in a browser. No installation required.
