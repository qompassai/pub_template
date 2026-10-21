# Current Work

pub_template — Qompass AI's Astro template for academic publication
pages (paper landing pages with figures, LaTeX, PDFs, 3D splats, and
image comparisons; React + Svelte islands, Tailwind).

## Status

- Fresh-clone build verified 2026-10-11: `npm ci` +
  `npm run build` green — astro check 0 errors / 0 warnings, build
  produces dist/ with the demo page.
- README now documents the template's own getting-started route and
  customization points (it previously did not).
- `index.scip` is a generated, gitignored artifact at the repo root
  (regen: `npx @sourcegraph/scip-typescript index`).

## Standing rules

- Dual license: LICENSE-AGPL + LICENSE-QCDA stay as they are.
- Code changes are pushed only under Owner's explicit direction
  (the 2026-10-11 overnight campaign authorization covered this pass).
