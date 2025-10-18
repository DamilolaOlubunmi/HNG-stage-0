# Profile Card — Minimal Frontend Widget

A small, single-page profile card demo that shows a user avatar, name, bio, social links, hobbies/dislikes and a live current time (in milliseconds).

Files
- [HNG Stage 0/profileCard.html](HNG Stage 0/profileCard.html) — Main HTML markup and test-friendly attributes (data-testid).
- [HNG Stage 0/profileCard.css](HNG Stage 0/profileCard.css) — Styles: responsive, glass-like card layout.
- [HNG Stage 0/profileCard.js](HNG Stage 0/profileCard.js) — Script that updates the clock.

Key symbols
- [`timeElement`](HNG Stage 0/profileCard.js) — DOM reference to the time <span>.
- [`updateTime`](HNG Stage 0/profileCard.js) — Function that writes Date.now() into the time element and is invoked every second.

How it works (concise)
- Open [profileCard.html](HNG Stage 0/profileCard.html) in a browser.
- The layout and visual styling come from [profileCard.css](HNG Stage 0/profileCard.css).
- The live clock is implemented in [profileCard.js](HNG Stage 0/profileCard.js): `updateTime` sets the element text to the current epoch milliseconds using `Date.now()` and `setInterval` calls it every 1000 ms.

Run locally
1. Place the three files together (already in this folder).
2. Open [profileCard.html](HNG Stage 0/profileCard.html) in any modern browser (no build step or server required).

Notes
- HTML includes `data-testid` attributes to facilitate automated tests.
- Styling uses simple responsive rules and a backdrop blur for a modern card look.
- The time shown is in milliseconds (epoch) for demonstration; replace with formatted time if needed.

License / attribution
- Small demo project intended for learning or portfolio use. Modify freely.