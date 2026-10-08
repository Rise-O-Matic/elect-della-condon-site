# Elect Dr. Della Condon: committee website

One static page for the Committee to Elect Della Condon (FPPC ID #1390909), San Gorgonio
Pass Water Agency, Director Area #4, election of November 3, 2026.

- `index.html` holds the page and its styles. Copy comes from the approved scripts in
  `C:\GitHub\della-condon-campaign-videos\docs\scripts.md`.
- `assets/` holds the portrait, the traced "Elect" lockup, the favicon and the share image.
  Brand source: `X:\My Drive\Projects\Della Condon\brand\`.
- The three campaign videos are 720x900 web encodes of the feed finals in
  `X:\My Drive\Projects\Della Condon\Campaign Videos\renders\` (`-crf 27`, `+faststart`), each
  with a poster frame.
- "Latest from Della" shows the three most recent daily Facebook posts. `POSTS` in
  `index.html` lists all 27 (Oct 7 to Nov 2) with their Facebook links, and a short script shows
  the ones already up (8:00 AM Pacific on their date). Thumbnails in `assets/posts/` are made
  from `facebook-page/cards/`. The page loads no Facebook code.
- Type is Poppins from Google Fonts. Palette: red `#DF3E2F`, navy `#252231`, sky `#43A5DE`.

The page exists so Meta can verify the committee's "Paid for by" disclaimer: the
disclaimer's website and email must share a domain. Intended domain: `electdellacondon.com`,
served by GitHub Pages, with `info@electdellacondon.com` forwarding to Steven.

Preview locally:

```bash
python -m http.server 4173
```
