# ISAIK — static site for GitHub Pages

This package contains a multilingual single-page website ready to publish on GitHub Pages.

## What changed in this version

- default language is **English**
- language switcher for **English / Español / Français**
- new brand direction centered on **Hacking the Noise**
- stronger positioning around **cybersecurity + sound + systems + hardware**
- new visual language: signal glyphs, console glass, controlled glow, cyber-sonic mood

## Included files

- `index.html` — homepage
- `styles.css` — visual styles
- `script.js` — translations, dynamic cards, mobile menu
- `404.html` — custom error page
- `robots.txt` — basic crawl rules
- `site.webmanifest` — device metadata
- `assets/og-cover.svg` — placeholder social preview image
- `assets/favicon.svg` — favicon

## What to edit first

Inside `index.html` and `script.js` update:

- real LinkedIn URL
- real SoundCloud / YouTube / Bandcamp URLs
- contact email if needed
- headline and bio copy if you want a more formal or more artistic tone
- project cards and service cards
- SEO title and description

## Recommended repo name

Create a public repository named exactly:

```text
yourusername.github.io
```

Replace `yourusername` with your real GitHub username.

## Upload with GitHub web UI

1. Create the repository.
2. Click **Add file**.
3. Choose **Upload files**.
4. Upload every file and folder from this package.
5. Commit the changes.

## Upload with Git

```bash
git init
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git add .
git commit -m "Deploy Isaik site"
git push -u origin main
```

## Enable GitHub Pages

1. Go to **Settings** in the repository.
2. Open **Pages**.
3. Under **Build and deployment**, choose:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Save.

Your site will be available at:

```text
https://yourusername.github.io
```

## Test locally

From the project folder run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Best next improvements

- add real proof links: GitHub, LinkedIn, demos, write-ups, talks
- add a downloadable cybersecurity CV and an artistic press kit
- add a music / media page with live excerpts or releases
- create a dedicated page for cybersecurity projects and another for artistic work
- connect a custom domain later
