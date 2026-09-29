# Delivered in parts — unzip all into the SAME folder

Unzip all parts into one location; they merge into a single `pp-u2-student-site/` folder.

---

# Promise & Practice — Unit Two (STUDENT edition)

Self-contained, offline-ready GitHub Pages site for students. `index.html` is the student
hub (no teacher resources). The summative exam is password-locked.

## Deploy (one repo)
1. Create a repository (e.g. `pp-u2-student-sds-v1.0.0`).
2. Upload the entire contents of this folder to the repo root (keep the folder structure
   and every `.nojekyll` file).
3. Settings → Pages → Deploy from a branch → `main`, folder `/ (root)`. Save.
4. Live at `https://shadowdogstudios-web.github.io/<repo-name>/`.

## The locked exam (`assessment/`)
Encrypted — content is not readable in the source until a correct password is entered.
Any ONE unlocks it (case-sensitive); give a different one to each period:

    Period 1  GrowthConflict
    Period 2  PromiseAndPractice
    Period 3  NewBirth1863
    Period 4  UnionForever65
    Period 5  ShadowDog2026

Unlock uses the browser's Web Crypto API — needs the page served over the web (https, as
GitHub Pages does) or localhost; a raw file:// open shows an "open over the web link" message.

## What's here
- `index.html` — the student hub.
- `book/` — the full flipbook.
- `music/` — The Music of the War (scrolling listening page) + `interrogate-the-anthem.html`.
- `music-carousel/` — the slide/carousel version of the music presentation (activity built in).
- `songs-of-the-enslaved/` — the guided showpiece.
- `gettysburg/`, `gettysburg-dark-romanticism/`, `sherman/` — deep dives.
- `ch01/` … `ch10/` — chapter modules.
- `assessment/` — the password-locked summative.
- `about/`, `black-hawk-*/` — the studio's other pieces.

© ShadowDog Digital Studios
