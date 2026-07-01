# Lewis Whitfield Portfolio

Modern personal portfolio website for Lewis Whitfield, focused on Data, AI, Automation, public sector delivery, projects, writing, testimonials, awards and certifications.

The site is built as a lightweight static website for GitHub Pages. It does not use a framework or build pipeline, so the live site is easy to maintain: edit the HTML/CSS/JavaScript files, commit the changes, and GitHub Pages republishes automatically.

## Site Overview

The portfolio is structured around:

- A high-impact hero section for Lewis's current Data, AI and Automation positioning
- About section with concise career highlights
- Project carousel covering current LinkedIn-backed project work
- Articles & Posts carousel linking to LinkedIn posts and external writing
- Testimonials carousel with colleague and customer-facing recommendations
- Honors & Awards carousel
- Certifications carousel
- Direct contact links for email, LinkedIn and GitHub

## Technology

- Static HTML
- CSS with responsive layouts and carousel styling
- Small JavaScript layer for mobile navigation, active section highlighting, scroll reveal effects and carousel controls
- Local image assets for reliable GitHub Pages hosting

## Key Files

- `index.html` - website content and structure
- `styles.css` - responsive visual design
- `script.js` - interactions and carousel controls
- `assets/` - local images and badges

## Local Preview

Open `index.html` in a browser, or serve the folder locally with a simple static server.

Example:

```bash
python -m http.server 8080
```

Then open `http://127.0.0.1:8080/`.

## GitHub Pages

This site is designed to publish from the repository root using GitHub Pages.

Recommended Pages settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`
- Custom domain: `lewiswhitfield.co.uk`

## Updating The Site

Edit the relevant content in `index.html`, adjust styling in `styles.css`, then commit the changed files to `main`. GitHub Pages will redeploy the site automatically.
