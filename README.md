# immersionlab.github.io

Homepage of **ImmersionLab** @ Illinois — Department of Aerospace Engineering,
University of Illinois Urbana-Champaign.

> We immerse computation, dynamics, geometry, and architected structures into fluid flows.

Built with [Astro](https://astro.build) and deployed to GitHub Pages from `main`
via [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## Local development

```bash
npm install
npm run dev      # dev server at http://localhost:4321
npm run build    # static build into dist/
npm run preview  # preview the production build
```

## Where content lives

| What | File |
| --- | --- |
| Team members | `src/data/team.ts` |
| News items | `src/data/news.ts` |
| Publications | `src/data/publications.bib` → `src/data/publications.ts` |
| Logo mark | `src/components/Logo.astro` |
| Favicons | `public/favicon.svg` (primary), `public/favicon.ico`, `public/apple-touch-icon.png` |
| Styles | `public/css/style.css` |

Publications are generated from BibTeX with `node scripts/bibtex-to-publications.mjs`.
