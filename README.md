# Ningchen Ma — Personal Site

A single-page personal profile site. Plain HTML/CSS, no build step.

- `index.html` — the main page
- `loop-app.html` — the Loop workforce-planning prototype (linked from Projects)

## Deploy on GitHub Pages (free)

1. Create a free account at github.com, then click **New repository**.
   - To publish at `https://<username>.github.io`, name the repo exactly `<username>.github.io`.
   - (Any other name publishes at `https://<username>.github.io/<repo-name>/`.)
   - Set it to **Public**.
2. On the new repo page, click **uploading an existing file** and drag in
   `index.html`, `loop-app.html`, `.nojekyll`, and this `README.md`. Click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set
   **Source = Deploy from a branch**, **Branch = main**, folder **/(root)**, then **Save**.
4. Wait ~1 minute and refresh — your live URL appears at the top of that Pages screen.

## Updating the site later

Edit the file (in GitHub's web editor or re-upload it) and commit. The live site
rebuilds automatically within a minute. Hard-refresh (Cmd+Shift+R) to see changes immediately.

## Using a custom domain (optional, later)

Buy a domain (~$10/yr at Cloudflare or Porkbun), then in **Settings → Pages → Custom domain**
enter it and add the DNS records GitHub shows you at your registrar. HTTPS is free and automatic.
