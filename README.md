# Portfolio Site

Single-file portfolio site built in plain HTML, CSS, and JavaScript.

The page presents a UX designer / builder portfolio inside an IDE-inspired interface, with tabs and sidebar navigation for an About page, case studies, field notes, and contact information.

## What It Includes

- IDE-style window chrome, tab bar, sidebar, and status bar
- Multiple content sections rendered as in-page "files"
- Simple client-side tab switching with vanilla JavaScript
- Responsive layout for desktop and mobile
- Placeholder content blocks for case studies, links, and contact details

## Project Structure

```text
.
├── index.html
└── README.md
```

## Run Locally

No build step or dependencies are required.

Open `index.html` directly in a browser, or serve the folder with any simple static server.

Examples:

```bash
open index.html
```

or

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customization Notes

- Update the copy in `about.md`, case study, notes, and contact sections directly inside `index.html`
- Replace placeholder media blocks with real screenshots, GIFs, or embedded video
- Swap placeholder outbound links on the Field Notes page with real LinkedIn or Medium URLs
- Review any confidential portfolio material before publishing; the current content already notes that some work should be recreated rather than shown directly

## Design Details

- Typography uses Google Fonts: IBM Plex Mono, IBM Plex Sans, and Instrument Serif
- Colors are managed through CSS custom properties in the `:root` block
- Navigation works by toggling `.active` on tabs, sidebar items, and page sections
- Reduced-motion support is included for the blinking cursor treatment

## Current Status

This site is a polished portfolio shell with strong visual direction, but several content areas are still placeholders:

- Case study descriptions and outcomes
- Field note titles and links
- Contact details
- Media assets and captions

## Next Steps

1. Replace placeholder copy with final portfolio content.
2. Add real media assets for each case study.
3. Publish the page with GitHub Pages, Netlify, or another static host.