# Ali Shahroor — Portfolio

A single-page academic portfolio. Pure HTML/CSS/JS — no build step, no cost.
Host it free as your GitHub Pages site (see `../DEPLOY.md`).

**Live site:** https://alishahroor.github.io/

## Edit your details

- **Profile links:** open `index.html`, find the `PROFILE` block near the bottom
  (inside `<script>`), and replace the `REPLACE_ME` values for Google Scholar,
  LinkedIn, and Hugging Face. Every link on the page reads from this one object.
- **CV:** replace `CV.pdf` with your latest file (keep the name `CV.pdf`).
- **Photo:** replace `assets/img/profile.jpg`.

## What's on the page

Hero/bio · stats · research areas · **publications** (only your 5 real,
CV-verified papers) · experience & education timeline · certifications · awards ·
languages · projects · skills · contact. Includes a dark/light theme toggle and
scroll animations.

## ⚠️ Integrity note

An earlier version of this page listed several **publications that were not in
your CV and appear fabricated** (e.g. a "MemeLens" ACL 2026 paper, a WWW 2026
paper, and "CritiSense", with invented arXiv IDs). Those were **removed** — a
public academic page with fake papers is a serious reputational risk. The page
now lists only the five real publications from your CV:

1. **MemeIntel** — EMNLP 2025
2. **PropXplain** — Findings of EMNLP 2025
3. **LlamaLens** — Findings of NAACL 2025
4. **Native vs Non-Native Language Prompting** — WISE 2024
5. **EverydayMMQA** — preprint

If any detail here is wrong, edit `index.html` (the Publications section).

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole page + inline script. |
| `assets/css/style.css` | Styling. |
| `assets/img/profile.jpg` | Your photo. |
| `CV.pdf` | Your downloadable CV. |
