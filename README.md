# Ayush Kushwaha | Portfolio

ML/DL engineer portfolio with a WebGL background, built as a single static page.

**Live:** https://0xkushwaha.github.io/portfolio/

## Files
- `index.html` : the whole site (HTML, CSS, JS in one file; Three.js loads from cdnjs, fonts from Google Fonts)
- `resume.pdf` : downloadable resume
- `og-image.png` : link preview image for LinkedIn, WhatsApp, X
- `.nojekyll` : tells GitHub Pages to serve files as-is
- `photo.jpg` : optional square profile photo (initials show until you add it)

## Run locally
No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy on GitHub Pages
1. Push this repo to GitHub (`0xKushwaha/portfolio`, public).
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch `main`, folder `/ (root)`, then **Save**.
5. Wait 1 to 2 minutes. The site appears at https://0xkushwaha.github.io/portfolio/.

Every push to `main` redeploys automatically.

## Customise
- **Photo:** add a square `photo.jpg` in the root.
- **Resume:** replace `resume.pdf`, keep the same file name.
- **Link preview:** after deploying, check it at https://www.opengraph.xyz.

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
