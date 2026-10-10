# LensLink Photography Redesign

A responsive, multi-page wedding photography website built with static HTML, CSS, and JavaScript.

## Run locally

From the project folder:

```bash
py -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Caching and deployment

The `_headers` file configures revalidation for HTML and one-year immutable caching for the versioned CSS and JavaScript assets on static hosts that support this format, including Netlify and Cloudflare Pages. When changing `styles.css` or `script.js`, increment the matching `?v=` value in each HTML page so visitors receive the new asset. A basic local HTTP server does not apply `_headers` rules.

The `robots.txt` file allows indexing. Add canonical URLs and a sitemap after the production domain is selected so search engines are not given placeholder URLs.

## Files

- `index.html` — page structure and content
- `styles.css` — layout, typography, colors, and responsiveness
- `script.js` — mobile nav and small interactive behaviors

## Notes

This is a clean redesign inspired by the original brand and structure, while improving clarity, spacing, visual hierarchy, and usability on mobile and desktop.
