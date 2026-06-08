# 🔤 Sound Play — Learn Letters & Sounds

A colorful, no-setup phonics app for toddlers and early readers. The child learns
letter **sounds** (not just names), tricky **letter combinations**, and practices
**spelling** — all by tapping, listening, and playing. Everything reads aloud,
celebrates with stars and confetti, and uses big touch-friendly buttons.

Live link (open on a phone/tablet): **https://clingck.github.io/python-binance/**

## Activities

1. **🔤 Letter Sounds** — A–Z. Tap the big letter to hear its *sound* ("mmm",
   "sss"), with a picture + example word (m → 🌙 moon). Swipe through with the
   arrows or jump around with the alphabet strip.
2. **🔡 Sound Combos** — the letter combinations from the phonics chart
   (`ar, ir, ur, or, er`) plus common digraphs (`sh, ch, th, oo, ee, ai`), each
   with example words and pictures. Includes a **listening game**: hear a sound,
   tap the matching combo.
3. **🎧 Sound Match Game** — hear a letter sound and tap the correct letter from
   three choices. The most effective way for a toddler to actively learn sounds.
4. **🐾 Spell the Pups** — spell rescue-pup and animal names by choosing the
   correct next letter from three options. Finish a word for a star + confetti.

## Designed for little learners

- **No internet or install needed** — one HTML file, emoji pictures, works offline.
- **Reads everything aloud** using the browser's built-in speech.
- **Forgiving** — wrong taps just say "Try again / Listen again", nothing is lost.
- **Big buttons**, bright colors, instant rewards (stars + confetti).

## A note on the rescue pups

The "Spell the Pups" pack is a fan-style nod to the rescue-pup theme kids love —
each pup is shown with a dog emoji and its job vehicle (🚓 police, 🚒 fire,
🚁 helicopter, etc.). It does **not** use any official Paw Patrol artwork,
logos, or images, since those are copyrighted; it's just the names as
spelling words with friendly emoji.

## Run it locally

Open `index.html` in any browser, or serve it:

```bash
cd animal-spelling-app
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Customize

Open `index.html` and edit the data lists near the top of the `<script>`:
`LETTERS` (letter sounds), `COMBOS` (letter combinations), and `ANIMALS`
(spelling words — including the pups). Keep words lowercase and emoji as single
pictures.
