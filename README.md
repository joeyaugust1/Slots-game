# CannaBus Slots Game

A visually rich slot machine game themed around cannabis culture and classic slot symbols. Built with HTML, CSS, and JavaScript—playable right in the browser!

## Features

- **3×3 Slot Grid:** Three reels, three rows.
- **Paylines:** Up to 5 selectable paylines, each with a unique color.
- **Animated Reels:** Smooth spinning animation for each reel.
- **Symbol Set:** Includes classic card faces (Ace, King, Queen), weed-themed icons, and more.
- **Payout Table:** Clearly shows symbol payouts and probabilities.
- **Interactive UI:** Select bet amount, number of paylines, and spin.
- **Winning Highlights:** 
  - Winning paylines are brightly colored.
  - Winning symbols are highlighted with a gold border.
- **Balance Tracking:** Play with a virtual balance.
- **Sound Effects:** (Ready to be added! See below.)

## Screenshots

![Slot machine with colored paylines](image1)
![Multiple paylines demonstration](image2)

## How to Play

1. **Set your bet amount** using the dropdown.
2. **Choose the number of active paylines** (up to 5).
3. Click **SPIN** to play!
4. If you win, your balance increases and winning lines/symbols are highlighted.

## Customization

- **Payline Colors:** Red, Blue, Green, Orange, Purple.
- **Symbol set and payouts** can be modified in `index.html` JavaScript.
- **Sound Effects:**  
  Add audio files for reel spins, wins, jackpots, etc. See [Where can I get sound effects for the pokies/slots machine?](#sound-effects) below.

## Adding Sound Effects

You can add sound effects to enhance the gaming experience. Good sources include:
- [Freesound.org](https://freesound.org/)
- [Pixabay Sound Effects](https://pixabay.com/sound-effects/)
- [Mixkit](https://mixkit.co/free-sound-effects/)
- [ZapSplat](https://www.zapsplat.com/)
- [AudioJungle](https://audiojungle.net/) (paid)

To add sounds:
1. Download your desired `.mp3` or `.wav` files.
2. Place them in the `assets/` folder.
3. In your `index.html`, use JavaScript to play sounds on spin/win/jackpot events, e.g.:
   ```javascript
   let spinSound = new Audio('assets/spin.mp3');
   spinSound.play();
   ```

## File Structure

```
index.html         # Main game file
assets/            # Image and sound assets
README.md          # Project documentation
```

## License

This project is open source. Please check individual asset licenses before distributing.

---

**Created by [joeyaugust1](https://github.com/joeyaugust1)**
