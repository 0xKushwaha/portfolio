# Ayush Kushwaha | Portfolio

ML/DL engineer portfolio with a WebGL background, built as a single static page.

**Live:** https://0xkushwaha.github.io/portfolio/

## Files
- `index.html` : the whole site (HTML, CSS, JS in one file; Three.js loads from cdnjs)
- `resume.pdf` : downloadable resume
- `og-image.png` : link preview image for LinkedIn, WhatsApp, X
- `.nojekyll` : tells GitHub Pages to serve files as-is

## Deploy
Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
Live in 1 to 2 minutes.

## Customise
- **Photo:** add a square `photo.jpg` in the root. Initials show until then.
- **Resume:** replace `resume.pdf`, keep the same file name.
- **Link preview:** check at https://www.opengraph.xyz after deploying.

## Shorter URL (optional)
Rename this repo to `0xKushwaha.github.io` to serve it at https://0xkushwaha.github.io,
then update the `og:url` and `og:image` lines in `index.html`.

## Custom domain (optional)
1. Add a `CNAME` file containing just your domain (e.g. `ayushkushwaha.dev`)
2. At your registrar, add A records for `@` to
   185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   and a CNAME for `www` to `0xkushwaha.github.io`
3. Settings > Pages: enter the domain, tick "Enforce HTTPS"
4. Update `og:url` and `og:image` in `index.html`
