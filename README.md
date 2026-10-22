# Gaurav Lokhande — DevOps & Cloud Portfolio

A responsive, static portfolio built with HTML, CSS, and vanilla JavaScript. No build tools, package installs, or server-side code are required.

## Included files

- `index.html` — portfolio content and page structure
- `style.css` — responsive design, layout, effects, and animations
- `script.js` — mobile navigation, scroll progress, reveal animations, active section navigation, and current year
- `assets/gaurav-lokhande.png` — supplied profile photo
- `assets/Gaurav_Lokhande_DevOps_Resume.pdf` — supplied résumé used by the Download résumé button

## Run locally

1. Extract the ZIP.
2. Open `index.html` in a modern browser.

For a local server (optional), run from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `gauravlokhande7248.github.io` for a user site, or any repository name for a project site.
2. Upload the contents of this folder to the repository root. Ensure `index.html`, `style.css`, `script.js`, and the `assets/` folder are at the repository root level.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for the Pages deployment to finish. GitHub will display the published URL in Settings → Pages.

For a project repository, the published URL typically follows `https://<username>.github.io/<repository>/`. For a user-site repository named `<username>.github.io`, the URL is `https://<username>.github.io/`.

## Personalization notes

- GitHub, LinkedIn, Credly, email, and phone links are based on the provided résumé.
- Project cards link to the GitHub profile because individual project repository URLs were not included in the résumé. Replace those links with specific repositories when available.
- The résumé lists AWS Cloud Quest: Cloud Practitioner as trained and AWS Certified Cloud Practitioner as in progress. The site preserves those statuses.
- Python was requested as a highlight, but the provided résumé does not include a Python skill detail or Python project. The site therefore flags that gap rather than presenting it as confirmed experience.
- Google Fonts are loaded from the web; if offline, the site falls back to system fonts.
- Contact form is intentionally omitted so the site does not pretend to send messages without a backend. Email and phone links work directly.

## Before publishing

- Preview on desktop and mobile.
- Verify that your résumé is current.
- If you add project repositories, update the project links in `index.html`.
