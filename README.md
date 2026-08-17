# hudson-radfx

Personal landing page — links to research sites and contact info.

## Publishing on GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → branch `main`, folder `/ (root)`.
Plain HTML/CSS, no build step. Fonts load from Google Fonts.

## Local preview

```bash
python3 -m http.server 8731
```

Then open <http://localhost:8731>.

## Before publishing

- Add `images/headshot.png` (referenced by `index.html`, not yet in the repo).
- Add more testing-setup photos to `images/` as `setup-2.jpg`, `setup-3.jpg`, etc.,
  and uncomment the matching `<figure>` blocks in the "Test setups" section of `index.html`.
- `images/setup-1.jpg` and the IU/CREATE logos are copied over from the NSREC companion
  site (`isahuds/NSREC-26-Hudson`) as a starting point — swap or add to them as needed.
