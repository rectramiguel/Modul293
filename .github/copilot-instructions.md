# Copilot Instructions for Modul 293

## Project Overview

This is an educational module for "Webauftritt erstellen und veröffentlichen" (Module 293) - teaching web development fundamentals including HTML structure, CSS styling, Flexbox, responsive design, and accessibility. Each exercise folder contains learning material and starter code.

## Architecture & Organization

### Directory Structure

- **`Übungen/`** - Main exercise directory with numbered folders (01-09)
  - **`01_HTML-Struktur/`** - HTML5 semantic structure (header, nav, main, footer, etc.)
  - **`02_Textauszeichnung-Listen/`** - Text formatting (strong, em) and list elements
  - **`03_Tabellen/`** - Table markup and semantics
  - **`04_Links/`** - Anchor tags and navigation
  - **`05_Bilder/`** - Image elements and optimization
  - **`08_Flexbox/`** - Flexbox layout with flex_skeleton/, grid_skeleton/, and shop/ subfolders
  - **`09_Responsive/`** - Responsive design principles

### Each Exercise Folder Pattern

- **`README.md`** - Task description (Aufgabenstellung) and learning objectives
- **`index.html`** - Student solution file or starter template
- **CSS files** - Separated (e.g., `shop.css`, `styles.css`, `background_styles.css`)
- **`img/`** - Static assets (images for shops, examples)

## Key Patterns & Conventions

### HTML Structure

- **HTML5 DOCTYPE** required: `<!DOCTYPE html>`
- **lang attribute** on root element (German exercises: `lang="de"`, English examples: `lang="en"`)
- **Metadata essentials**: charset (`UTF-8`), viewport for responsiveness
- **Semantic HTML5 elements**: Use `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` instead of divs

### Styling Approach

- **Separated CSS files**: Multiple stylesheets (structural vs decorative)
  - `background_styles.css` - Background and decorative styles
  - `styles.css` - Layout and component styles
- **External stylesheets only** - No inline styles or `<style>` tags in exercises
- **Flexbox-first layout** - Primary layout method (Exercise 08)

### File Naming & Language

- Exercise folders use German naming (`Textauszeichnung-Listen`, `Bilder`)
- Code comments and task descriptions are in German
- HTML examples may use English (flexbox skeleton references Kyle's YouTube video)

## Development Workflow

### Running Exercises

- No build system needed - exercises are static HTML/CSS
- Open `.html` files directly in browser (VS Code Live Server extension recommended)
- No npm scripts (package.json files are empty placeholders)

### Exercise Progression

1. Read `README.md` for task requirements
2. Create/edit `index.html` with required elements
3. Link external CSS in `<head>`
4. Style using separate CSS files
5. Peer review: "Besprechung" section in README suggests analyzing peer code

## Important Considerations

### Educational Context

- Exercises are **progressive** - later modules build on earlier concepts
- Solutions should follow **semantic HTML** - demonstrates best practices
- Code should be **self-documenting** with minimal comments
- Task descriptions include acceptance criteria in German

### When Assisting with Exercises

- Refer to exercise's `README.md` for exact requirements
- Ensure HTML5 validity and semantic element usage
- Validate responsive design where applicable (Übungen 09)
- Maintain separation between structure (HTML) and presentation (CSS)
- Suggest external resources (e.g., references in flex_skeleton point to Kyle's Flexbox video)

## Cross-Module References

- Flexbox (08) builds on text formatting (02), lists (02), and images (05)
- Responsive (09) requires understanding of layout from Flexbox (08)
- All modules reinforce HTML structure (01) and accessibility principles

## File Examples

- [Flexbox skeleton template](Übungen/08_Flexbox/flex_skeleton/flex.html)
- [Simple e-shop layout](Übungen/08_Flexbox/shop/index.html)
- [Text formatting exercise](Übungen/02_Textauszeichnung-Listen/index.html)
