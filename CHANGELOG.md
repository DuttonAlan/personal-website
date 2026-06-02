# Changelog

All notable changes to this project will be documented in this file.

## [0.3.0] - 2026-06-02

### Added
- Blog page with post listing and individual post routes (`/blog`, `/blog/[slug]`)
- Blog content collection with Markdown support (`src/content/blog/`)
- First blog post: "Hello World" (`src/content/blog/hello-world.md`)
- Extended global styles for blog layout

## [0.2.0] - 2026-05-26

### Added
- Privacy policy page (`/privacy`)
- Imprint page (`/imprint`)
- Footer navigation links to privacy and imprint pages

### Fixed
- Replaced email placeholder with real email address on homepage

## [0.1.0] - 2026-05-26

### Added
- Initial personal website setup with Astro
- GitHub Pages deploy workflow (`.github/workflows/deploy.yml`)
- CNAME for custom domain `alandutton.de`
- Site URL configured in `astro.config.mjs`
- README and LICENSE
