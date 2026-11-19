# Consultancy Website

Single-page site for an operations and growth consultancy serving veteran-owned small businesses and family- and community-centered organizations. Everything lives in one `index.html`; Tailwind CSS and Google Fonts load from CDNs, so there is no build step. Hosted with GitHub Pages from the `main` branch.

## Before launch: replace the placeholders

Find and replace these across `index.html`:

| Placeholder       | Replace with                     |
| ----------------- | -------------------------------- |
| `[FIRM NAME]`     | The firm's name                  |
| `[EMAIL ADDRESS]` | The address inquiries should go to |
| `[PHONE NUMBER]`  | The office phone number          |
| `[CITY, STATE]`   | The firm's location              |

Each email and phone placeholder appears in both the link and its text, so one find-and-replace updates both.

## Connecting the inquiry form

GitHub Pages only serves files, so it can't receive form submissions on its own. Pick one:

1. **Email (no setup).** Once `[EMAIL ADDRESS]` is replaced, submitting the form opens the visitor's email app with their inquiry filled in.
2. **Direct submission (recommended).** Create a free form at [Formspree](https://formspree.io) or a similar service, then paste its endpoint into `FORM_ENDPOINT` in the script at the bottom of `index.html`. Inquiries then arrive in your inbox without the visitor leaving the page.

## Preview locally

Open `index.html` in any browser.
