# Kartik Reddy Cricket Analyst — Telegram Landing Page

A single mobile-first landing page that introduces Kartik Reddy's official Telegram channel. It shows a profile header, trust stats and a large "Join Telegram" button. After a 3-second countdown, it automatically sends visitors to the Telegram invite link.

## Technologies

- Plain HTML, CSS and vanilla JavaScript in a single `index.html` file, with no build step
- Google Fonts (Plus Jakarta Sans, Teko) and Font Awesome, both loaded from a CDN
- Hosted on Netlify as a static site

## Running locally

Open `index.html` in a browser, or serve the folder with `netlify dev --port 8889`.

## Changing the Telegram link

The invite URL appears twice in `index.html`: in the `href` of the `#joinBtn` button and in the `TELEGRAM_URL` constant in the script. Update both.
