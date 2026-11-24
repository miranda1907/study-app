# IICS Technical Assessment — 12 Versions

Static GitHub Pages site: **Open-ended 1–6** and **Multiple-choice 1–6**, 20 questions each
(8 Beginner, 8 Moderate, 2 Advanced, 2 Expert). No answer keys or grading included.

## How it works

- Candidate enters a name, picks a version, and answers one question per screen.
- On submit, `.txt` and `.json` files download automatically. Nothing is sent to a server.
- Progress is saved in the browser (local storage) and survives refreshes. It is cleared only by **Back to start**.
  On shared computers, click **Back to start** when done.

## Deploy

Upload `index.html`, `styles.css`, `app.js`, `README.md` to a GitHub repo, then Settings → Pages → `main` / root.
After updates, hard refresh (Ctrl+Shift+R) and bump the `?v=` number in `index.html`.

## Customize

Edit `QUESTION_BANK` in `app.js`. Do not add answer keys to this public repo.
