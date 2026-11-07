# Free Christmas bingo card generator (one HTML file, nothing stored)

Make and print 1 to 30 different Christmas bingo cards in your browser, with a caller sheet. No sign-up, no server, no cookies, no build step: it is one `index.html` file.

**Use it now, no install:** [tchworks.co.uk/free/christmas-bingo-printable-2026](https://www.tchworks.co.uk/free/christmas-bingo-printable-2026/?utm_source=github&utm_medium=repo&utm_campaign=bingo-repo)

**Free printable PDF (no install):** [Download the A4 pack](https://github.com/wilsonryan-hue/christmas-bingo-generator/releases/download/v1.0.0-free-printable/christmas-bingo-printable-2026-free.pdf) — 4× 5×5 cards, 2× kids' 3×3, caller sheet ([release notes](https://github.com/wilsonryan-hue/christmas-bingo-generator/releases/tag/v1.0.0-free-printable)).

## What it does

- Three built-in lists: Christmas words (32), Christmas Day things that always happen (28) and Christmas film spotting (25). The same lists are in `lists.json`.
- Or paste your own list, one word or phrase per line (a family joke, a class topic, a film).
- 3 by 3 (young children), 4 by 4 or 5 by 5 grids, with an optional free space in the middle of 3 by 3 and 5 by 5.
- Every card in a set is checked so that no two are the same. If your list is too short to make that many different cards, it tells you.
- Four styles: red, green, midnight blue and a plain outline that saves ink.
- Prints two cards per A4 page, then a caller sheet with every word in random order and a tick box beside each.
- Typed text is escaped, so HTML in your own list is shown as text and never run.

## Use it

Open `index.html` in any browser, press **Make my cards**, then **Print cards and caller sheet**. To keep a copy, save the file; it works offline.

## Self-host

Put `index.html` on any static host (GitHub Pages, Netlify, a school intranet, a WordPress media upload). There is nothing to configure. To change the built-in lists, edit the `L` object near the end of the script (the file `lists.json` is a copy for reference).

## How to play

1. Give everyone a card and a pen, or counters such as buttons or dried pasta.
2. The caller reads the words from the caller sheet in order and ticks each one off.
3. Players mark any word they have. The first to complete a row, column or diagonal shouts Bingo.
4. Check the winner's squares against the ticked caller sheet.

For a class party, play a few rounds so everyone wins something. For a family afternoon, use the Christmas Day list and tick squares as they really happen.

## Free Gumroad download

Also free on Gumroad (instant download): https://tchworks.gumroad.com/l/rmbaok

## Licence

MIT. Made by [TCH Works](https://www.tchworks.co.uk/?utm_source=github&utm_medium=repo&utm_campaign=bingo-repo). The hosted version has more free Christmas tools, including [gift tags](https://www.tchworks.co.uk/free/christmas-gift-tags-printable-2026/?utm_source=github&utm_medium=repo&utm_campaign=bingo-repo) and a [Secret Santa generator](https://www.tchworks.co.uk/free/secret-santa-generator/?utm_source=github&utm_medium=repo&utm_campaign=bingo-repo).
