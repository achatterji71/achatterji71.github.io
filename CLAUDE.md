# achatterji71.github.io — Project Context

## What this is
A personal website for Ashu Chatterji (Ashutosh Chatterji), rebuilt in 2026 from a 2005 FrontPage/Tripod site. Hosted on GitHub Pages at **https://achatterji71.github.io**.

The site is a digital memoir — a restoration of the original content with a 2026 sensibility, preserving the vintage writing as a time capsule while being honest about what has changed. Phase 2 will layer in the post-2005 chapters.

---

## Owner profile
- **Name:** Ashu Chatterji (Ashutosh Chatterji)
- **GitHub:** achatterji71
- **Background:** Software engineer by training, ~20 years in technical program management and executive roles, now re-entering hands-on development
- **Location:** Ashburn, Virginia (primary); Calcutta (spiritual home)
- **Device:** Microsoft Surface Pro (Windows)

---

## Design system

### Fonts
- **Cormorant Garamond** — headings, body prose, captions (literary, warm)
- **DM Sans** — navigation, labels, UI elements (clean, modern)
- Both loaded from Google Fonts

### Colour palette (CSS variables)
```css
--ink:        #1a1a18;   /* near-black body text */
--ink-light:  #5a5a54;   /* secondary text */
--ink-faint:  #9a9a92;   /* captions, metadata */
--paper:      #faf9f6;   /* page background */
--cream:      #f2efe8;   /* card hover, blockquotes */
--rule:       #e0ddd4;   /* borders, dividers */
--accent:     #b85c2a;   /* terracotta — links, labels, highlights */
```

### Visual tone
Clean and minimal. White space, warm neutrals, terracotta accent. No dark mode. Subtle fade-up animations on page load (`fadeUp` keyframe). Sepia filter on historical photos (`filter: sepia(15%) contrast(1.05)`).

### Layout
- Max content width: **860px**, centred
- All pages share the same header/nav/footer structure
- Breadcrumb navigation on all sub-pages
- Cards use a CSS grid with `gap: 1px; background: var(--rule)` for the hairline grid effect

---

## Site structure

### Top-level sections (homepage)
- **Family** — people + family places
- **Places** — professional and life chapters
- **Interests** — links, reading, hobbies

### File naming
All pages use `.htm` extension (matching the original Tripod site). Homepage is `index.html`.

### Pages built (Phase 1 complete)

#### Homepage
- `index.html` — bio intro, Bruges family photo, three section groups

#### Family section
- `family.htm` — intro page with cards to all family members
- `thamma.htm`, `ma.htm`, `babali.htm`, `jamu.htm`, `mamon.htm` — placeholders
- `tanu.htm` (wife), `mini.htm` (daughter), `pronoy.htm` (son — has birth photos), `gagga.htm` (sister) — placeholders except Pronoy
- `71_wk_road.htm`, `asansol.htm`, `boumar_bari.htm`, `boy_trips.htm` — placeholders (family places)
- `us_homes.htm` — Our Homes landing page → links to sub-pages
- `apartments.htm` — combined Herndon/Watervliet/Columbia/Fairfax page (1996–2001)
- `sterling_va.htm` — first owned home with 17 photos (boxcar00–16)
- `ashburn_va.htm`, `manila.htm`, `calcutta_ashram.htm` — placeholders

