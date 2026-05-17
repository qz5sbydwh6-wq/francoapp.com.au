# francoapp.com.au

Public website for the Franco iOS app.

## Pages

- `index.html` — landing
- `privacy.html` — privacy policy (linked from App Store listing)
- `terms.html` — terms of use
- `support.html` — support / contact / FAQ (linked from App Store listing)
- `CNAME` — GitHub Pages custom domain binding

## Hosting

GitHub Pages serves this repo at https://francoapp.com.au

DNS:
- `francoapp.com.au` and `www.francoapp.com.au` point to GitHub Pages IPs
- Records managed at VIPcontrol (Ventraip)

## Editing

Just edit the HTML files directly. GitHub Pages rebuilds automatically on push.

The page styling is intentionally inline (no separate CSS file) so each page is fully standalone — there's no chance of a broken link to a shared stylesheet, and the site loads even if a CDN is slow.

Keep page content in sync with the in-app versions at:
`lib/screens/legal_and_story_screens.dart` (PrivacyScreen, TermsScreen)
