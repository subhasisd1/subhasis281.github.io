# Anuj T Revankar — BIM Engineer Portfolio

A fast, responsive, single-page portfolio built with plain HTML, CSS and
JavaScript (no build step, no dependencies). Designed with a modern
architectural / blueprint theme suitable for interviews.

**Live site:** https://manikanta209.github.io/

## Features
- Modern architectural design with blueprint-grid backdrop
- Light / dark theme toggle (remembers your choice)
- Smooth scroll-reveal animations & animated stat counters
- Scroll-spy navigation + mobile menu
- Fully responsive (desktop / tablet / mobile)
- Downloadable resume PDF
- Accessible & respects `prefers-reduced-motion`

## Structure
```
.
├── index.html                 # markup & content
├── styles.css                 # theme & layout
├── script.js                  # interactions
├── .nojekyll                  # lets GitHub Pages serve /assets as-is
└── assets/
    └── AnujRevankar_Resume.pdf
```

## Run locally
Just open `index.html` in a browser, or serve it:
```bash
npx serve .
# or
python3 -m http.server 8080
```

## Editing content
All text lives in `index.html`. Update contact details in the **Contact**
section and the `mailto:` / `tel:` / LinkedIn links. Replace the resume file in
`assets/` with the same filename to keep the download button working.
