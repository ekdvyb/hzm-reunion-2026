# Harare Zimbabwe Mission Reunion 2026 — Campaign Pack

The complete campaign built around the original cover artwork. Same palette, same
message, extended into print, social, motion, branding, press and a ready-to-host
microsite.

**Event:** Saturday 5 December 2026
**Start:** The Temple, 10:00 AM · then Kingfisher Park, Harare
**Line:** Calling every comrade. Come and be together again.

---

## Start here

| If you want to… | Open |
|---|---|
| Post something today | `content-calendar.md` — pick the next date |
| Post with ready captions | `content-calendar.csv` — caption, hashtags, CTA, alt text |
| Print invitations or a poster | `print/` |
| Change profile/cover images | `digital/` |
| Make a Reel, Short or TikTok | `video/` |
| Send to media or partners | `mediakit/` and `press/` |
| Publish the event page | `web/index.html` |
| Keep everything on-brand | `brand/HZM-Reunion-2026-Brand-Guide.pdf` |

The original 21-post ad pack sits beside this folder in `../base/` and still
works. This folder is the wider campaign that replaces it for the
November–December push.

---

## Folder map

```
campaign/
├── content-calendar.csv      40 posts: date, time, platform, asset, caption, hashtags, CTA, alt, notes
├── content-calendar.md       quick scanning table of the same 40 posts
├── MANIFEST.txt              every file with size and SHA-256 checksum
├── print/                    7 print-ready layouts (300 dpi poster, invites, ticket, badge, signs, sticker)
├── digital/                 19 platform-sized stills (profiles, covers, banners, merch, wallpaper, highlights)
├── video/                    7 MP4s + 1 WebM + 2 GIF previews (silent, for trending audio)
├── brand/                    logos, monograms, avatar, favicon, 6-page brand guide
├── mediakit/                 4-page media kit (PDF + page PNGs)
├── press/                    press release (PDF, PNG, Markdown)
└── web/                      self-contained microsite + local assets + .ics calendar file
```

Palette:

| Token | Hex | Use |
|---|---|---|
| Ink | `#07160F` | Deepest background |
| Forest | `#0D2B1F` | Primary brand green |
| Gold | `#E5AB3E` | Primary accent |
| Champagne | `#F7E3AE` | Light gold on dark |
| Cream | `#F7F2E4` | Body text on dark, paper on light |
| Copper | `#B87A2A` | Fine rules, secondary accent |

Type: **Archivo Black** (display), **Cormorant Garamond** (serif), **Montserrat**
(body and UI).

---

## The 40-post calendar

Runs **Thursday 5 November → Sunday 6 December 2026**, all times CAT (UTC+2),
across Instagram, Facebook, WhatsApp, X, LinkedIn, TikTok, YouTube and email.

| Phase | Dates | Posts | Job |
|---|---|---|---|
| Tease | 5–7 Nov | 1–4 | Put the date in the diary |
| Announce | 8–11 Nov | 5–10 | Venues, travel, families, full invite |
| Details | 12–16 Nov | 11–15 | Email, quote, big date, kinetic video, venue card |
| RSVP | 17–20 Nov | 16–20 | Formal invite, Facebook event, link card, mixtape |
| Countdown | 21–30 Nov | 21–30 | Two weeks, press, poster, tees, stickers, sunrise |
| Final week | 1–4 Dec | 31–36 | This week, three days, print, tomorrow |
| Today | 5 Dec | 37–39 | Morning, 10 AM, live from the venue |
| Thank you | 6 Dec | 40 | Carousel of real photographs |

Every row in `content-calendar.csv` contains the finished caption, hashtags,
call to action, alt text and a posting note. Assets are referenced relative to
the `adverts/` folder, so `campaign/video/...` means `adverts/campaign/video/...`.

Weekly rhythm used by the schedule: one hero post per platform per day maximum,
Stories twice a week, video twice a week, and a committee member asked to share
each Facebook post with a personal line.

---

## Asset inventory

### Print — `print/`

| File | Pixels | Print size | Use |
|---|---|---|---|
| `poster-a3-3508x4961.png` | 3508 × 4961 | A3 at 300 dpi | Street, church, shop, office poster |
| `invitation-front-1500x2100.png` | 1500 × 2100 | 127 × 178 mm at 300 dpi | Invitation front, also good on WhatsApp |
| `invitation-back-1500x2100.png` | 1500 × 2100 | 127 × 178 mm at 300 dpi | Map, travel plan, contacts |
| `ticket-2100x900.png` | 2100 × 900 | 178 × 76 mm at 300 dpi | Entry ticket / reminder card |
| `badge-1000x1400.png` | 1000 × 1400 | 85 × 119 mm at 300 dpi | Name badge with `COMRADE` field |
| `table-sign-1480x1050.png` | 1480 × 1050 | 125 × 89 mm at 300 dpi | Table / refreshment sign |
| `car-sticker-1200x1200.png` | 1200 × 1200 | 100 mm circle at 300 dpi | Transparent PNG for sticker printing |

