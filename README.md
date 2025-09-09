## About this repository
This repository hosts a presentable, data-driven resume built with Jekyll. Content is maintained in a single YAML file and rendered into a clean, responsive web page suitable for both web viewing and printing as a PDF.

## What it supports
- Data‑driven resume sections (profile, contact, experience, projects, skills, education, etc.) controlled from `_data/data.yml`.
- Responsive layout for mobile and desktop, with a print‑optimized view for PDF export.
- A simple toolbar for printing to PDF and toggling dark mode.
- Easy hosting on GitHub Pages.

## How to make use of it
1. Update `_data/data.yml` with your information. Toggle any section by setting `display: true/false`.
2. Place a profile image (optional) under `assets/images/` and reference it via `basic.avatar.path` in the YAML.
3. Adjust site‑wide settings in `_config.yml` (e.g., title, language, theme color).
4. Commit and push changes; the site will rebuild automatically on GitHub Pages if enabled.

## Getting started
### Use on GitHub Pages
1. Fork or copy this repository to your account.
2. Enable Pages for the repository (Settings → Pages) and select the `main` branch.
3. Visit your site once it builds.

### Run locally (optional)
If you prefer local preview, serve this as a standard Jekyll site with your usual Ruby/Jekyll setup.

## Helpful references
- Resume link: https://Devanshirajput501.github.io/resume/
- YAML Checking: https://www.yamllint.com/
- Font: Arial — Color Palette: Ivory and Charcoal (#ECE9E1 and #3D3D3D) — https://designshack.net/articles/graphics/resume-color-schemes/
- QR code generator: https://express.adobe.com/tools/qr-code-generator

## License
MIT (see `LICENSE`).
