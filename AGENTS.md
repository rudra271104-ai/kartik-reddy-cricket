# AGENTS.md

## Architecture
This is a static, single-page site with no framework and no build step. All markup, styles and scripts are in `index.html`. Netlify publishes the repo root (see `netlify.toml`).

## Key files
- `index.html`: the whole page (inline `<style>` and `<script>`)
- `netlify.toml`: sets publish = "." and no build command

## Conventions and decisions
- Keep it a single dependency-free file. The page is sized for mobile (max-width 440px).
- The Telegram invite URL is in two places: the `#joinBtn` href and `TELEGRAM_URL` in the script. Keep them in sync.
- The countdown is 3 seconds. If you change the duration, update `timeLeft`, the divisor in the offset calculation, and the visible "3" text in the markup.
