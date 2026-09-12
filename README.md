# Nordic Astro Portfolio

A clean, minimal personal website starter built with Astro.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL Astro prints in your terminal.

## Customize

- Edit your name, introduction, research, education, work, and extracurricular content in:
  - `src/pages/index.astro`
- Edit project cards in:
  - `src/pages/projects.astro`
- Edit contact details in:
  - `src/pages/contact.astro`
- Replace:
  - `public/profile.jpg` to update your photo (display crop is controlled in `src/styles/global.css`)
  - `public/cv.pdf` to update your downloadable CV
- Update the navigation name in `src/components/Header.astro`
- Update footer text in `src/components/Footer.astro`

## Build

```bash
npm run build
```

The production site will be generated in `dist/`.
