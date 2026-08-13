# dev1lsconf.github.io

Personal portfolio site for **dev1ls** — Full-stack developer, BSD & Linux user.

## Stack

- **HTML/CSS/JS** — Vanilla, no frameworks
- **Tailwind CSS** — Via CDN (utility-first styling)
- **GitHub Pages** — Static hosting
- **GitHub API** — Dynamic repo fetching

## Features

- **Animated starfield background** — Canvas-based, respects `prefers-color-scheme`
- **Responsive design** — Mobile-first, works on all screen sizes
- **Dark/Light mode** — Automatic via CSS media queries
- **Live GitHub repos grid** — Fetches public repos, shows OpenGraph images, language, stars/forks
- **SEO ready** — OpenGraph, meta tags, semantic HTML
- **Performance** — Lighthouse > 95, minimal JS, lazy-loaded images

## Project Structure

```
├── index.html      # Single-file app (HTML + CSS + JS)
├── twtxt.txt       # twtxt feed
└── README.md       # This file
```

## Development

```bash
# Serve locally
npx serve .
# or
python3 -m http.server 8000
```

## Deployment

Push to `main` branch → GitHub Pages auto-deploys from root.

## Customization

Edit `index.html` to change:
- Avatar, name, bio, links
- Excluded repos list (line ~355)
- Starfield density (line ~395)
- Color palette (CSS `:root` variables)

## License

MIT