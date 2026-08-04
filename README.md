# Shivangi Awasthi — Portfolio

A single-page portfolio site with an Apple-inspired design. No build step, no
dependencies — just static files.

## Files

| File          | Purpose                                  |
|---------------|------------------------------------------|
| `index.html`  | The entire website (HTML + CSS + JS)     |
| `404.html`    | Styled "page not found" page             |
| `favicon.svg` | Browser-tab icon (SA monogram)           |
| `README.md`   | This file                                |

## Preview locally

Just double-click `index.html` — it opens in your browser. That's it.

---

## Deploy with GitHub Pages (free, recommended)

1. **Create a GitHub account** at https://github.com if you don't have one.
2. Click the **+** (top-right) → **New repository**.
3. Name it **`awasthishivangi24.github.io`** (use your own username in place of
   `awasthishivangi24`). This exact name gives you a clean root URL.
   Set it to **Public**, then click **Create repository**.
4. On the new repo page, click **uploading an existing file**.
5. Drag in `index.html`, `404.html`, and `favicon.svg`, then click
   **Commit changes**.
6. Go to **Settings → Pages** (left sidebar).
7. Under **Build and deployment → Source**, choose **Deploy from a branch**.
   Set branch to **`main`** and folder to **`/ (root)`**, then **Save**.
8. Wait ~1 minute, refresh, and your site is live at:
   **https://awasthishivangi24.github.io**

To update the site later, upload the changed file to the repo again.

---

## Deploy with Netlify (fastest, ~30 seconds)

1. Go to https://app.netlify.com/drop
2. Drag the whole folder (or just `index.html`) onto the page.
3. You get an instant live URL. Create a free account to keep it and rename the
   subdomain under **Site settings → Change site name**.

---

## Add a custom domain (optional, ~$12/year)

1. Buy a domain (e.g. `shivangiawasthi.com`) from Namecheap, Cloudflare, or
   Porkbun.
2. **GitHub Pages:** Settings → Pages → **Custom domain** → enter your domain →
   Save, then add the DNS records GitHub shows you at your registrar.
   **Netlify:** Site settings → **Domain management** → **Add custom domain**.
3. Enable **HTTPS / Enforce SSL** (both hosts offer it free, one click).

---

## Update the résumé link

In `index.html`, the **Résumé (PDF)** link currently points to `#`. Once you
host a PDF (e.g. add `resume.pdf` to the repo), change that line to:

```html
<a href="resume.pdf" target="_blank">R&eacute;sum&eacute; (PDF)</a>
```
