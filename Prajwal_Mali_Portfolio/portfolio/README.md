# Prajwal Mali — Personal Portfolio

A responsive personal portfolio website built from the information in Prajwal Mali's CV.

## Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (Inter + Space Grotesk)

## Project structure

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── assets/
│   └── Prajwal_Mali_Resume.pdf
└── README.md
```

## Run locally

No build tools are required.

### Option 1 — Open directly

Double-click `index.html` and it will open in your browser.

### Option 2 — VS Code Live Server

1. Open the `portfolio` folder in VS Code.
2. Install the **Live Server** extension if you use it.
3. Right-click `index.html`.
4. Choose **Open with Live Server**.

### Option 3 — Python local server

From the portfolio folder:

```bash
python -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

## GitHub Pages deployment

1. Sign in to GitHub.
2. Create a new repository, for example `prajwal-portfolio`.
3. Upload all files and folders from this project.
4. Make sure `index.html` is in the repository root.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
7. Save.
8. GitHub will provide your live Pages URL after deployment.

## Before publishing

- Verify the resume PDF opens from the **View Resume** button.
- Test the mobile navigation.
- Test the theme toggle.
- Test LinkedIn and GitHub links.
- Test the contact form on a device with an email client configured.
- If you later add a custom domain, update the GitHub Pages settings.

## Content policy for this portfolio

The content was intentionally kept faithful to the CV. No additional companies, achievements, certifications, project links, responsibilities or dates were invented.
