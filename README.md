# Tseleng — Marketing Website

Static marketing website for **Tseleng**, Botswana's driver theory test prep web app at [tseleng.co.bw](https://tseleng.co.bw).

Built by [Kgaile Digital Solutions](https://kgailedigital.co.bw).

## Tech Stack

- Plain HTML + Tailwind CSS (CDN) + Font Awesome (CDN)
- No build tools, no frameworks
- Google Fonts: Plus Jakarta Sans

## Before You Deploy

Search for `TODO` comments in `index.html` and update the following:

| What | Where | Example |
|------|-------|---------|
| Tseleng app URLs (signup/login/subscribe) | All `href="https://tseleng.co.bw/..."` links | ✅ https://tseleng.co.bw |
| WhatsApp support number | Contact Support link in footer | ✅ 26771211867 |
| Meta Pixel ID | `<head>` section (uncommented) | ✅ 1421102126173317 |
| Google Analytics ID | `<head>` section (uncommented) | ✅ G-B7C4W5YSF3 |
| OG image | `og:image` and `twitter:image` meta tags (served by the web app) | ✅ https://tseleng.co.bw/og-image.png |
| Facebook page URL | Footer social link | ✅ https://www.facebook.com/tselengbw |
| Instagram page URL | Footer social link | ✅ https://instagram.com/tselengbw |
| Hero mockup image | Hero section `<img>` | ✅ assets/images/pedestrian-crossing.png |
| cPanel deploy path | `.cpanel.yml` | ⏳ /home/yourusername/public_html/ |

## Deployment

### Option A — Manual (cPanel File Manager)
1. Log into cPanel → File Manager
2. Navigate to your domain's document root (e.g. `public_html/`)
3. Upload all files from this folder

### Option B — Git Auto-Deploy (cPanel)
1. Push this repo to GitHub
2. In cPanel → Git™ Version Control → Create
3. Enter your GitHub clone URL
4. Update the `DEPLOYPATH` in `.cpanel.yml`
5. Pull to deploy; future pushes auto-deploy

## File Structure

```
tseleng-website/
├── index.html           ← Main (and only) page
├── data-protection-policy.html ← Data Protection Policy
├── favicon.png          ← Favicon (PNG)
├── favicon.svg          ← Favicon (SVG, scalable)
├── apple-touch-icon.png ← Apple Touch Icon (180×180)
├── assets/
│   └── images/
│       ├── logo.png              ← Official Tseleng logo
│       ├── og-image.png          ← Open Graph preview image (1200×630)
│       └── pedestrian-crossing.png ← Hero mockup image
├── .gitignore
├── .cpanel.yml          ← Auto-deploy config
└── README.md            ← This file
```

## License

© 2025 Tseleng / Kgaile Digital Solutions. All rights reserved.
