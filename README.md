# subashsaajan.site

Personal site of Subash Saajan J, a full-stack engineer working in TypeScript, Go and Python.

Live at **https://subashsaajan.site**

It's one hand-written HTML page with its CSS inline. There's no framework and no build step. Cloudflare Pages deploys every push to `main`.

## What's in here

| File | Purpose |
|---|---|
| `index.html` | The page, plus Open Graph tags and JSON-LD (`WebSite`, `ProfilePage` and `Person`, linked by `@id`) |
| `llms.txt` | Plain-text summary for language models and AI search tools |
| `robots.txt` | Lets search and AI crawlers in, and points to the sitemap |
| `sitemap.xml` | The single URL, with its image |
| `404.html` | Not-found page (Cloudflare Pages serves it with a real 404 status) |
| `resume.pdf` | Current résumé |
| `og-image.png` | 1200x630 link-preview card |
| `<key>.txt` | IndexNow key, used to tell Bing about updates |

## Run locally

```bash
npx serve .
```
