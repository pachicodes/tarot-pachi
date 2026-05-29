# DEV_PLAN

## Phase 1: Base Static Shell

**Status:** TODO

**Goal:** Create the minimum static page shell that opens directly in the browser and links the stylesheet correctly.

**Deliverables:**

- Create `index.html`
- Create `styles.css`
- Link `styles.css` from `index.html`
- Add base metadata for language, charset, viewport, title, description, and social sharing
- Link the selected web fonts
- Add comments for replacing WhatsApp, Instagram, logo, submark, personal photo, and CTA messages

**Manual Acceptance Criteria:**

- Opening `index.html` in a browser displays a valid page without console errors.
- The browser tab shows the Pachi page title.
- The page uses Portuguese language metadata.
- The stylesheet loads successfully.
- The page contains visible placeholder structure for the landing page.
- The source includes clear replacement comments for all future real links and assets.

## Phase 2: Landing Page Content

**Status:** TODO

**Goal:** Add all required landing page sections in semantic HTML, following the order and copy defined by the roadmap and planning document.

**Deliverables:**

- Update `index.html`
- Add the hero section
- Add the about/manifesto section with a photo placeholder
- Add the services section with four service cards
- Add the process section with four numbered steps
- Add the post-Bússola decision route section
- Add the rituals and alchemy section with intention tags
- Add the final CTA section
- Add the ethical note
- Add the footer

**Manual Acceptance Criteria:**

- The browser displays all planned sections in the correct order.
- The hero includes the main headline, subtitle, support text, and primary WhatsApp CTA.
- The services section includes the four planned offers: Bússola Intuitiva, Bússola Profissional, Norte da Semana, and Rituais & Alquimia.
- Each service card includes its planned description, delivery details, pricing or price guidance, and CTA.
- The ethical note is present and visible.
- The copy does not promise future prediction or replace therapeutic, medical, legal, or financial support.

## Phase 3: Brand Visual System

**Status:** TODO

**Goal:** Apply the mobile-first visual direction using the existing logo and submark as the brand reference.

**Deliverables:**

- Update `styles.css`
- Define `:root` variables for colors, fonts, spacing, border radius, and shadows
- Style base typography with serif headings and clean body text
- Apply the warm off-white background, dark olive text, and burned gold accents
- Add mobile-first spacing, section rhythm, cards, buttons, tags, and subtle dividers
- Use `img/TP-Logomarca.jpg` and `img/TP-Submarca.jpg` in appropriate places

**Manual Acceptance Criteria:**

- The page visually matches the existing logo and submark palette.
- The design feels mature, editorial, ritualistic, and minimal rather than childish or overly mystical.
- The logo and submark appear at restrained sizes and do not dominate the mobile layout.
- Cards have subtle borders, rounded corners, and soft shadows.
- CTAs are visually clear without feeling aggressive.
- Typography scales gracefully on small screens.

## Phase 4: Responsive Layout

**Status:** TODO

**Goal:** Ensure the page is designed mobile-first and adapts cleanly to tablet and desktop widths.

**Deliverables:**

- Update `styles.css`
- Add responsive breakpoints only where needed
- Stack all content cleanly on mobile
- Convert the about section to two columns on wider screens
- Convert the services section from one column on mobile to a multi-column grid on wider screens
- Keep the process section readable across screen sizes

**Manual Acceptance Criteria:**

- On a narrow mobile viewport, the page is readable without horizontal scrolling.
- On mobile, sections stack naturally and CTAs are easy to tap.
- On desktop, the about section uses two columns.
- On desktop, the services section displays as a multi-column grid.
- Spacing remains balanced from mobile to desktop.
- Images and placeholders do not stretch or distort.

## Phase 5: Interaction and Accessibility Polish

**Status:** TODO

**Goal:** Add the required interaction states, floating WhatsApp button, and accessibility basics.

**Deliverables:**

- Update `index.html`
- Update `styles.css`
- Add a fixed floating WhatsApp button in the lower-right corner
- Add hover, active, and focus-visible states for all links and CTAs
- Add descriptive `alt` text for logo, submark, and image placeholders
- Add accessible labels where needed
- Confirm readable contrast for text, buttons, and links

**Manual Acceptance Criteria:**

- The floating WhatsApp button remains visible while scrolling.
- All CTAs and footer links have visible hover, active, and keyboard focus states.
- Keyboard navigation can reach all interactive links.
- Focus styles are clearly visible.
- Images have useful alternative text.
- Text remains readable against the background colors.

## Phase 6: GitHub Pages Readiness

**Status:** TODO

**Goal:** Prepare the finished static site for direct publication through GitHub Pages without a build step.

**Deliverables:**

- Verify `index.html` is at the repository root
- Verify `styles.css` is at the repository root
- Verify image paths point to the existing `img/` folder using relative paths
- Update `README.md` with local preview and GitHub Pages deployment notes if needed
- Leave the project dependency-free with no package manager or build configuration

**Manual Acceptance Criteria:**

- The site works when opening `index.html` directly in a browser.
- All images load through relative paths.
- No build command is required.
- No package install command is required.
- The repository root contains the production-ready site files.
- GitHub Pages can be configured to publish from the repository root on the selected branch, typically `main`.
