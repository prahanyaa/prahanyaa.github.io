# Prahanya Sriram — Portfolio

A minimal, responsive portfolio prepared for https://prahanyaa.github.io.
Plain HTML and CSS; no installation or build dependencies.

## Preview
Open index.html in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a public repository named `prahanyaa.github.io` under your GitHub account. If it already exists, review its contents before replacing anything.
2. Upload the contents of this folder into the repository root on the `main` branch. Do not upload a parent `portfolio` folder.
3. Ensure `.github/workflows/pages.yml` is included. Browser uploads may skip hidden folders; create this file manually using GitHub's Add file → Create new file if needed.
4. Open Settings → Pages → Build and deployment → Source → GitHub Actions.
5. Open Actions, select Deploy portfolio to GitHub Pages, and run the workflow on `main` (or push a new commit).
6. Once the workflow succeeds, visit https://prahanyaa.github.io.

Git upload alternative, after creating an empty repository:
```bash
git init -b main
git add .
git commit -m "Add professional portfolio"
git remote add origin https://github.com/prahanyaa/prahanyaa.github.io.git
git push -u origin main
```
Use these commands only in this extracted folder and only with a new empty repository.

## Customize
- `index.html`: introduction, work examples, projects, education, and skills.
- `assets/style.css`: colors, spacing, typography, and responsive layout.
- `resume.html`: experience overview, not a replacement for your full résumé.
- `.github/workflows/pages.yml`: automatic deployment.

Your full résumé PDF, email, LinkedIn URL, and complete employment history were not supplied for this version. Add them when ready; no invented contact details or broken download links are included. To add a résumé download, place a reviewed PDF at `assets/Prahanya_Sriram_Resume.pdf`, add its link in the navigation, and retain the assets-copy step in the workflow.

EventFlow and CloudForge are labeled Planned. Their listed capabilities are proposals, not completed accomplishments. Add repository/demo links and measured results only after implementation.

Work summaries are high-level and include no employer code or internal architecture diagrams. Review all public text before publishing.
