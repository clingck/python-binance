# 🐾 Spell the Animals!

A simple, colorful spelling game for young children. The child sees a picture of
an animal and spells its name by tapping the **correct next letter from three
choices**. When the word is finished, the animal bounces, confetti flies, and
the word is read aloud. 🎉

## How to play

1. An animal picture appears (e.g. 🐶) with empty letter boxes below it.
2. Three big letter buttons are shown. The child taps the letter that comes next.
3. A correct letter fills the box and turns green; a wrong letter wiggles and the
   child can try again — nothing is ever "lost".
4. Finish the word to earn a star ⭐ and move to the next animal.
5. Spell every animal to reach the big celebration screen, then **Play Again**.

## Features

- **No setup, no internet needed.** Everything is in one file using emoji
  pictures — works offline in any modern browser.
- **Reads words aloud** using the browser's built-in speech (tap the picture or
  the 🔊 *Say it* button). Falls back gracefully if speech isn't available.
- **Forgiving for little learners** — wrong taps just say "Try again 💪".
- **Big, touch-friendly buttons** that work great on a tablet or phone.
- 34 animals, from `cat` to `elephant`, shuffled into a fresh order each round.

## Run it

Just open `index.html` in any web browser — double-click the file, or:

```bash
# optional: serve it locally
cd animal-spelling-app
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customize the animals

Open `index.html` and edit the `ANIMALS` list near the top of the `<script>`:

```js
var ANIMALS = [
  { word: "cat", emoji: "🐱" },
  { word: "dog", emoji: "🐶" },
  // add your own: { word: "shark", emoji: "🦈" },
];
```

Keep the words lowercase and the emoji a single picture, and they'll show up in
the game automatically.
