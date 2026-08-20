# The Missing Walk website

Zero-dependency static launch site for The Missing Walk.

## Files

- `index.html` — marketing home page
- `privacy.html` — App Store privacy-policy destination
- `support.html` — App Store support destination
- `styles.css` — shared responsive visual system
- `robots.txt` — search-crawler allowance

## Deliberate placeholders to replace before production

- `[LEGAL NAME]`
- `[SUPPORT EMAIL]`
- `[EFFECTIVE DATE]`
- final production domain / canonical URL
- App Store URL once the application is actually available
- exact location/session data-handling language after confirmation against the production iOS build

## Deployment

This folder can be deployed as-is to any static host. No build command or server runtime is required.

Recommended production checks before launch:

1. Replace all placeholders.
2. Verify privacy wording against the final iOS build and App Store privacy answers.
3. Add the real App Store link only after it exists.
4. Add canonical and Open Graph URLs once the domain is known.
5. Add the final app icon / social-sharing image only from approved product assets.
6. Run Lighthouse / Safari checks on the deployed URL.
