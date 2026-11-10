# Dainik Panchang Website

Official promotional website for **Dainik Panchang (दैनिक पंचांग)** — an offline-first, senior-centric Hindu Vrat & Tithi calendar for Android, crafted by [anvik.studio](https://anvik.studio).

Live URL: [https://panchang.anvik.studio](https://panchang.anvik.studio)
Google Play: [Dainik Panchang on Google Play](https://play.google.com/store/apps/details?id=studio.anvik.dainikpanchang)

## Features

- Modern single-page landing site designed with Tailwind CSS, Plus Jakarta Sans, and Cinzel/Rozha typography
- Bhagwa/Saffron and warm Gold ambient dark theme matching anvik.studio design system
- Interactive screenshot viewer showcasing Today Panchang, Monthly Calendar, Vrats & Festivals, and District Settings
- Interactive Live Panchang & Choghadiya preview widget
- Regional language showcase supporting 11 Indian languages
- Side-by-side comparison with ad-cluttered conventional calendar apps
- Accessible semantic markup, high-contrast ratios, Schema.org `SoftwareApplication` JSON-LD, and OpenGraph SEO tags

## Local Development

Start a local server with Python 3:

```bash
python3 -m http.server 4173
```

Then visit [http://localhost:4173](http://localhost:4173).

## Deployment

Automated via GitHub Actions to GitHub Pages on every push to `main` branch.
