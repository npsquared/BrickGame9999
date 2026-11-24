# Brick Game 9999

A falling-bricks game drawn on a recreation of the LCD screen from the old "9999 in 1" pocket handhelds: a 10×20 brick grid, seven-segment score digits, the coffee-cup pause icon and square-wave beeps.

**Play:** https://npsquared.github.io/BrickGame9999/

Everything is in one self-contained file, `index.html`. It has no dependencies or build step, so you can also just open it in a browser.

## Controls

| Keyboard | Touch | Action |
| --- | --- | --- |
| ← → | Drag sideways | Move |
| ↓ | Drag down | Drop faster |
| ↑ or Space | Tap the playfield | Rotate |
| Enter | Tap the right panel | Start, pause, resume |
| M | Tap the ♪ icon | Sound on/off |
| R | Swipe up while paused | Reset to the title screen |

On the title screen, ← → (or swipe sideways) sets the **level**: each level above 1 starts with one more row of junk. ↑ ↓ (or swipe up/down) sets the **speed** from 1 to 10. Every 10 lines cleared adds one to the speed.

Points: 100 for 1 line, 300 for 2, 700 for 3, 1500 for 4. The hi-score is kept in your browser.
