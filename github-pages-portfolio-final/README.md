# Adarsh Dubey — Cybersecurity & AI Portfolio

GitHub Pages-ready portfolio website.

## Files
- `index.html` — main portfolio page
- `CNAME` — custom domain file for GitHub Pages
- `.nojekyll` — disables Jekyll processing
- `robots.txt` and `sitemap.xml` — basic SEO files

## Important: custom domain
Replace `your-custom-domain.com` inside these files with your real domain:
- `CNAME`
- `robots.txt`
- `sitemap.xml`

Example: if your domain is `adarshdubey.com`, the CNAME file should contain only:

```txt
adarshdubey.com
```

## GitHub Pages deployment
1. Create a new GitHub repository.
2. Upload all files from this ZIP into the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**.
6. Save.

## DNS setup for custom domain
For an apex/root domain like `example.com`, add these A records at your domain provider:

```txt
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

For a subdomain like `www.example.com`, add a CNAME record pointing to:

```txt
Pauseandplay.github.io
```

Then add the domain in GitHub repository **Settings → Pages → Custom domain**.
