# Copilot Instructions for sixth-project

## Project Overview
This is a simple static website project using HTML and CSS, with Bootstrap 5.3.7 included via CDN. The project consists of two main files:
- `index.html`: The main HTML file containing the structure and content of the site.
- `style.css`: The custom stylesheet for additional styles.

## Architecture & Structure
- The site uses a single-page layout with a navigation bar, a hero section, and action buttons.
- Bootstrap is used for layout, grid, and component styling. Custom classes (e.g., `.logo-box`, `.hero`, `.arrow-btn`) are used for project-specific styles.
- All scripts and styles are loaded via CDN or local files; there is no build process or JavaScript framework.

## Developer Workflows
- **No build step is required.**
- To view changes, simply open `index.html` in a browser.
- Bootstrap is loaded via CDN; ensure you have an internet connection for full styling and functionality.
- Custom styles should be added to `style.css`.

## Project-Specific Conventions
- Use Bootstrap utility classes for layout and spacing where possible.
- Custom components (e.g., `.logo-box`, `.arrow-btn`) should be styled in `style.css`.
- Keep all HTML in `index.html`; do not split into multiple files unless the project structure changes.
- Use semantic HTML and Bootstrap's grid system for responsive design.

## Integration Points & Dependencies
- **Bootstrap 5.3.7** is included via CDN for both CSS and JS.
- No external JavaScript or backend integration is present.

## Examples
- The navigation bar uses Bootstrap's `navbar`, `navbar-expand-lg`, and utility classes.
- The hero section uses a custom `.hero` class and Bootstrap's grid for layout.
- Action buttons use Bootstrap's `btn`, `btn-light`, and `btn-outline-light` classes.

## Key Files
- `index.html`: Main entry point, contains all HTML structure.
- `style.css`: Place for all custom styles.

## How to Extend
- Add new sections directly to `index.html`.
- Add or modify styles in `style.css`.
- To add interactivity, include JavaScript in a new file and link it in `index.html`.

---

For questions or unclear conventions, review the structure of `index.html` and `style.css` for examples of current patterns.
