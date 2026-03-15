# The 18 Steps USA — Inauguration Website

The official website for **The 18 Steps USA Inauguration Ceremony**, taking place on **June 6, 2026** at the PYLUSD Performing Arts Center in Placentia, California.

## About The 18 Steps

The 18 Steps is a non-profit organization founded by **Sharath A. Haridasan** — a filmmaker, Vedic scholar, and spiritual orator. Born from a deep commitment to preserving and sharing the timeless wisdom of Sanatana Dharma, The 18 Steps has grown into a spiritual nerve center with over 105,000 YouTube subscribers and 600+ original videos.

The organization actively engages in:
- **Heritage Conservation** — Preserving India's spiritual and cultural heritage
- **Temple Renovation** — Supporting the revival and upkeep of temples and rituals
- **Vedic Education** — Courses, workshops, and discourses on Sanatana Dharma
- **Humanitarian Service** — Supporting students, orphanages, and communities in need

The 18 Steps USA brings these values to American shores, inaugurating its USA chapter with a landmark ceremony featuring cultural performances, spiritual discourse, and community celebration.

## Website Pages

| Page | Path | Description |
|------|------|-------------|
| Home | `/` | Landing page with event details, countdown, RSVP, program schedule, and raffle |
| Chaayamukhi | `/chaayamukhi` | Featured dance drama performance details |
| Donations | `/donations` | Donation options and book purchases |
| Gallery | `/gallery` | Art gallery with original Dharmic paintings |
| Sponsors | `/sponsors` | Sponsorship tiers and current sponsors |
| About Sharath | `/sharath` | Dedicated profile of Sharath A. Haridasan |
| Socials | `/socials` | All social media links and QR codes |
| Admin | `/admin` | Hidden admin tools (raffle draw, keynote, style guide) |

## Key Features

- Countdown timer to event date
- Google Maps integration for venue navigation
- Add-to-calendar dropdowns (Google, Apple, Outlook)
- Eventbrite RSVP integration
- Raffle ticket purchase via Zeffy
- Sponsor keynote presentation (full-screen slide deck)
- Live raffle winner selection tool
- Responsive design with cosmic theme and gold accents

## Event Details

- **Date:** Saturday, June 6, 2026
- **Time:** 2:00 PM — 8:00 PM PST
- **Venue:** PYLUSD Performing Arts Center, 1651 Valencia Ave, Placentia, CA 92870
- **Highlights:** Chaayamukhi dance drama, spiritual discourse, $1,500 raffle, professionally catered dinner
- **Entry:** Free (non-ticketed community event)

---

## Tech Stack

Built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com). Deployed on GitHub Pages.

## Project Structure

```text
/
├── public/
│   └── images/          # Event photos, book covers, QR codes, etc.
├── src/
│   ├── components/      # Navbar, Footer
│   ├── layouts/         # Layout wrapper (Layout.astro)
│   ├── pages/           # All site pages
│   │   ├── admin/       # Admin tools (raffle, keynote, style guide)
│   │   └── ...          # Public pages
│   └── styles/          # Global CSS with design tokens
└── package.json
```

## Commands

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`       |
| `npm run build`           | Build your production site to `./dist/`           |
| `npm run preview`         | Preview your build locally, before deploying      |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check`  |
| `npm run astro -- --help` | Get help using the Astro CLI                      |

## Learn More

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