All print files are RGB. Ask the printer to convert to CMYK and to add 3 mm
bleed if they require it; the artwork already keeps text well inside the trim.

### Digital — `digital/`

| File | Size | Platform |
|---|---|---|
| `whatsapp-dp-1080x1080.png` | 1080 × 1080 | WhatsApp / Instagram profile |
| `avatar` in `brand/` | 1080 × 1080 | Fallback profile image |
| `email-banner-1200x400.png` | 1200 × 400 | Mailchimp / Gmail banner |
| `linkedin-cover-1584x396.png` | 1584 × 396 | LinkedIn page cover |
| `x-header-1500x500.png` | 1500 × 500 | X profile header |
| `facebook-event-cover-1920x1005.png` | 1920 × 1005 | Facebook event |
| `youtube-thumb-1280x720.png` | 1280 × 720 | YouTube thumbnail |
| `og-image-1200x630.png` | 1200 × 630 | Link preview / Open Graph |
| `zoom-background-1920x1080.png` | 1920 × 1080 | Zoom / Teams background |
| `mixtape-cover-3000x3000.png` | 3000 × 3000 | Playlist / carousel art |
| `tshirt-forest-3000x3600.png` | 3000 × 3600 | Merch mockup, forest colourway |
| `tshirt-cream-3000x3600.png` | 3000 × 3600 | Merch mockup, cream colourway |
| `tote-3000x3600.png` | 3000 × 3600 | Tote bag mockup |
| `phone-wallpaper-1170x2532.png` | 1170 × 2532 | Phone lock screen |
| `hl-01-info.png` … `hl-06-rsvp.png` | 1080 × 1080 each | Instagram highlight covers |

### Motion — `video/`

All videos are silent by design. Add trending or nostalgic audio in the app.

| File | Ratio | Length | Use |
|---|---|---|---|
| `01-reveal-9x16.mp4` | 9:16 | 9 s | Launch Reel / TikTok |
| `02-date-9x16.mp4` | 9:16 | 7 s | Date announcement |
| `03-kinetic-type-9x16.mp4` | 9:16 | 8 s | Kinetic-type Reel |
| `04-sunrise-loop-9x16.mp4` | 9:16 | 6 s | Loopable sunrise Story |
| `05-details-9x16.mp4` | 9:16 | 6 s | Everything-you-need Short |
| `06-teaser-1x1.mp4` | 1:1 | 5 s | Square feed teaser |
| `07-loop-16x9.mp4` | 16:9 | 8 s | Venue screen / Facebook |
| `07-loop-16x9.webm` | 16:9 | 8 s | Web hero fallback |
| `01-reveal-preview.gif` | 420 × 747 | 108 frames | Thumbnail preview |
| `03-kinetic-preview.gif` | 420 × 747 | 96 frames | Thumbnail preview |

H.264 (libopenh264) MP4s, 30 fps, no audio track. WebM is VP9.

### Brand — `brand/`

- `HZM-Reunion-2026-Brand-Guide.pdf` — 6 pages: cover, brand idea, logo,
  colour, type, voice.
- `brandguide-01.png` … `brandguide-06.png` — the same pages as images for slide decks.
- Lockups: horizontal and stacked, gold and forest versions.
- `monogram-gold-1600.png`, `monogram-forest-1600.png` — transparent.
- `avatar-square-1080.png`, `favicon-512.png`.
- `_preview-*.png` — previews only, not for publishing.

### Media kit and press — `mediakit/`, `press/`

- `mediakit/HZM-Reunion-2026-Media-Kit.pdf` — 4 pages: cover, story, campaign,
  contacts. Use for partners, editors, sponsors and radio.
- `press/HZM-Reunion-2026-Press-Release.pdf` — one-page release, plus `.md`
  source and a PNG for email bodies.
- All claims in these documents are limited to confirmed event facts.

### Web — `web/`

- `index.html` — single-file microsite. No build step, no framework, no server
  code. All CSS and JS are inline.
- `assets/` — 10 optimised gallery JPEGs, logo, favicon, OG image, hero loop
  (`hero.mp4`, 9:16, silent), video poster.
- `reunion-2026.ics` — calendar file with two reminders.

