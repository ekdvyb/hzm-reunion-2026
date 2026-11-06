# Harare Zimbabwe Mission Reunion 2026

The campaign site and full marketing pack for the **Harare Zimbabwe Mission
Reunion 2026** — Saturday 5 December 2026, The Temple at 10:00 AM, then
Kingfisher Park, Harare.

**Live site:** <https://hzm-reunion-2026.vercel.app>

---

## The event

> Calling every comrade. Come and be together again.

- **Date:** Saturday 5 December 2026
- **Start:** The Temple, 10:00 AM
- **Then:** Kingfisher Park, Harare — travel together from The Temple, if you are willing
- **Families:** children welcome; mascot and jumping castle for the kids
- **RSVP:** Samantha Chauya 0779 227 983 · Griffiths Mukwaira 0776 451 344 · Elvis Kwaramba 0772 527 284

---

## What is in this repository

| Path | What it is |
|---|---|
| `index.html` | The landing page and invitation microsite |
| `assets/` | Optimised web images, logo, OG image, silent hero loop |
| `reunion-2026.ics` | Calendar file with two reminders |
| `marketing/base/` | Original 21-post ad pack and 8K cover master |
| `marketing/campaign/print/` | A3 poster at 300 dpi, invitations, ticket, badge, table sign, sticker |
| `marketing/campaign/digital/` | 19 platform-sized stills — profiles, covers, banners, merch, wallpaper |
| `marketing/campaign/video/` | 7 silent MP4s, 1 WebM, 2 GIF previews |
| `marketing/campaign/brand/` | Logo suite, monograms, avatar, favicon, 6-page brand guide |
| `marketing/campaign/mediakit/` | 4-page media kit |
| `marketing/campaign/press/` | Press release (PDF, PNG, Markdown) |
| `marketing/campaign/content-calendar.*` | 40 ready-to-post captions for 5 Nov – 6 Dec 2026 |
| `marketing/campaign/MANIFEST.txt` | Every campaign file with size and SHA-256 |

The landing page links directly to the poster, invitation, videos, brand guide,
media kit, press release, content calendar and the full archive, so anyone can
carry the invitation without asking for files.

**Full pack download:**
<https://github.com/ekdvyb/hzm-reunion-2026/releases/latest/download/HZM-Reunion-2026-adverts.zip>

---

## Run it locally

No build step, no dependencies.

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

Or open `index.html` directly in a browser. The page is fully static.

---

## Deploy

The repository is ready for Vercel as a static site. Import the repo at
<https://vercel.com/new>, leave the framework preset as **Other**, and deploy.
No build command or output directory is required.

`vercel.json` adds long-lived caching for `assets/` and basic security headers.

After the final domain is known, set the absolute Open Graph and canonical URLs
in `index.html` (currently `https://hzm-reunion-2026.vercel.app/`).

---

## Design

| Token | Hex |
|---|---|
| Ink | `#07160F` |
| Forest | `#0D2B1F` |
| Gold | `#E5AB3E` |
| Champagne | `#F7E3AE` |
| Cream | `#F7F2E4` |
| Copper | `#B87A2A` |

Type: **Archivo Black** for display, **Cormorant Garamond** for headlines,
**Montserrat** for body and UI.

All artwork is drawn natively at final size from the original cover direction.
The 8K cover master is an enhanced version of the embedded 2520 × 3564 JPEG in
the source PDF, not invented detail.

---

## Notes

- Nothing in the pack claims free admission, and no unverified superlatives are
  used.
- The children's mascot and jumping castle are included as confirmed by the
  committee brief.
- The campaign calendar assumes CAT (UTC+2) and a 5 November – 6 December 2026
  publishing window.

---

## Contacts

| Name | Phone |
|---|---|
| Samantha Chauya | 0779 227 983 |
| Griffiths Mukwaira | 0776 451 344 |
| Elvis Kwaramba | 0772 527 284 |

#HZMReunion2026 · #ComeAndBeTogetherAgain · #HarareZimbabweMission
