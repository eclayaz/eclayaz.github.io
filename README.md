# eclayaz.github.io

Personal site — [eclayaz.github.io](https://eclayaz.github.io/).

Built with [Astro](https://astro.build) + [Tailwind CSS](https://tailwindcss.com). Deployed via GitHub Actions to GitHub Pages on push to `master`.

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # static site to ./dist
npm run preview  # serve the built site locally
```

## Adding a project

Drop a Markdown file into `src/content/projects/`. See `_example.md.template` for the schema.

```yaml
---
title: My project
description: What it does, one or two sentences.
tech: [TypeScript, AWS]
repo: https://github.com/eclayaz/my-project
demo: https://example.com
order: 1
---
```

## Assets you may want to add

- `public/avatar.jpg` — profile photo on the landing page
- `public/cv.pdf` — file behind the "Download CV" button on `/about`

Both have placeholders wired in; the site renders fine without them.
