# Wings — Little Rock, AR

Static, single-page website for **Wings**, a take-out wing shop in Little Rock, Arkansas.

- **Address:** 1423 West Roosevelt, Little Rock, AR 72206
- **Phone:** (501) 747-2121
- **Service:** Take-out only · Est. 1997

## How it works

The entire site is one self-contained file — [`index.html`](index.html). All styles,
runtime, and images are packed inside it (the page unpacks its images into Blob URLs at
load time), so there is **no build step and no external assets** required to run it.

Open `index.html` in any modern browser, or serve the folder with any static file server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Deployed as a **zero-build static site** on Vercel:

- Framework preset: **Other** (none)
- Build command: **none**
- Output directory: **repo root**
- Entry: `index.html`

`og-image.jpg` (1200×630) is the social-share card referenced by the Open Graph /
Twitter meta tags.
