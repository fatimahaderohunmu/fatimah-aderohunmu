# Fatimah Adesola Aderohunmu — Portfolio Website

A lightweight, dependency-free portfolio site (HTML, CSS, vanilla JS) built for
job applications in communications, digital media, writing and editorial roles.

## Files

```
index.html            The whole site (one page, anchor navigation)
styles.css             All styling
script.js               Mobile menu + small behaviours
assets/
  Fatimah-Aderohunmu-CV.pdf   The CV shown on the Download CV buttons
```

## Status

All five items from the original checklist are now on the site: the "Beyond
the Ramp" essay (full text, under Writing Portfolio → Original Writing), the
Digital Content Sample, the fixed KnowIslam link, the LinkedIn button, and
the confirmed 2026 graduation year.

Nothing is currently outstanding. Add new published pieces or samples the
same way described below whenever you have them.

- **Replace the CV file** whenever your CV changes — see below.

## Updating your CV file

The Download CV buttons link to `assets/Fatimah-Aderohunmu-CV.pdf`. To
replace it:

1. Rename your new CV file to exactly `Fatimah-Aderohunmu-CV.pdf`.
2. Drop it into the `assets` folder, replacing the old one.
3. Keep the file name the same, or update the two `href` values in
   `index.html` that reference it (search for `Fatimah-Aderohunmu-CV.pdf`).

## Editing content

Everything is in `index.html`, organised into clearly labelled sections
(`<!-- WRITING PORTFOLIO -->`, `<!-- EXPERIENCE -->`, etc.). To add a new
published article, copy one `<article class="article-card">…</article>`
block inside `#writing` and edit the text and link.

## Publishing for free with GitHub Pages

1. Create a free GitHub account at [github.com](https://github.com) if you
   don't have one.
2. Create a new repository (top right → "New repository"). Name it anything,
   e.g. `fatimah-portfolio`. Make it **Public**. Don't add a README (you
   already have one).
3. On the new repository's page, click **"uploading an existing file"** and
   drag in `index.html`, `styles.css`, `script.js`, and the whole `assets`
   folder (with the CV inside it). Commit the changes.
4. Go to the repository's **Settings → Pages**.
5. Under "Build and deployment", set **Source** to **Deploy from a branch**,
   branch **main**, folder **/(root)**. Save.
6. Wait 1–2 minutes, then refresh the Pages settings page — it will show your
   live URL, something like:
   `https://your-username.github.io/fatimah-portfolio/`
7. Put that URL on your CV and LinkedIn.

Any time you edit a file in the repository (on github.com, or by re-uploading
it), the live site updates automatically within a minute or two.

## Alternative: Cloudflare Pages

If you'd rather use Cloudflare Pages: create a free account at
[pages.cloudflare.com](https://pages.cloudflare.com), choose "Upload assets"
(no GitHub needed), and drag in the same files. You'll get a
`*.pages.dev` URL immediately.
