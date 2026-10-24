# VAST Series Examination Analytics

Single-page tool (index.html) that runs entirely in the browser.

## Publish on GitHub Pages
1. Create a repository named `aruncx.github.io` (a user site) so that `robots.txt` is served from the site root. A project repo such as `aruncx.github.io/vast/` serves robots.txt from `/vast/robots.txt`, which crawlers ignore.
2. Upload `index.html`, `robots.txt` and `LICENSE` to the repository root.
3. Settings, Pages, Source: Deploy from a branch, branch `main`, folder `/ (root)`.
4. Open https://aruncx.github.io/

## Protection notes
- Right-click, F12, Ctrl+Shift+I/J/C, Ctrl+U and Ctrl+S are blocked, and an overlay appears if DevTools is open. This only deters casual copying.
- robots.txt asks AI crawlers (GPTBot, ClaudeBot, CCBot, Google-Extended, PerplexityBot and others) not to crawl. Only well-behaved crawlers obey it.
- A public repository exposes the source on GitHub itself. Use a private repo (GitHub Pages from private repos needs a paid plan) or accept that the code is visible.
