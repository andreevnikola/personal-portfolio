# personal-portfolio

Personal portfolio of Nikola Andreev. Single-page static site built with [Astro](https://astro.build).

## Commands

| Command           | Action                                  |
| :---------------- | :-------------------------------------- |
| `npm install`     | Install dependencies                    |
| `npm run dev`     | Start dev server at `localhost:4321`    |
| `npm run build`   | Build production site to `./dist/`      |
| `npm run preview` | Preview the production build locally    |

## Structure

- `src/pages/index.astro` — the single page (hero, about, skills, projects, contact). Edit content in the frontmatter.
- `src/layouts/Layout.astro` — HTML shell, meta tags, global theme (auto light/dark).
- `public/` — static assets (favicon).
