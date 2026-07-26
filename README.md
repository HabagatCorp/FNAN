# 🕯️ 5 Nights at Nasha's

A tiny FNAF-style browser game made as a monthsary gift.

**Only 3 files, no folders needed:** `index.html`, `style.css`, `script.js`.
All images are embedded directly as base64 inside `script.js`, and all
audio is generated live with the Web Audio API — nothing external to
break on upload.

## How to deploy on GitHub (from your phone)
1. Create/open your repo.
2. **Add file → Upload files**.
3. Select all 3 files (`index.html`, `style.css`, `script.js`) at once.
4. Commit.
5. Settings → Pages → deploy from the `main` branch → save.
6. Visit `https://<yourusername>.github.io/<reponame>/`.

That's it — no subfolders, no renaming, no path issues possible.

## Premise
Survive 5 minutes in the office. Sanity drains constantly — call Brent
to refill it. Check the tablet's CCTV feeds if you dare (purely for
vibes — and jumpscares). If Sanity hits 0%, Nasha finds you.

## Tweaking
Open `script.js` and edit the constants near the top:
- `GAME_LENGTH_SEC` – how long a night lasts
- `CALL_REFILL_AMOUNT` – how much sanity a call to Brent restores
- `CALL_COOLDOWN_SEC` – cooldown between calls

Made with 💛 for Nasha.
