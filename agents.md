# Project: Kirill Kuzmin — Personal CV Website

## Overview
A single-page personal CV/portfolio website for Kirill Kuzmin, a B2B Sales & BizDev professional based in Amsterdam. Built as a static site (no framework, no build step) — just `index.html` and `photo.jpg`.

## Hosting
- **Platform:** GitHub Pages
- **Repository:** `https://github.com/kuzminkirillv-web/kirill.kuzmin`
- **Live URL:** `https://kuzminkirillv-web.github.io/kirill.kuzmin`
- **Branch:** `main`
- **Deploy:** Automatic on push (GitHub Actions)

## Local Setup
- **Local path:** `/Users/kirill/Вайбкодинг/`
- **Files:** `index.html`, `photo.jpg`, `agents.md`
- **Git remote:** `git@github.com:kuzminkirillv-web/kirill.kuzmin.git` (SSH)
- **SSH key:** `~/.ssh/github` (ed25519), added to GitHub account `kuzminkirillv-web`

## Tech Stack
- Pure HTML5 / CSS3 / Vanilla JS — no frameworks, no dependencies
- Google Fonts: `Playfair Display` (headings) + `Inter` (body)
- No build tools, no npm, no bundler

## Design System
| Token | Value | Usage |
|---|---|---|
| `--bg` | `#080808` | Page background (deep black) |
| `--surface` | `#111111` | Cards, nav, stats bar |
| `--surface2` | `#191919` | Skill tags, contact links |
| `--border` | `#2a2a2a` | All borders |
| `--text` | `#e6edf3` | Primary text |
| `--muted` | `#8b949e` | Secondary text, bullet points |
| `--accent` | `#c9a84c` | Gold — highlights, underlines, numbers |
| `--accent-l` | `#e8c96a` | Gold hover state |
| `--radius` | `12px` | Card border radius |

- **Heading font:** Playfair Display (serif) — elegant, professional
- **Body font:** Inter (sans-serif) — clean, readable
- **Philosophy:** Professional but not boring. No bright colours. Dark with warm gold accents.

## Page Sections
1. **Hero** — Name, tagline, role tags, bio, CTA buttons, photo
2. **Stats bar** — 4 animated counters (projects, retention rate, growth, contacts)
3. **Experience** — Vertical timeline with 4 jobs
4. **Skills** — Two-column grid: Core Competencies + Tools & Platforms
5. **Education** — Two cards + language strip
6. **Contact** — Email, phone, Telegram links
7. **Footer** — Copyright

## Interactive Features
- **Scroll-reveal animations** — sections fade + slide up via `IntersectionObserver`
- **Counter animation** — stats count up when scrolled into view (eased cubic)
- **Sticky nav** — transparent → solid background on scroll
- **Active nav link** — highlights current section as user scrolls
- **Card hover effects** — subtle lift (`translateY(-3px)`) + gold border glow
- **Photo hover** — removes slight grayscale filter on hover
- ~~Custom cursor~~ — removed per user request

## Content (Kirill Kuzmin)
- **Location:** Amsterdam
- **Email:** kuzmin.kirill.v@gmail.com
- **Phone:** +381 62 194 27 26
- **Telegram:** @sp4ceacademy

### Experience
| Company | Role | Period |
|---|---|---|
| IMS (Marketing B2B SaaS) | Business Manager | May 2024 – Present |
| ProductStar (RBC) | B2B Sales Manager | May 2023 – Apr 2024 |
| ED TECH | B2B Sales Manager | Nov 2022 – May 2023 |
| Freelance TG Development | Product / Project Manager | Jul 2022 – Present |

### Education
| Degree | Institution | Field | Year |
|---|---|---|---|
| Master's | ITMO University | Innovative Entrepreneurship | 2021–2022 |
| Bachelor's (Honours) | ITMO University | Technology Innovation Management | 2017–2021 |

### Languages
- Russian — Native
- Ukrainian — Native
- English — C1 Advanced

## Source Files
- **CV source:** `/Users/kirill/Desktop/Вайбкодинг/Kirill_Kuzmin_CV.docx`
- **Photo source:** `/Users/kirill/Desktop/Вайбкодинг/photo_2026-02-21 21.53.59.jpeg`
- **Photo** was rotated 90° clockwise with `sips` to fix portrait orientation

## Change History
| Change | Details |
|---|---|
| Initial build | Full single-page CV site created from DOCX CV |
| Photo rotation | Rotated 90° clockwise using `sips -r 90` |
| Background colour | Changed from dark navy `#0d1117` to deep black `#080808` |
| Cursor removed | Custom gold cursor dot + ring animation removed per user request |
| Git & deploy setup | SSH key generated, remote configured, force-pushed to resolve conflict |
