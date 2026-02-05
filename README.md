# DGL233 – Project 1: Custom WordPress Block Theme

## Project Overview
This project is a custom WordPress **block theme** built for DGL233. The goal was to plan, design, and build a personal portfolio website using modern WordPress block theme practices, including hand-coded templates, template parts, and a manually written `theme.json` file.

The website demonstrates a clear separation between **structure (templates)** and **content (pages)**, and uses the WordPress Site Editor and Style Book for global styling.

---

## Live Site
🔗 https://dgl233.abd.aawad.imgd.ca/project-1

## GitHub Repository
🔗 https://github.com/Abdalrhman210505/dgl233-project-1

---

## Theme Features

### Block Theme Structure
- Fully custom **block theme** created from scratch
- Hand-coded theme files:
  - `theme.json`
  - `templates/front-page.html`
  - `templates/404.html`
  - `parts/header.html`
  - `parts/footer.html`
- Header and Footer implemented as **template parts**
- Homepage template includes **Post Content** block only (content lives in the page, not the template)

---

### Global Styles (`theme.json`)
All styling is defined globally using a manually written `theme.json` file.

**Color Palette**
- Background: `#ffffff`
- Primary Text: `#000000`
- Chestnut: `#954535` (primary headings, buttons)
- Fuchsia Blue: `#7a5dc7` (secondary accents, links)
- Dark UI: `#524046` (header and footer background)

**Typography**
- Body text: clean system sans-serif font (normal weight for readability)
- Headings: handwriting-style font for personality and hierarchy
- Headings are bolder than body text to establish clear visual structure

**Components Styled Globally**
- Buttons (background, text color, padding, border radius)
- Navigation (dark background, white text, accent hover color)
- Footer styling
- Headings (H1–H3)
- Paragraph spacing and line height
- Separators

All styles are applied through the **Style Book / theme.json**, with minimal per-block overrides.

---

### Homepage Content
The homepage content is built directly in **Pages → Home** and includes:

1. Hero section with introduction and call-to-action
2. About section
3. Skills section using columns
4. Projects & Experience section
   - Includes a concrete tools list for credibility
5. Call-to-action section
6. Contact section with a working contact form

---

### Navigation & Anchors
- Header navigation uses **anchor links** for smooth scrolling:
  - `#about`
  - `#skills`
  - `#projects`
  - `#contact`
- Anchors are applied to section Group blocks
- Buttons link to the Contact section using anchor navigation

---

### Contact Form
- Contact form implemented using **WPForms Lite**
- Fields included:
  - Name
  - Email
  - Message
- Form is placed directly on the Home page (not in a template)
- Form submission tested and working

---

### Responsiveness
- Layout tested on desktop, tablet, and mobile views
- Section spacing adjusted using Group padding
- Header navigation collapses into a mobile menu for smaller screens

---

### Development & Workflow
- WordPress installed and configured via cPanel
- Development mode enabled during build and disabled before submission
- Regular Git commits with descriptive commit messages
- Theme built locally and synced with the live site
- Site backed up using a remote backup plugin

---

## Bonus / Extra Work
- Manually authored `theme.json` with detailed global styles
- Custom color system aligned with a visual mood board
- Handwriting-style heading typography for brand personality
- Clean, modern header an
