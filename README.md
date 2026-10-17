# CALD HDR Engagement Forum website

Website of the Culturally and Linguistically Diverse (CALD) HDR Engagement Forum at The University of Queensland.

Live site: https://caldhdr-uq.github.io/ (the old address https://yatarek.github.io/cald-uq.github.io/ forwards here)

## What's in this repository

| Path | What it is |
|---|---|
| `index.html` | The whole site on one page: About, Registration, Speakers, Symposium day, Organisers and Contact, with the sponsor in the footer. Links such as `#speakers` jump straight to a section. |
| `img/cald-logo.webp` | CALD logo in the top bar. |
| `img/uq-logo-reversed.svg` | White UQ logo for the Sponsors block in the footer. |
| `img/hero-banner.jpg` | Banner image at the top of the page. |
| `img/committee/` | Organiser photos. |
| `img/speakers/` | Welcome address and speaker photos. |
| `qr-code.png` | QR code for the 2026 Symposium registration form. |

## Updating the site

Edit `index.html`, then commit and push to `main`. GitHub Pages republishes automatically, usually within a minute or two.

Useful places to search for in `index.html`:

- `id="registration"`: 2026 Symposium details, dates and registration
- `id="speakers"`: welcome addresses and symposium speakers
- `id="schedule"`: symposium day schedule table, venue and date
- `id="organisers"`: organisers (the forum committee)
- `f-sponsor`: Sponsors block in the footer
- `id="contact"`: contact details

## Previewing locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Credits

- CALD logo: supplied by the forum.
- Banner image: supplied by the forum.
- Organiser photos and positions: UQ Experts profiles.
- Deputy Vice-Chancellor photos: UQ Senior Executive Team page.
- Keynote speaker photo: Griffith Experts profile.
- UQ logo: The University of Queensland (static.uq.net.au).
