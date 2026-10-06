# Ysabela — Professional Portfolio

Standalone static reconstruction of the existing Ysabela Marasigan Squarespace portfolio.

## Stack

- Semantic HTML5
- CSS3
- Vanilla JavaScript
- No React
- No build step
- No database
- No backend

## Run locally

Because this is a static site, you can open `index.html` directly in a browser.

For a local server, from the project directory:

```bash
python -m http.server 8000
```

Then visit:

`http://localhost:8000`

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder.
3. Go to **Settings → Pages**.
4. Select the branch containing the website and the root folder.
5. Save.
6. GitHub will provide the published URL.

## Deploy to Netlify

1. Create a Netlify account.
2. Choose **Add new site → Import an existing project**.
3. Connect the GitHub repository.
4. Build command: leave blank.
5. Publish directory: `/`
6. Deploy.

## Deploy to Cloudflare Pages

1. Create a Pages project.
2. Connect the GitHub repository.
3. Framework preset: None.
4. Build command: leave blank.
5. Output directory: `/`.

## Custom domain

Replace `YOUR-DOMAIN.example` in the SEO/canonical files with the final domain, then configure the domain in the hosting provider.

## Contact form

The form is intentionally not presented as automatically sending email.

Open `contact.html` and replace:

`YOUR_FORM_ENDPOINT`

with your Formspree/Netlify Forms endpoint.

## Assets that still need replacement

The supplied materials were screenshots, not the original source image files. The reconstruction therefore contains crops made from the supplied screenshots. Replace the following with original high-resolution assets where possible:

- `assets/images/home-hero.jpg`
- `assets/images/about-portrait.jpg`
- `assets/images/how-step-1.jpg`
- `assets/images/how-step-2.jpg`
- `assets/images/how-step-3.jpg`
- `assets/images/admin-email.jpg`
- `assets/images/admin-management.jpg`
- `assets/images/admin-tracker.jpg`
- `assets/images/writing-hero.jpg`
- `assets/images/research-hero.jpg`
- `assets/images/creative-left.jpg`
- `assets/images/creative-right.jpg`
- `assets/images/portfolio-admin.jpg`
- `assets/images/portfolio-writing.jpg`
- `assets/images/portfolio-research.jpg`
- `assets/images/portfolio-creatives.jpg`
- `assets/images/contact-hero.jpg`

## Documents still needed

No actual resume PDF or certificate files were supplied with the screenshots. Add them to:

`assets/documents/`

Then activate the placeholder links on `about.html` and `credentials.html`.

## Squarespace-specific features

The following cannot be reproduced exactly without the Squarespace platform:

- Squarespace editor/admin interface
- Squarespace's native form-processing service
- Squarespace scheduling/invoicing/membership integrations
- Squarespace analytics dashboard
- Any private Squarespace CMS data

The portfolio pages themselves are implemented as ordinary static HTML/CSS/JS.

## Content integrity

Practice/fictitious portfolio examples are not represented as client work. Replace them with original files and descriptions where applicable.

## Structure

```text
ysabela-portfolio/
├── index.html
├── about.html
├── services.html
├── work.html
├── how-i-work.html
├── research.html
├── writing.html
├── creatives.html
├── administrative-support.html
├── credentials.html
├── contact.html
├── css/style.css
├── js/script.js
├── assets/
│   ├── images/
│   ├── icons/
│   └── documents/
├── robots.txt
├── sitemap.xml
├── README.md
└── .gitignore
```
