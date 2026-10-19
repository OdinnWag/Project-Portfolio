# Odinn Waguespack — Project Portfolio

Personal engineering portfolio hosted with GitHub Pages.

## Website reformat

This update reformats the website with an About landing page, responsive project gallery, project detail pages, Experience, and Resume. It preserves the existing project images, videos, and documents. Legacy page URLs redirect to the reformatted pages.

The site is static HTML, CSS, and JavaScript. Its visual design was developed as a preview; it does not require a Jekyll or Ruby build. The .nojekyll file allows GitHub Pages to serve the static site directly.

## Editing

- Update the About and Experience sections in index.html.
- Project descriptions are stored in originalProjectContent in index.html; gallery entries are in projects.
- Styles are in the style block in index.html.
- Store images and videos under images/ and documents under Documents/.
- The Resume page uses Documents/Resume_Odinn_Waguespack.pdf. Replace that file to update the displayed resume. This publication retains the existing repository PDF; the newer chat attachment has not been incorporated.
- The AquatiClaw poster is rendered inline with PDF.js loaded from jsDelivr. Fonts load from Google Fonts.

GitHub Pages publishes changes from the configured main branch. Check the pages build and deployment workflow after committing.
