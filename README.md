# bookupiq-presentation

A short slide deck that introduces BookUp IQ, the clinic operating layer that turns ads and WhatsApp messages into booked, attended and paid consultations. It covers the problem, the BookUp loop, a walkthrough of the product with screenshots and recordings, the staff roles, the platform it is built on, the MVP scope and the roadmap. It is for people who meet BookUp IQ for the first time. The product itself runs at `bookupiq.com` (the clinic app at `app.bookupiq.com`); this repository holds only the deck, which GitHub Pages serves at <https://hatchup-io.github.io/bookupiq-presentation/>. The repository is public.

## What is inside

| Path | What it is |
| --- | --- |
| `index.html` | The deck: 16 slides in one self-contained HTML file (fonts from Google Fonts) |
| `assets/` | The logo, the product screenshots, and the two recordings |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

The screenshots and recordings in `assets/` come from the BookUp IQ prototype and contain only fictional demo data.

The two recordings are in `assets/` as GIFs (`05-book-from-inbox.gif`, `06-whatsapp-lead.gif`), shown on their slides, and as smaller MP4 copies; each slide links to both for download.

## View it

Open `index.html` in a browser, or view the published version at <https://hatchup-io.github.io/bookupiq-presentation/>. There is nothing to build or install.

Use the arrow keys, space, the on-screen buttons, a click or a swipe to move between slides. Add `#n` to the URL to open slide n.

## Test

There are no tests and no CI. Open the deck in a browser and step through every slide before you push.

## Deploy

GitHub Pages builds the site from the root of the `main` branch (a classic Pages build, no workflow in this repository). A push to `main` updates the published deck. No swarm stack runs anything from this repository.

## Related repositories

The deck presents the BookUp IQ product, which is built in:

- [bookupiq-backend](https://github.com/hatchup-io/bookupiq-backend): the API.
- [bookupiq-app](https://github.com/hatchup-io/bookupiq-app): the clinic app.
- [bookupiq-website](https://github.com/hatchup-io/bookupiq-website): the public website.
- [bookupiq-admin](https://github.com/hatchup-io/bookupiq-admin): BookUp IQ Admin.
