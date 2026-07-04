# Ali Shahroor — Portfolio

A single-page academic portfolio. Pure HTML/CSS/JS — no build step, no cost.
Host it free as your GitHub Pages site (see `../DEPLOY.md`).

**Live site:** https://alishahroor.github.io/

## Edit your details

- **Profile links:** open `index.html`, find the `PROFILE` block near the bottom
  (inside `<script>`), and update Google Scholar, LinkedIn, GitHub, Hugging Face,
  or email in one place. Every link on the page reads from this one object.
- **CV:** replace `CV.pdf` with your latest file (keep the name `CV.pdf`).
- **Photo:** replace `assets/img/profile.jpeg`.

## What's on the page

Hero/bio · stats · research areas · selected publications · paper summaries ·
experience & education timeline · certifications · awards · languages · projects ·
skills · contact. Includes a dark/light theme toggle and scroll animations.

## Publications note

The page has two publication areas:

- **Selected Publications:** compact citation-style entries with BibTeX where available.
- **Paper Summaries:** short plain-language summaries based on the PDFs in
  `/Users/alishahrour/Desktop/Personal/My_Papers`.

If any detail here is wrong, edit `index.html` in the Publications section.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole page + inline script. |
| `assets/css/style.css` | Styling. |
| `assets/img/profile.jpeg` | Your photo. |
| `CV.pdf` | Your downloadable CV. |
