# portfolio-info

A detailed, single-page reference backing up and extending [omkulkarni.me](https://omkulkarni.me): work experience, the full open-source contribution history (filterable by repo, same structure as the portfolio's Open Source Explorer), personal projects, milestones, coding profiles, and system design notes.

Static site, no build step. `index.html` is the entire thing.

## Local preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Static root with `index.html` — works on Vercel, Netlify, GitHub Pages, or any static host with zero configuration.
