# Alex Gabel · Academic Website

## Project Overview
- Personal academic homepage highlighting research, publications, and projects.
- Built with the Hugo Blox Academic CV template (Hugo v0.152.1, Tailwind CSS v4) and deployed via GitHub Pages.

## Live Site & Preview
- Production: https://alexgabel.github.io
- Optional: add a landing-page screenshot under `.github/preview.webp` and reference it here if desired.

## Features & Highlights
- Biography, CV download, publications, projects, experience timeline, blog posts, and talks.
- BibTeX-driven publication import, automatic dark/light mode, custom navbar logo, privacy-friendly defaults.

## Local Development
- Requirements: Hugo Extended ≥ v0.152.1, Node.js ≥ 18, pnpm (or npm) for Tailwind utilities.
- Setup:
  ```bash
  git clone https://github.com/alexgabel/alexgabel.github.io.git
  cd alexgabel.github.io
  pnpm install
  pnpm dev      # runs `hugo server --disableFastRender`
  ```
- Regenerate assets by removing `resources/_gen/` when logos or SCSS change. Import publications with `hugoblox import publications --bibtex publications.bib --author admin`.

## Deployment Workflow
- Continuous deployment via GitHub Actions (`.github/workflows/deploy.yml`) on pushes to `main`.
- Manual `hugoblox-import` workflow ingests `publications.bib`, commits generated content, and triggers the deploy pipeline.
- For local publishing, run `pnpm build` (or `hugo --minify`) and serve the `public/` folder.

## Content Structure
- `content/` – Markdown bundles for homepage blocks, publications, projects, blog posts, courses, and events.
- `assets/media/` – Logos, icons, and publication/project imagery.
- `config/_default/` – Site-wide settings (menus, localization, appearance, parameters).
- `data/publications.bib` (or repository root) – Source BibTeX file for publication imports.

## Customization Notes
- Update navigation labels and footer text in `config/_default/menus.yaml` and `config/_default/params.yaml`.
- Adjust color theme and typography via Hugo parameters or Tailwind overrides in `assets/scss/custom.scss`.
- Ignore `.bib` files during Hugo builds by ensuring `ignoreFiles` includes `\.bib$` in `config/_default/hugo.yaml`.

## Acknowledgments & Licensing
- Theme and tooling by Hugo Blox Builder (MIT License © George Cushen and contributors).
- Site content © Alex Gabel (consider noting Creative Commons terms if applicable).
- Publication metadata sourced from the BibTeX file maintained in this repository.

## Contact / Maintainer
- Maintained by Alex Gabel — reach out via https://alexgabel.github.io/#contact or open an issue/pull request.
