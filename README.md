# bukvuk-packs

Content packs for **БУКВУК** (kids word-building game), served as static
files over GitHub Pages: `https://alagerty.github.io/bukvuk-packs/manifest.json`.

The app checks `manifest.json` after launch; a newer `version` than the
bundled/installed pack is downloaded, sha256-verified and installed for the
next launch. Published from the main repo with
`python3 tools/build_packs.py --version N --publish` — never edit by hand.
