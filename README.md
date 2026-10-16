# CALD HDR Engagement Forum website

Website of the Culturally and Linguistically Diverse (CALD) HDR Engagement Forum at The University of Queensland.

Live site: https://yatarek.github.io/cald-uq.github.io/

## What's in this repository

| Path | What it is |
|---|---|
| `index.html` | The whole site. Each page (About, Program, 2026 Symposium, Committee, Resources, Contact) is a section switched from the sidebar, and links such as `#committee` open a page directly. |
| `img/header-banner.webp`, `img/scene/` | The animated header: the artwork as a still background, plus the cut-out character pieces that move. |
| `img/cald-logo.webp` | CALD logo in the top bar. |
| `img/jacaranda-uq.jpg` | Background photo for the About banner. |
| `img/committee/` | Committee photos. |
| `img/unis/` | University icons on the Symposium page. |
| `qr-code.png` | QR code for the 2026 Symposium registration form. |

## Updating the site

Edit `index.html`, then commit and push to `main`. GitHub Pages republishes automatically, usually within a minute or two.

Useful places to search for in `index.html`:

- `view-events`: 2026 Symposium details, dates and registration
- `view-committee`: committee members
- `view-resources`: resource links
- `view-contact`: contact details

## Previewing locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Credits

- Header artwork and CALD logo: supplied by the forum.
- About banner photo: Genevieve Mackintosh, from UQ Contact magazine, "UQ in bloom" (2021).
- Committee photos: UQ Experts profiles.
- University icons: each university's official website icon.
