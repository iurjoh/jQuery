# jQuery selectors and cards

[Português (Brasil)](README.pt-BR.md)

## Idea and process

Educational source reviewed on 2026-10-01. No dated plan, wireframes or personal development diary was found in the reviewed files. This README records the implemented exercise without inventing process history. No backend or database is part of the reviewed structure.

## Architecture and design

cards-jquery.html loads jQuery 3.2.1, style.css and script.js. Stream controls actively highlight matching cards. statements.js is a separate console walkthrough of selectors, CSS, HTML/text replacement and append; it is not loaded by the page. CSS uses flex cards and a 700px navigation breakpoint. The HTML uses img/ paths while the root listing contains images/, so image references need review.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/cards-jquery.html`. No package install is required by the reviewed static files; external fonts/libraries need network access. This command was not run in the documentation update.

## Testing and limitations

No automated test suite was found in the reviewed root listing. Browser behavior was not tested and no public deployment was verified here. Test stream selection, image paths, narrow layouts and keyboard access. Console statements are independent examples: running the body.html replacement removes the fixture. The final my_footer selector lacks # for the ID. Do not copy unsafe HTML insertion patterns into untrusted-content workflows.

## Snapshots

No application screenshot was verified or added. Future captures should use dated files under `docs/assets/`, cover initial and changed states on desktop/mobile, and be labeled as a lesson fixture. Add links only after the images exist.

## Credits and licensing

The page uses Code Institute lesson text and branding. Preserve third-party code, images and library rights. No new license is applied. The original README is retained below as historical reference, not current setup advice.

---

## Original README


Bootstrap CSS version 4.6.2 link:
https://getbootstrap.com/docs/4.6/getting-started/introduction/#quick-start
Bootstrap Font Awesome version 4.7.0 link:
https://codepen.io/mosbth/pen/qBEeJpg
