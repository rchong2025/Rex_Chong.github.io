# Engineering Portfolio Website

A responsive, single-page portfolio for an electrical engineering student, built with plain HTML and CSS plus a tiny JavaScript snippet for the mobile navigation menu.

## Files

- `index.html` — page content, project case studies, navigation, and contact links
- `style.css` — visual design and responsive layout
- `assets/README.md` — notes for adding your resume and project media

## Before publishing

1. In `index.html`, replace:
   - `your.email@example.com`
   - `YOUR-USERNAME`
   - `YOUR-LINKEDIN`
2. Add your resume PDF as `assets/resume.pdf`, or change/remove the Resume link.
3. Review every project description and make sure it accurately reflects your own contribution.
4. Add real photos, screenshots, schematics, and measured test results. The current project visuals are CSS illustrations, not photographs of your actual builds.
5. Confirm the target-board configuration and repository links for the Tron game before publishing.
6. Check that you are comfortable making all source code and public project information visible online. Do not include passwords, private keys, personal phone numbers, or confidential course/company material.

## Preview locally

Open `index.html` in a modern browser. The page uses Google Fonts if online; fallback fonts are included.

## Publish with GitHub Pages

1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload `index.html`, `style.css`, and the `assets` folder to the root of the repository.
3. In the repository, open **Settings → Pages**.
4. Under the build/deployment section, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. Wait for the Pages deployment to finish. Visit `https://YOUR-USERNAME.github.io`.
7. After each update, commit and push your changes; GitHub Pages will redeploy the site.

For official instructions, see https://docs.github.com/en/pages/quickstart

## Customization tips

- Edit text and links in `index.html`.
- Change colors and spacing in the `:root` section at the top of `style.css`.
- Project case studies use native HTML `<details>` and `<summary>`, so they expand without JavaScript.
- The visual artwork on each project card is CSS-drawn. Replace or supplement it with real images once you have them.