#### Alma Maters section (under Places)
- `alma_maters.htm` — landing page for St. Mary's, REC, GWU
- `marian.htm` — Marian Musings (St. Mary's Academy, 1975–1988)
  - `reminiscences.htm` — reunion with Krishnan, Lakshmi, Nisheeth
  - `visitingstmarys.htm` — homecoming 2003 with daughter
  - `lakshmi_the_poet.htm` — Lakshmi's Linux parody of Tagore
- `rourkela.htm` — Rourkela Ruckus (REC, 1988–1992)
  - `hall_1.htm` — 5 photos (Hostel1–5)
  - `hall_2.htm` — 2 photos (Hostel6–7)
  - `csea.htm`, `up_association.htm`, `pongopal.htm` — placeholders
  - `expeditions.htm` — 3 photos (Hostel8, Varanasi, Pic3)
- `gwu.htm` — Foggy Bottom placeholder

#### Places section
- `workplaces.htm` — Karma Kshetra landing page (6 chapters)
  - `cmc.htm` — CMC Limited (1992–1995) with sub-pages
    - `life_in_maroda.htm` — 6 photos (Bhilai1–6)
    - `the_picnic.htm` — 23 photos (Picnic01–23)
  - `sweatshop.htm`, `microsoft.htm`, `caravel.htm`, `enslaver.htm`, `digital_agency.htm` — placeholders
- `calcutta.htm` — Project Calcutta landing page
  - `calcutta_history.htm` — history index (7 chapters)
  - `calcutta_history1.htm` — East Meets West
  - `calcutta_history2.htm` — Charnock's Folly
  - `calcutta_history3.htm` — The Hon'ble Company
  - `calcutta_history4.htm` — Rule Britannia
  - `calcutta_history5.htm` — The Grand Old Lady
  - `calcutta_history6.htm` — New Horizons
  - `calcutta_history7.htm` — A Reckoning (2026 critique of colonial framing)
- `around.htm` — Around the World (84 countries by 2026, placeholder with counter)
- `passage_to_india.htm`, `passage_to_america.htm` — placeholders
- `bhilai.htm` — redirect to cmc.htm

#### Interests
- `links.htm` — Interests & Links (substantially updated 2026)

---

## Key conventions

### Datestamps
Every page footer and article includes a datestamp. Format:
- Original content: `Originally written [Month Year] · Restored 2026`
- Updated content: `Originally written [Year] · Substantially updated 2026`
- New content: `Written 2026`
- Phase 2 placeholder: `2026`

### Privacy
- Family members referenced by first name/nickname only (no surnames)
- No addresses, phone numbers, or identifying details for living family
- Children (Mini/Arpita, Pronoy) treated with extra care — they are now adults
- Wife (Tanu/Meenakshi) — same care
- Historical photos of interiors (Sterling house) are fine
- Baby/childhood photos of children not included on public site

### Placeholders
Placeholder pages use this consistent note:
```
This section is being written up. Check back shortly.
```
Phase 2 placeholders (workplaces, richer content) use more evocative teasers that capture the voice of the content to come.

### Time capsule framing
The original 2005 content is preserved as written, framed as a historical document. Where the worldview has changed (e.g. Calcutta history's colonial framing), a new section is added rather than the original being deleted.

---

## Family reference (important — get these right)
- **Thamma** — grandmother
- **Ma** — mother
- **Babali** — father
- **Jamu** — uncle
- **Mamon** — aunt
- **Tanu** (Meenakshi) — wife
- **Mini** (Arpita) — daughter
- **Pronoy** — son
- **Gagga** — sister

---

## Phase 2 priorities
1. **Family memoir pieces** — each family member page needs a proper essay
2. **Workplaces** — CMC, Sweatshop Decade, Microsoft (2007–2020), Caravel Labs, Enslaver Phases, Digital Agency Project
3. **Calcutta Chapter VII** — expand the reckoning
4. **Around the World** — travel writing for 84+ countries
5. **Food essays** — cooking and dining
6. **CSEA Friends** — the Prasit/NC Sahoo story email is already saved
7. **Pongopal** — Bengali Association at REC
8. **Photo enhancement** — AI upscaling of low-res scanned images
9. **Ashburn VA** — the long chapter, 2005–present
10. **Manila** — the gilded cage, 2024–2025

---

## What NOT to do
- Do not use Inter, Roboto, Arial or system fonts
- Do not use purple gradients or generic AI aesthetics
- Do not add addresses, phone numbers or sensitive personal information
- Do not change the `.htm` extension convention (except `index.html`)
- Do not break the breadcrumb navigation hierarchy
- Do not use dark backgrounds (the site is light/paper-toned throughout)
- Do not remove datestamps
