# 2026-10-11 — Overnight campaign pass: fresh-clone build verified, README getting-started gap closed, SCIP indexed

Facts established during the overnight completion pass (verified on primo):

- Fresh-clone route works: `npm ci` (752 packages from the tracked
  lockfile) then `npm run build` — `astro check` reports **0 errors,
  0 warnings, 1 hint**, and `astro build` completes (1 page, dist/).
  `git status` stays clean afterwards (dist/ and node_modules are
  already ignored).
- README drift found: the README's quick-start section never documents
  this template's own install/build/preview steps — a fresh user could
  not learn from it how to build the template. A "Getting started
  (this template)" section with the verified commands and the
  customization map (index.mdx, citation files, assets, config) was
  appended. The organization tree in the README also lists a
  `texput.log` that does not exist in the repo (cosmetic; left alone).
- SCIP: `npx @sourcegraph/scip-typescript index` generated
  `index.scip` (21.6 KB) at the repo root; gitignored as a generated
  artifact, not committed.
- `current.md` carried the language-mirror template; refreshed to
  describe the template itself.
