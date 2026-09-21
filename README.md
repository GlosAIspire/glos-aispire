# Glos AIspire

The website for Glos AIspire — Gloucestershire's first AI network for women.

## What this is

One self-contained `index.html`. No framework, no build step, no dependencies,
no JavaScript. Every image is embedded as a base64 data URI, so the page works
opened straight from disk with no internet connection.

## Editing

Open `index.html` in any editor. The sections are numbered in HTML comments, in
the order they appear on the page.

Meeting summaries, case studies and member cards each have a commented-out
template in the file, with a note above it explaining how to fill it in. Member
photos are embedded too: a square 264×264 JPEG of around 18 KB. Two rules apply
to all of them:

- **No names in meeting summaries.** "One member brought…", never a name.
- **Consent first**, for member cards and case studies. Nobody appears until she
  has read what will be published and said yes. A case study can identify
  someone even without a name, and may involve her employer.

Colours, type and contrast are documented in comments at the top of the
stylesheet. Every piece of text on the page clears 7:1 contrast (WCAG AAA). If
you change a colour, re-measure — the accent has very little headroom.

## Deploying

Push to `main`. GitHub Pages serves the site from the repository root, at
https://glosaispire.github.io/glos-aispire/. If that address ever changes,
update the three social-preview URLs at the top of `index.html` to match.
