# Sabari Dev — DevOps & Cloud Portfolio

A responsive, terminal-inspired portfolio built with plain HTML, CSS, and JavaScript. It is designed for GitHub Pages and does not require a build step.

## Files

- `index.html` — page content and sections
- `styles.css` — layout, colors, responsive design, and animations
- `script.js` — mobile navigation and current year
- `assets/favicon.svg` — browser icon
- `assets/resume.pdf` — optional resume placeholder; replace it with your real PDF or remove the resume link

## Before publishing

1. Open `index.html`.
2. Replace `YOUR_EMAIL@example.com` with the email address you want to publish.
3. Replace `YOUR-LINKEDIN` with your LinkedIn profile slug, or remove the LinkedIn link if you do not want to share it.
4. Check the GitHub username and repository links. They currently point to `SabariDev18`; change them if needed.
5. Update each project link to its specific repository when available.
6. Add your actual resume as `assets/resume.pdf`, or remove the Resume links until you have one.
7. Review every project description and keep only the claims you can explain and demonstrate.

## Preview locally

You can open `index.html` directly in a browser. For a local web server, run this from the project directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

### Option A: Use the personal-site repository name

Create a **public** GitHub repository named exactly:

```text
YOUR-GITHUB-USERNAME.github.io
```

Copy the contents of this folder into the repository root, then run:

```bash
git init
git add .
git commit -m "Build DevOps portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME.github.io.git
git push -u origin main
```

On GitHub, open **Settings → Pages**. Under the build/deployment section, choose **Deploy from a branch**, select `main` and `/(root)`, then save. After GitHub finishes publishing, your site should be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/
```

### Option B: Use an existing repository

For a repository named `portfolio`, GitHub Pages usually publishes at:

```text
https://YOUR-GITHUB-USERNAME.github.io/portfolio/
```

The files can still be deployed from `main` and `/(root)`. Use relative paths for assets (this template already does).

## Custom domain

A custom domain is optional. You do not need to buy one to use GitHub Pages.

## Notes

- This is a static website. It does not include a server-side contact form or backend.
- The Google Fonts import is optional; if the visitor is offline or Google Fonts is unavailable, local system fonts are used as fallbacks.
- Keep secrets, access tokens, and private information out of the repository.
