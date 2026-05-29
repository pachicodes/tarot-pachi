# AGENTS.md

## 1. Project Overview

This project is a one-page static landing page for **Pachi | Tarot Intuitivo & Direção**.

It delivers a calm, elegant, mobile-first experience for people arriving from Instagram. The page presents the brand, explains the reading process, showcases the available services, includes an ethical note, and guides visitors toward WhatsApp with a trust-first tone.

The final goal is a lightweight, responsive, editorial, ritualistic, and mature landing page that can be published directly with GitHub Pages.

## 2. Stack and Constraints

The stack is:

- Plain HTML5
- Plain CSS3

The project must remain static and dependency-free.

Do not use:

- React
- Vue
- Angular
- Tailwind CSS
- Bootstrap
- Any SPA framework
- Any backend
- Any database
- Authentication
- A build step unless explicitly requested later

The site should run directly in the browser from `index.html`.

## 3. File Structure

Expected final structure:

```text
tarot-pachi/
├── index.html
├── styles.css
├── AGENTS.md
├── ROADMAP.md
├── plano-landing-page.md
├── README.md
└── img/
    ├── TP-Logomarca.jpg
    └── TP-Submarca.jpg
```

## 4. Main Commands

There are no package scripts, build commands, or dependency installation commands for this project.

To run locally, open `index.html` directly in a browser.

If a local static server is desired for previewing relative paths, use any simple static file server outside the project configuration. Do not add tooling unless explicitly requested.

Production build:

- No production build exists.
- No production build is needed.
- The production output is the repository root containing `index.html`, `styles.css`, and the `img/` assets.

## 5. Code Conventions

Use semantic HTML:

- `header`
- `main`
- `section`
- `footer`
- meaningful headings
- descriptive links and buttons
- useful `alt` text for images

Use mobile-first CSS:

- Start with the smallest screen layout.
- Add media queries only when the layout needs more room.
- Use CSS custom properties in `:root` for colors, typography, spacing, radius, and shadows.
- Use `clamp()` for responsive typography.
- Use `grid` and `flexbox` for layout.

Naming conventions:

- Use clear lowercase class names.
- Prefer readable BEM-like names when helpful, such as `service-card`, `section-heading`, and `floating-whatsapp`.
- Keep class names tied to the page structure and brand purpose, not visual accidents.

Organization:

- Keep HTML sections in the same order defined by `ROADMAP.md`.
- Keep CSS grouped by purpose: variables, reset/base, layout utilities, sections, components, responsive rules.
- Add concise comments only where they help future edits, especially for replacing WhatsApp, Instagram, logo, submark, personal photo, and CTA messages.

Fetch handling:

- This project does not fetch external data.
- Do not add fetch logic unless the project scope changes explicitly.

## 6. Deployment Process

GitHub Pages can publish this project directly because it is a static site.

Deployment expectation:

- Entry file: `index.html`
- Output folder: repository root
- Build step: none
- Deploy branch: the branch configured in GitHub Pages, typically `main`
- Publish source: repository root, unless the repository settings specify another source

Keep all asset paths relative so the site works correctly on GitHub Pages.

## 7. What Not To Do

Do not invent new stack choices, frameworks, package managers, bundlers, or build tools.

Do not replace the static HTML/CSS approach with a JavaScript app.

Do not add services, prices, copy, sections, or funnel steps that are not described in `ROADMAP.md` or `plano-landing-page.md`.

Do not change the brand direction away from warm off-white, dark olive, burned gold, subtle ritual geometry, and mature editorial spacing.

Do not make the page visually childish, overly mystical, neon, corporate, or aggressive in sales tone.

Do not make claims about predicting the future or replacing therapeutic, medical, legal, or financial support.

Do not remove the ethical note, floating WhatsApp button, mobile-first behavior, accessibility basics, or clear replacement comments.

Do not assume real WhatsApp or Instagram URLs if they have not been provided. Use clearly marked placeholders instead.
