# LittleBig — first website version

A responsive static website concept: tiny discoveries, creative prompts, and mini activities.

## Files
- `index.html` — complete website, styling, and interactive features.
- `favicon.svg` — simple site icon.
- `robots.txt` — allows search engines to crawl the site.
- `sitemap.xml` — starter sitemap template. Replace `YOUR_GITHUB_USERNAME` and `YOUR_REPOSITORY` with your actual GitHub username and repository name before publishing.

## Features
- Responsive white/minimal design
- Discover / Create / Try filters
- Search across ideas
- Surprise-me button and daily nudge
- Save ideas in browser localStorage
- Share site/ideas using native share when supported, otherwise copy link
- No account, API key, paid service, or build step required

## Publish free using GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a **public** repository named `littlebig` (or another name you like).
3. Upload `index.html`, `favicon.svg`, `robots.txt`, and `sitemap.xml` to the repository root.
4. Edit `sitemap.xml` and replace the placeholder URL with your real GitHub Pages URL.
5. Open repository **Settings → Pages**.
6. Under build/deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
7. Wait for GitHub Pages to publish. The address will usually be `https://YOUR_GITHUB_USERNAME.github.io/littlebig/`.
8. Test on phone and desktop.

For a user/organization site, the repository name needs to match `YOUR_GITHUB_USERNAME.github.io`; then the URL is `https://YOUR_GITHUB_USERNAME.github.io/`.

## Google Search
1. Once the public site is live, open https://search.google.com/search-console/
2. Add a URL-prefix property matching the exact live URL, including the repository path for a project site.
3. Follow Google's verification instructions. For GitHub Pages, HTML file verification may be possible; upload the provided verification file to the repository root if Google offers that method. DNS verification requires access to a domain's DNS settings.
4. Submit the sitemap URL, for example `https://YOUR_GITHUB_USERNAME.github.io/littlebig/sitemap.xml`.
5. Use URL Inspection to request indexing for the homepage.
Google indexing is free but not guaranteed or instant. Useful original content, working links, and a clear site description help.

## Custom domain
GitHub Pages can use a custom domain you own. Registering a new `.com` or `.in` domain normally costs money. If you already own a domain, follow GitHub Pages' custom-domain guide and configure DNS with your domain provider. Do not pay for anything just to launch the first version.

## Important next steps
- `LittleBig` is a working name, not a trademark/domain availability check.
- The starter sitemap is a template; replace its URL before submitting.
- The idea cards are local content. Saved items are stored in the visitor's browser only; there is no shared database or account system yet.
