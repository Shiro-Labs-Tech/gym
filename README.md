# Shiro Gym

Landing page case study by [Shiro Labs](https://shiro-labs.tech). Live at https://gym.shiro-labs.tech

**This is a concept project.** Shiro Gym is not a real business. The classes, prices, hours and clubs are invented to show what a polished small-business landing page build looks like.

## What it shows

- Variable-font hero (Anybody, width and weight axes driven by the pointer)
- Live heart-rate canvas trace that reacts to pointer and scroll activity
- Scroll-velocity marquee, sticky stacking cards, 3D-tilt pricing cards
- Class finder quiz that picks a real slot and pre-fills a WhatsApp booking message
- Weekly schedule with Jakarta-time "open now" status
- Stylized multi-city locations map (schematic, pins link to OpenStreetMap)
- English, Bahasa Indonesia and Japanese, with USD, IDR and JPY pricing
- Respects `prefers-reduced-motion`

## Stack

One static `index.html`. No framework, no build step. Fonts come from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server.

## Deploy

Hosted on Vercel from `main` (static, no build command). The subdomain is a CNAME at the DNS provider pointing to Vercel.
