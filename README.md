# Home — Dan Beaulieu

A personal landing page that collects my professional links and core information in a clean, responsive, mobile-first layout.

## Overview

This repository contains a minimal static site (HTML/CSS) used as a central hub for my online presence and professional profiles. The site is intentionally simple — no build steps or runtime dependencies — so it can be hosted on GitHub Pages or any static file host.

## Key Features

- Clean, responsive design
- Dark theme with blue accent colors
- Mobile-first layout
- Accessible semantic HTML where possible
- Quick links to professional profiles and contact info

## Profiles

- LinkedIn: [dano-beaulieu](https://www.linkedin.com/in/dano-beaulieu)
- GitHub: [Dano-SanDog](https://github.com/Dano-SanDog)
- YouTube: [My Channel](https://www.youtube.com/channel/UCLb-486pz570VvL0PlsIgrw)

## About Me

Information Security Engineer | Cybersecurity Generalist

I use this page as a lightweight personal landing page to share links and a brief summary of my work.

## Preview / How to Use

- Open `index.html` in your browser to view the page locally.
- Or serve the directory with a simple static server, for example:

  - Python 3: `python -m http.server 8000`
  - Node (http-server): `npx http-server -p 8000`

Then open http://localhost:8000 in your browser.

## Customization

- Edit `index.html` to update text, links, or visual elements.
- CSS is in `styles.css` (or the stylesheet linked in `index.html`) — adjust colors, spacing, and typography there.
- Replace images or avatars in the repo and update the paths in `index.html`.

## Deployment

This site can be hosted on any static-hosting provider. Common options:

- GitHub Pages
  - Option A (recommended for simple sites): Push to the `main` branch and enable Pages from the repository settings (Root or `/docs` folder).
  - Option B: Create a `gh-pages` branch and push built/static files there, then enable Pages for `gh-pages`.
- Netlify / Vercel: Connect the repo and deploy. Since there is no build step, set the publish directory to the repository root.
- Any static host: Upload the files to your host or use the provider's CLI.

## Accessibility & Best Practices

- Use semantic HTML for screen-reader compatibility.
- Keep contrast high for text on dark backgrounds (WCAG AA recommended minimum contrast ratios).
- Include descriptive alt text for images and avatars.

## Contributing

This repository is my personal site; contributions are not generally expected. If you want to suggest an improvement, open an issue or PR and I will review it.

## License & Copyright

© 2026 Dan Beaulieu

If you'd like a formal license added (MIT, Apache 2.0, etc.), tell me which one and I can add a LICENSE file.
