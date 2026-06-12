# 🪐 Planet Spelling — Sounds & Letters

A space-themed phonics + spelling game for toddlers. For each planet the child:

1. **Hears the name broken into sound-parts** (syllables) — e.g. *Jupiter =
   Ju‑pi‑ter*, *Mer‑cu‑ry*, *Sa‑turn*. Tap any part to hear just that sound.
2. **Spells the planet** by picking the next letter from three choices.

The letters in the spelling row are **colour-matched to the sound-parts**, so the
child can see which letters make each sound. Finishing a planet brings stars,
confetti, and the name read aloud.

Live link: **https://clingck.github.io/python-binance/planets/**

## Designed for little learners

- **No internet or install needed** — one HTML file, works offline.
- **Original cartoon planets** drawn as SVG (colours, bands, Saturn's rings) — no
  copyrighted artwork.
- **Reads everything aloud** with the browser's built-in speech; phonetic hints
  make each part sound natural ("joo‑pih‑ter").
- Goes in order from Mercury outward, so it doubles as a little solar-system tour
  (Pluto included as a bonus "dwarf planet").
- Big, touch-friendly buttons; forgiving — wrong taps just say "Try again".

## Run it locally

Open `index.html` in any browser, or serve it:

```bash
cd planets-spelling-app
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Customize

Edit the `PLANETS` list near the top of the `<script>`. Each entry has the word,
planet colours, `chunks` (how the name is split into sound-parts), and `say`
(phonetic hint for each part). The chunks must join to spell the full word.
