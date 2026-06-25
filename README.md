# PaulCDilley.github.io

Paul C. Dilley's academic website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll theme (a fork of Minimal Mistakes) and hosted via GitHub Pages.

## Structure

- `_pages/about.md` — the "About Me" page (site homepage)
- `_pages/publications.html` + `_publications/` — the Publications tab and one
  Markdown file per publication (a placeholder example file is included —
  delete it and add your own)
- `_pages/lexical-topography.md`
- `_pages/textual-diffusion-metrics.md`
- `_pages/gospel-of-thomas.md`
- `_pages/coptic-dialects.md`
  — placeholder pages for the four resource tabs; replace the "coming soon"
  text with real content (or whole new HTML/Markdown layouts) as each project
  is ready.
- `_data/navigation.yml` — controls the order/labels of the tabs in the top nav
- `_config.yml` — site title, author bio/sidebar info, social/academic links

## Publishing this site

1. Push the contents of this folder to the root of the
   `PaulCDilley/PaulCDilley.github.io` repository on the `main` (or `master`)
   branch.
2. In the repo, go to **Settings -> Pages** and confirm the source is set to
   deploy from that branch (root). GitHub Pages auto-detects Jekyll and will
   build the site for you -- no local build step is required.
3. Wait a minute or two, then visit https://PaulCDilley.github.io.

## Editing later

- To add a publication, copy `_publications/2025-00-00-example-publication.md`
  to a new file and fill in the front matter and text.
- To fill in one of the four resource tabs, edit the corresponding file in
  `_pages/` directly, or replace it with a full set of static pages/assets for
  that project (keep the same `permalink` so the nav link keeps working).
- To change your profile photo, replace `images/profile.png` with a square
  image of the same name.