The page includes: live countdown, hero video, details cards, travel and kids
notes, gallery with lightbox, RSVP contact cards (call and WhatsApp), Google
Calendar link, share row, copy-link, media-kit/press/brand links and a sticky
navigation bar.

---

## Publish the microsite

The site is static, so any of these work:

1. **Netlify Drop** — drag the whole `web/` folder onto
   <https://app.netlify.com/drop>. You get a URL in seconds.
2. **GitHub Pages** — commit `web/` to a repository, enable Pages on the branch,
   publish from `/web`.
3. **Any shared host** — upload the contents of `web/` to `public_html`.

After you know the final URL, do these two things:

- In `web/index.html`, change
  `<meta property="og:image" content="assets/og.jpg">` to the absolute URL,
  e.g. `https://yourdomain.org/assets/og.jpg`. Most platforms will not resolve a
  relative OG image.
- Keep `web/assets/` and `reunion-2026.ics` beside `index.html`. All 17 local
  references are relative and already verified.

Share and copy-link buttons use the live page URL automatically, so no code
change is needed there.

Optional: add analytics by pasting a Plausible or GA snippet before `</head>`.
Do not add cookie-tracking pixels without checking consent requirements.

---

## Print guidance

- **Poster:** A3 at 300 dpi is the master. For A2, scale to 200%; for A1, 300%.
  The artwork is native vector-style drawing, so it stays sharp at large sizes.
- **Invitations:** print front and back on 250–300 gsm matte or silk. A6 also
  works — the layout is centred and forgiving.
- **Tickets and badges:** 300 gsm, single-sided. Badge has a clear name field.
- **Sticker:** order on white vinyl with a gloss laminate; keep the transparent
  PNG as supplied.
- **Colour:** the greens print richly; ask for a proof if using recycled stock.

---

## Regenerate anything

Scripts live in `../_work/` and write directly into this folder.

```bash
cd ../_work
python3 campaign_print.py      # 7 print pieces, poster at 300 dpi
python3 campaign_digital.py    # 19 digital pieces
python3 campaign_brandguide.py # brand guide + media kit + press release
python3 campaign_videos.py     # 7 videos, 1 WebM, 2 GIFs
python3 campaign_calendar.py   # content-calendar.csv and .md
```

The base 21-post pack is generated by `../_work/generate.py`.

Requirements: Python 3 with Pillow, ImageMagick and ffmpeg (with
`libopenh264`). Fonts must be installed under
`~/.local/share/fonts/flyers/` (`ArchivoBlack.ttf`,
`Cormorant1793625743255003953.ttf`, Montserrat).

---

## Quality status

| Area | Check |
|---|---|
| Base pack | 21 images + 8K master + contact sheet, visually QA'd |
| Print | 7/7 pass; poster verified at 3508 × 4961, 300 dpi |
| Digital | 19/19 pass |
| Brand / media kit / press | Pass; PDF text checked, no unverified claims |
| Video | Frame QA pass on all 7 MP4s and both GIFs |
| Microsite | Links 17/17, images 13/13, fonts load, no overflow or overlap at 1440, 500 and 390 px, countdown live, lightbox/copy/share/nav pass |
| Calendar | 40 posts, dates 5 Nov–6 Dec 2026, all asset paths exist, X posts under 280 characters |

Visual QA was done with a vision model on rendered slices, and layout geometry
was verified in a real Firefox browser where it mattered. Intentional design
choices — the sun disc bleeding off an edge, the marquee scrolling past the
viewport — are not defects.

---

## Event facts — copy and paste

```
Harare Zimbabwe Mission Reunion 2026
Saturday 5 December 2026
The Temple, 10:00 AM
then Kingfisher Park, Harare

Calling every comrade. Come and be together again.
Families and children welcome — mascot and jumping castle for the kids.
Travel together from The Temple, if you are willing.

RSVP:
Samantha Chauya   0779 227 983
Griffiths Mukwaira 0776 451 344
Elvis Kwaramba     0772 527 284
```

WhatsApp links in the pack use the international form: `263779227983`,
`263776451344`, `263772527284`.

Hashtags: `#HZMReunion2026 #ComeAndBeTogetherAgain #HarareZimbabweMission
#Reunion2026 #Harare #Zimbabwe`

---

## Notes and limits

- Nothing in the pack states or implies free admission. If the committee
  confirms that, add it deliberately to the site and calendar.
- The children's mascot and jumping castle are included as confirmed by the
  brief. Confirm with the committee before the final week.
- The 8K cover master remains an enhanced version of the embedded 2520 × 3564
  JPEG, not invented detail. New layouts are drawn natively at final size.
