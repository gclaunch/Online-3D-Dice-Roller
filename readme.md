# Online 3D Dice Roller
## Roll some dice here: https://gclaunch.github.io/Online-3D-Dice-Roller/
* Add modifiers by typing your desired notation and including `+` or `-` with your number. For example: `2d6 + 10` will add `10` to the output.
* Fudge rolls by typing your desired notation and including `@` with desired results. For example: `4d4 @ 1 1 1 1` will output all `d4` dice values to be `1`.

Set up a pre-roller with query strings:
* Auto-set notation: https://gclaunch.github.io/Online-3D-Dice-Roller/dice/?notation=4d6
* Auto-roll notation: https://gclaunch.github.io/Online-3D-Dice-Roller/dice/?notation=4d6&roll
---

Project can be downloaded and used stand-alone. Needs internet connection for random.org API.

To run, open `dice/index.html` with your browser.

* It uses three.js for 3d and cannon.js for physics.
* It also uses random.org to produce true random numbers (from atmospheric noise).
* dice.py is a GAE serverlet that makes proxy requests to random.org API.
