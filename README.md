# Netlify Portfolio (Mohannad Taha)

A minimal, production‑ready portfolio you can deploy to Netlify in minutes.

## Files
- `index.html` — main page with sections: Hero, About, Projects, Skills, Experience, Contact
- `styles.css` — modern, responsive styling (dark theme)
- `script.js` — small UX touches (current year, mobile nav)
- `404.html` — custom not‑found page
- `thank-you.html` — form submission confirmation (Netlify Forms)
- `netlify.toml` — configuration and security headers
- `assets/*` — images/illustrations
- `icons/favicon.svg` and `icons/favicon.png`

## Deploy (Git-based)
1. Create a new repo and push these files.
2. On Netlify: **New site from Git** → connect your repo.
3. Build settings:
   - **Base directory:** (blank)
   - **Build command:** (blank for static)
   - **Publish directory:** `/`
4. Deploy. Your site will be live at `https://<site>.netlify.app`.

## Deploy (Drag & Drop)
1. Zip the folder or drag the folder directly onto **https://app.netlify.com/drop**.
2. Done. (Yes, really.)

## Forms
The contact form uses **Netlify Forms** (no backend). When you submit,
Netlify will capture submissions in the dashboard. You can set the form's
success page by editing the `action` attribute or adding deploy‑time settings.

## Customize
- Replace images under `assets/` and `icons/`.
- Update text in `index.html`, especially project links.
- Tweak colors in `styles.css` `:root` variables.
