# Patriot Consulting Website

Site for Patriot Consulting, an operations and growth consultancy serving veteran-owned small businesses and family- and community-centered organizations. Tailwind CSS and Google Fonts (Libre Caslon) load from CDNs, so there is no build step. Hosted with GitHub Pages from the `main` branch.

| File                | What it is                                       |
| ------------------- | ------------------------------------------------ |
| `index.html`        | The home page                                    |
| `about.html`        | About the founder: portrait, bio, LinkedIn       |
| `css/site.css`      | Shared styles for both pages                     |
| `images/andrew.jpg` | The portrait on the About page                   |

The masthead, menu, and footer are repeated in both pages, so edit both when you change them. On `about.html`, the menu links point to `index.html#section`.

## Before launch: replace the placeholders

Find and replace these across `index.html` and `about.html`:

| Placeholder       | Where                       | Replace with                       |
| ----------------- | --------------------------- | ---------------------------------- |
| `[EMAIL ADDRESS]` | Both pages                  | The address inquiries should go to |
| `[PHONE NUMBER]`  | Both pages                  | The office phone number            |
| `[CITY, STATE]`   | Both footers                | The firm's location                |
| `[BIO]`           | `about.html`                | A short bio, one `<p>` per paragraph |

Each email and phone placeholder appears in both the link and its text, so one find-and-replace updates both. The firm name is set to "Patriot Consulting"; to change it, find and replace that text in both pages as well.

To change the portrait, replace `images/andrew.jpg`. If the file is missing, the About page shows a plain placeholder box instead.

## Connecting the inquiry form

GitHub Pages only serves files, so it can't receive form submissions on its own. Pick one:

1. **Email (no setup).** Once `[EMAIL ADDRESS]` is replaced, submitting the form opens the visitor's email app with their inquiry filled in.
2. **Direct submission (recommended).** Create a free form at [Formspree](https://formspree.io) or a similar service, then paste its endpoint into `FORM_ENDPOINT` in the script at the bottom of `index.html`. Inquiries then arrive in your inbox without the visitor leaving the page.

## Preview locally

Open `index.html` in any browser.
