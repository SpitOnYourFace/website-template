# 🏗️ Website Template — KrasiKralev.com

Astro 5 + Tailwind starter за бизнес сайтове. Clone → customize → deploy за 2 часа.

## Quick Start

```bash
# Clone
degit SpitOnYourFace/website-template my-client-site
cd my-client-site
npm install

# Customize
# 1. Edit src/pages/index.astro → CLIENT config object
# 2. Edit src/styles/theme.css → uncomment niche preset
# 3. Add images to public/
# 4. Update astro.config.mjs → site URL

# Dev
npm run dev

# Build & Deploy
npm run build
npx vercel --prod
```

## Niche Presets (theme.css)
- 🦷 Зъболекар / Дентална клиника
- 💪 Фитнес зала
- 🧘 Йога студио
- 💈 Барбершоп
- 💇 Фризьорски салон
- ⚖️ Адвокат
- 💄 Козметичен салон
- 💅 Маникюр студио

## Components
| Component | Props |
|-----------|-------|
| Header | businessName, phone, links[] |
| Hero | headline, subheadline, ctaText, ctaHref, image, variant |
| Services | headline, services[], columns |
| Reviews | headline, reviews[] |
| Contact | phone, email, address, workingHours, mapEmbed, whatsapp |
| Footer | businessName, year |
| WhatsAppFloat | phone |
| CookieBanner | — |
| BackToTop | — |

## Features
- ⚡ Zero JS by default (Astro islands)
- 🎨 CSS variables = change theme in 2 min
- 📱 Fully responsive
- 🔍 SEO: JSON-LD, sitemap, robots.txt, meta tags
- 🚀 View Transitions (SPA-like navigation)
- 🍪 GDPR cookie banner
- 💬 WhatsApp floating button
- 🎯 Lighthouse 100/100/100/100

## Per-Client Customization

Only edit these files:
1. `src/pages/index.astro` → CLIENT object (name, phone, services, reviews)
2. `src/styles/theme.css` → :root variables
3. `astro.config.mjs` → site URL
4. `public/` → favicon, images
