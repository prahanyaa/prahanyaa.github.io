# Prahanya Sriram — Portfolio

Responsive static portfolio for GitHub Pages. No build step required.

## Update the existing website
1. Unzip `Prahanya_Interactive_Portfolio.zip`.
2. Open https://github.com/prahanyaa/prahanyaa.github.io.
3. Choose **Add file → Upload files**.
4. Drag `index.html`, `resume.html`, `README.md`, and the whole `assets` folder from the extracted folder. Upload the files themselves, not the outer folder or ZIP.
5. Commit to `main`. The existing Pages workflow copies the assets automatically, including the new `app.js`.
6. Wait for the Actions deployment to finish, then refresh https://prahanyaa.github.io with Cmd + Shift + R.

The included `.github/workflows/pages.yml` is unchanged; an existing deployment workflow does not need to be replaced.

## Features
- Interactive backend/cloud/reliability illustration
- Expandable production work highlights and proposed project scopes
- Filterable toolkit
- Persistent light/dark theme
- Rotating role text, section navigation, scroll progress and reveal effects
- Responsive mobile layout, keyboard access, reduced-motion support
- Résumé overview with print styling

## Content
EventFlow and CloudForge are planned, not completed. No project results or repositories are invented. Employer highlights use existing professional experience. The illustration is conceptual, not an employer architecture diagram.

The résumé page is an overview, not a downloadable full CV. Add a reviewed résumé PDF, portrait, LinkedIn URL and email only when supplied. The contact section currently links to GitHub; it has no nonfunctional form.

## Preview
Open index.html or run `python3 -m http.server 8000` in this directory.

## Files
- index.html: portfolio content
- resume.html: résumé overview
- assets/style.css: design and responsive layouts
- assets/app.js: interactions

Google Fonts is optional; the browser uses local sans-serif fallbacks if unavailable. Theme storage failure is handled gracefully. Content remains readable without JavaScript.
