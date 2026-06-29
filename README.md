# dev-techs.com static company site

Single-page static company website for `dev-techs.com`.

## Files

- `index.html` - company website content.
- `styles.css` - responsive layout and visual design.
- `logo.svg` - favicon and site logo.
- `robots.txt` - search crawler allowlist.
- `sitemap.xml` - canonical URL for search engines and verification crawlers.
- `_headers` - Cloudflare Pages security and cache headers.
- `vercel.json` - Vercel static deploy headers.

## Deploy

This site can be deployed as a static site on Cloudflare Pages, Vercel, Netlify, or any basic web host.

Recommended fast path:

1. Publish this folder with GitHub Pages, Cloudflare Pages, Vercel, or any static host.
2. Add the custom domain `dev-techs.com`.
3. Add the DNS records requested by the host.
4. Confirm `https://dev-techs.com` opens without browser warnings.
5. Use `https://dev-techs.com` in Meta Business Verification.

## GitHub Pages DNS

When GitHub Pages is used, set these DNS records in the domain provider panel:

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | alibaytok.github.io |

Do not add wildcard DNS records.

Drag-and-drop option:

- Upload `dev-techs-site.zip` to a static host that accepts ZIP uploads.
- If the host asks for build settings, use no build command and root output directory `/`.

For Meta Business Verification, keep the company details on the page aligned with official company documents.
