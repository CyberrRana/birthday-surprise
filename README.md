# Birthday Surprise 🎀

A cute, interactive birthday surprise website in a soft 3D claymorphism style, made for Swagatika.

**Live site:** https://cyberrrana.github.io/birthday-surprise/

## Personalize

Open `index.html` and change the names in one place:

```js
const CONFIG = {
  name: 'Swagatika',              // her name
  loveName: 'My Love Swagatika',  // birthday screen + finale
  dearName: 'Dear Swagatika',     // wish heading + closing spell
  from: 'Your Love'               // letter signature
};
```

Her name is spelled out letter-by-letter on the birthday screen and in the finale, and the letters also float up out of the gift and the final hug.

## What's inside

1. Gift-box landing screen with confetti opening and floating name letters
2. Birthday celebration with an animated name reveal, a two-tier clay cake (dripping frosting, sprinkles, berries and glowing candles) and floating balloons
3. Three love cards (reminder / wish / virtual hug)
4. Blow-the-candles wish interaction
5. Envelope with a handwritten letter
6. Final section with four tappable friends, each with its own animation:
   - 🧸 teddy — wiggles and sheds hearts
   - 🌸 flower — spins and bursts petals
   - 💗 heart — beats and rains love
   - 🎁 gift — pops with confetti

Built with plain HTML, CSS and JavaScript — no build step, no dependencies, mobile-first, and `prefers-reduced-motion` friendly.
