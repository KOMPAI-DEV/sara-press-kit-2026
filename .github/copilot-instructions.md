# EPK Project — Copilot Instructions

Act as an expert frontend developer and UX designer working on a minimalist, single-page Electronic Press Kit (EPK) for a debut female pop artist.

## Design Rules

- Mobile-first, responsive, elegant — less is more
- Dark mode by default: near-black background, crisp white typography
- Ample whitespace throughout
- Semantic HTML5 tags always
- Do NOT add empty sections (no Tour Dates, no Awards, no Press Reviews — debut artist)

## Tech Stack

- Plain HTML5 — single self-contained `index.html`
- Tailwind CSS via CDN `<script>` tag — no build step, no external files

## Page Structure (4 sections only)

### 1. HERO
- Bold large header with Artist Name
- Short micro-headline (e.g. "Alt-pop from Stockholm for late nights")
- Prominent CTA button "Listen to [Single Title]" linking to Spotify

### 2. BIO & INFO
- Biography text block, 50–80 words
- Flat 3-item list (no nesting):
  - **For fans of:** [Reference 1, Reference 2]
  - **Debut single:** "[Title]" — [Release date]
  - **Vibe/Theme:** [Short description of sound and aesthetic]

### 3. PRESS MEDIA
- Responsive image grid with 4 placeholders:
  - 1 vertical press photo
  - 1 horizontal press photo
  - 1 portrait press photo
  - 1 single cover art
- Caption: "All images are high-res and cleared for press use."

### 4. CONTACT & LINKS
- "Management / Press Contact: [Name] — [Email]"
- Minimalist links for Spotify, Instagram, TikTok

## Artist Details (fill in as confirmed)

- **Artist name:** Sara
- **Single title:** TBD
- **Spotify URL:** TBD
- **Press contact:** TBD
