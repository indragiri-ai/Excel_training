# The Excel Workbook — Course Guide, Shortcuts & Formula Generator

A single-file, self-contained website for your BBA & MBA students. It works completely in the browser — no server, no build step, no API keys. You can open `index.html` by double-clicking it, or host it free on GitHub Pages.

## What's inside
- **Home** — overview and quick links, with a live formula-bar animation.
- **Course Guide** — every topic you taught, step by step, tagged **BBA** / **MBA** with a track filter and search. Click any lesson to expand it (what it's for, steps, example formula, and a "watch out" note).
- **Shortcuts** — keyboard shortcuts sorted by category, with a **Windows / Mac** toggle and search.
- **Tips & Tricks** — 15 practical habits as cards.
- **Formula Generator** — the signature feature. Students describe their goal, fill in a few details, and get the exact formula with a plain-English explanation, a "where to type it" note, and a one-click copy. A smart search box routes plain questions to the right builder. Covers VLOOKUP, XLOOKUP, INDEX/MATCH, SUMIFS, COUNTIFS, AVERAGEIFS, IF, IFERROR, and text cleaning / combining / extracting.

## Host it on GitHub Pages (free)
1. Create a new repository on GitHub (e.g. `excel-workbook`).
2. Upload `index.html` to the root of the repo (drag-and-drop works).
3. Go to **Settings ▸ Pages**.
4. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
5. Wait about a minute — your site will be live at
   `https://<your-username>.github.io/<repo-name>/`
6. Share that link with your students.

That's it. Any time you edit `index.html` and push the change, the site updates automatically.

## How to update the content
All the content lives in plain JavaScript arrays near the top of the `<script>` section in `index.html`, so you can edit it without touching the design:
- `LESSONS` — add or edit course topics (title, track, steps, example, watch-out).
- `SC` — shortcuts, grouped by category (each has Windows and Mac keys).
- `TIPS` — the tips cards.
- `RECIPES` — the formula-generator builders.

Set a lesson's `track` to `"bba"` to show it for both tracks, or `"mba"` to show it only under MBA.

## Add your own teaching materials
Send me the files you used in class and I can fold your exact examples, screenshots, and sample datasets into the matching lessons — so it mirrors precisely how you taught it.
