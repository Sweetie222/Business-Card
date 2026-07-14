# Free editable QR contact card

Two files, no subscription:

- **`index.html`** — your contact page (the thing clients land on). Edit the `CARD = {...}` block at the top with your real info. This is what you change whenever your details change.
- **`qr.html`** — a QR designer. Encodes a link, styles it (dots, eyes, color, logo), downloads PNG/SVG.

## One-time setup (free hosting = editable forever)

1. Create a free GitHub account, make a new **public** repo (e.g. `card`).
2. Upload `index.html` to it.
3. Repo **Settings → Pages → Deploy from branch → main → /(root)**. Save.
4. In ~1 minute your page is live at `https://YOURUSER.github.io/card/`.

## Make the QR

1. Open `qr.html` (double-click).
2. Paste your GitHub Pages URL into **"Link the QR opens"**.
3. Style it, optionally drop a center logo, **Download PNG** (print) or **SVG** (large signage).

## To change your info later

Edit the `CARD` block in `index.html`, re-upload it to GitHub. **Do NOT regenerate the QR** — the printed code still points to the same URL, it just serves your new info. That's the "edit anytime" feature you wanted, for $0.

## Why this beats the paid version for you
- Clients scan one stable code ✔
- You edit content anytime ✔
- No monthly fee, no expiry ✔
- Trade-off: no built-in scan analytics (add free Cloudflare Web Analytics to `index.html` if you ever want counts).
