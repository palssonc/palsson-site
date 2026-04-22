# Craig Palsson Static Site

This project is a plain static rebuild of the original Gatsby and Netlify-based site so it can be hosted directly on GitHub Pages.

## Structure

- `index.html` is the homepage
- `research/index.html` is the research page
- `me/index.html` is the personal page
- `styles.css` contains the shared design system
- `site.js` provides mobile navigation and active-link behavior
- `assets/` contains the preserved images and CV PDF

## Editing

The site is intentionally simple to maintain:

- edit page content directly in the HTML files
- replace or add files in `assets/` as needed
- keep links folder-based so GitHub Pages serves clean URLs

## Deploying to GitHub Pages

Host the repository root with GitHub Pages. Because the site is pure static HTML, CSS, JS, and assets, no build step is required.
