# RetailOS Landing Page

Static landing pages for RetailOS:

- `index.html`
- `login.html`
- `signup.html`

The site is built as plain HTML with Tailwind via CDN, so there is no build step required.

## Local Preview

Open `index.html` directly in a browser, or serve the folder with any static server.

## Deploy

### GitHub Pages

This repo uses standalone HTML files, so GitHub Pages can host it as a static site.

1. Open the GitHub repo.
2. Go to `Settings` > `Pages`.
3. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
4. Save.
5. GitHub Pages will publish the site and provide the live URL.

Note:
- GitHub Pages serves `index.html` by default, and this repo already uses that filename for the homepage.

### Vercel

1. Open [Vercel](https://vercel.com/).
2. Import this GitHub repository.
3. Framework preset: `Other`.
4. Build command: leave empty.
5. Output directory: leave empty.
6. Deploy.

This repo is already ready for root-path deployment with `index.html`.

### Netlify

1. Open [Netlify](https://www.netlify.com/).
2. Add a new site from Git.
3. Select this repository.
4. Build command: leave empty.
5. Publish directory: `.`
6. Deploy.

This repo is already ready for root-path deployment with `index.html`.

## Notes

- Primary CTA buttons on the homepage currently open WhatsApp:
  `https://wa.me/2348139535071`
- Navigation links on the landing page still scroll to on-page sections.
- The auth pages are static mockups designed to match the landing page visually.
