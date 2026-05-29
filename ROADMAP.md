# ROADMAP

## Product Summary

Pachi is a one-page landing page for **Pachi | Tarot Intuitivo & Direção**, designed as a calm, elegant entry point for people arriving from Instagram. The site will present the brand, explain the reading process, showcase the available services, and guide visitors toward WhatsApp with a trust-first tone.

The final experience should feel editorial, ritualistic, mature, mobile-first, and lightweight.

## Chosen Stack

The project will use **plain HTML5 and CSS3**.

This is the right direction because the landing page is static, has no backend, no database, no authentication, and does not need a JavaScript framework. Keeping the site dependency-free makes it faster, easier to deploy, and easier to maintain.

## Core Features

1. **Build the static page structure**
   - Create a semantic `index.html` with all required landing page sections.
   - Include clear replacement comments for WhatsApp, Instagram, logo, submark, personal photo, and CTA messages.

2. **Create the visual system**
   - Create a mobile-first `styles.css` using CSS variables for colors, typography, spacing, borders, and shadows.
   - Use the existing brand assets in `img/TP-Logomarca.jpg` and `img/TP-Submarca.jpg` as the visual reference.
   - Apply the warm off-white background, dark olive text, burned gold accents, subtle ritual symbols, and editorial spacing.

3. **Render the complete landing page**
   - Implement the hero, manifesto, services, process, decision route, rituals, final CTA, ethical note, footer, and floating WhatsApp button.
   - Ensure the page is responsive from mobile screens to desktop layouts.

## Expected File Structure

```text
tarot-pachi/
├── index.html
├── styles.css
├── ROADMAP.md
├── plano-landing-page.md
├── README.md
└── img/
    ├── TP-Logomarca.jpg
    └── TP-Submarca.jpg
```

## Development Sequence

### 1. Create the base HTML document

- Add `index.html`.
- Set the language to Portuguese.
- Add metadata for responsive layout, page title, description, and social sharing basics.
- Link Google Fonts and `styles.css`.
- Add comments for replacing WhatsApp, Instagram, logo, submark, and future personal photo.

### 2. Implement all landing page sections

- Add the hero section with the main promise and primary WhatsApp CTA.
- Add the about/manifesto section with image placeholder.
- Add the services grid with the four official offers.
- Add the process section with four numbered steps.
- Add the post-Bússola decision route section.
- Add the rituals and alchemy section with intention tags.
- Add the final CTA, ethical note, and footer.

### 3. Build the mobile-first visual system

- Add `styles.css`.
- Define `:root` variables for the brand palette, fonts, spacing, radius, and shadows.
- Style the page for mobile first.
- Add desktop breakpoints only where the layout needs more width, such as the about section and services grid.

### 4. Add interaction and accessibility polish

- Add hover, active, and focus-visible states for all links and CTAs.
- Add the fixed WhatsApp button in the lower-right corner.
- Confirm that all images have useful `alt` text.
- Confirm that color contrast is readable and that keyboard navigation remains visible.

### 5. Prepare for GitHub Pages

- Keep all paths relative so the site works from GitHub Pages.
- Confirm that `index.html` is at the repository root.
- Document that GitHub Pages should publish from the repository root or the selected deployment branch.

## Acceptance Criteria

- The project contains `index.html` and `styles.css` at the repository root.
- The site uses only HTML5 and CSS3, with no React, Tailwind, Bootstrap, SPA framework, backend, database, or build step.
- The layout is mobile-first and adapts cleanly to desktop.
- The visual direction matches the existing logo and submark: warm off-white, dark olive, burned gold, subtle ritual geometry, and mature editorial spacing.
- The page includes all planned sections: hero, manifesto, services, process, decision route, rituals, final CTA, ethical note, and footer.
- The services section includes the four specified offers with their names, descriptions, delivery details, prices or price guidance, and CTAs.
- The WhatsApp CTAs use clear replacement comments and include the intended pre-filled message.
- A floating WhatsApp button remains visible while scrolling.
- The page has semantic HTML, readable contrast, visible focus states, useful alt text, and accessible link labels.
- The copy avoids future prediction promises, childish mysticism, aggressive sales language, and cold corporate tone.

## GitHub Pages Note

GitHub Pages can publish this project directly because the site is static and the entry file will be `index.html` at the repository root. After implementation, enable GitHub Pages for the repository and select the branch/root folder that contains `index.html`.
