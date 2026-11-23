# Chromatic Engine II

A live Sun and Moon dial on a 26-letter wheel.

- **Sun letter:** the Sun's compass bearing (azimuth) at your chosen location.
- **Moon letter:** the Moon's phase angle. New Moon sits at 180° and Full Moon at 0°.
- **Midpoint:** a green diamond on the degree ring, halfway between the Sun and the Moon along the shorter way around.
- **Sky Tones:** soft ambient music made from the dial. The Sun's letter sets the key and the low drone, the Moon's letter sets where the bell chimes play, and the midpoint adds a middle tone. Press "Play sky tones" to start it, since browsers need a click before a page can play sound.
- **Find a Time:** finds when the Sun or Moon will reach a chosen letter or degree, with a "Show on dial" button for each result.

## Running it

Open `index.html` in any web browser. The whole app is in that one file.

The sky calculator is built into the page, so it works without an outside website. If the built-in copy ever fails to start, the page loads the same version from jsDelivr as a backup.

The Builder's Notes section works only when the page is opened in Claude. Everywhere else, the rest of the app works normally.

## Credits

Sky calculator: [Astronomy Engine](https://github.com/cosinekitty/astronomy) 2.1.19 by Don Cross, MIT License. Its license notice is kept inside `index.html`.
