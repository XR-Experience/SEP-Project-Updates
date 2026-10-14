# XR Experience Updates

SEP updates repo

### What's inside
```
[Year]_[Month] (e.g 2025_03 for March 2025)
│── README.md # Update Documentation
└── README.pdf  # PDF version of the README
```
### Website
The updates are published as a GitHub Pages site (`index.html`). To add a new update to the site, create the `[Year]_[Month]` folder as usual, then add an entry to the top of `updates.json`:
```json
{ "folder": "2026_11", "title": "November 2026", "summary": "One-line summary shown on the home page." }
```
Add `"pdf": "2026_11.pdf"` if the folder has a PDF version.
