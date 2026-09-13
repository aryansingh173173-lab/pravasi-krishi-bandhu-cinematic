# Pravasi Krishi Bandhu: cinematic website

The cinematic presentation with the corrected bilingual v2 content from [BKS-Bengal/pravasi-krishi-bandhu](https://github.com/BKS-Bengal/pravasi-krishi-bandhu), source commit `018c0ca` (the upstream `cinematic/` build).

## Content authority

Read [FACTS.md](FACTS.md) before changing programme copy or numbers. Fetch upstream before starting content work and compare its latest FACTS.md and cinematic build. Later dated rulings supersede earlier provisional notes.

The website includes the 90% farm / 6% prize / 2% operations / 2% administration split, the 2026–2028 roadmap, the revised awards timeline, an interest-first form, and the supplied bilingual 80G/FCRA notice. Do not remove or weaken that notice.

## Run locally

Requires Node.js, with no package installation:

```sh
node serve.cjs
```

Open [the local website](http://127.0.0.1:8000/).

## Static deployment

The website lives in `pravasi-krishi-bandhu/`. For Vercel, select that folder as the Root Directory, use the Other framework preset, no build command, and `.` as the Output Directory.

## Presentation and behaviour

- The original KRL video remains the muted, looping hero background; cinema.js and serve.cjs are unchanged.
- The sticky header keeps the English/Bengali switch available while scrolling.
- Video controls and the decorative top line remain removed.
- Reduced-motion and data-saving preferences are respected.
- The interest form opens the reader's email app. It does not send automatically, collect payment, or store submissions on a server.
- The East Kolkata Wetlands visual is an illustrative rendering, labelled as such. The empty ancestral-home photograph card has been removed; explanatory videos remain explicitly marked as pending.

Other documents retained in this fork may describe earlier drafts; FACTS.md and the corrected website are the content reference.
