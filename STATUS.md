# STATUS

## What was built

A beginner manual on eBay and Amazon reselling, published by Asdale Dynamics, LLC.

**Files**
- `README.md` — project overview; credits Asdale Dynamics, LLC
- `LICENSE` — MIT License, copyright line exactly `Copyright (c) 2026 Asdale Dynamics, LLC`
- `docs/manual.md` — full beginner manual: finding items to flip, writing listings, pricing, shipping supplies, eBay/Amazon fees, record keeping
- `docs/listing-checklist.md` — printable listing checklist
- `docs/profit-worksheet.md` — printable profit worksheet
- `static/index.html` — static HTML home page
- `static/manual.html` — full manual as HTML
- `static/checklist.html` — printable HTML checklist
- `static/worksheet.html` — printable HTML worksheet
- `static/styles.css` — shared styles with print media query
- `STATUS.md` — this file

## How to run it

It is a static site; no build step or server is required.

- Read the markdown in `docs/` directly, or open `static/index.html` in any browser.
- Print `static/checklist.html` or `static/worksheet.html` (Ctrl/Cmd + P) for the printable tools. The CSS includes a `@media print` sheet that hides navigation and formats the page for paper.

## Verification results

- All four HTML files parse without errors; internal links and anchors resolve.
- `LICENSE` contains the exact copyright line `Copyright (c) 2026 Asdale Dynamics, LLC`.
- `README.md` credits Asdale Dynamics, LLC.
- All docs files have substantive content (manual 7,552 chars, checklist 1,897 chars, worksheet 1,335 chars).
- No `.github/workflows` files, no secrets, API keys, or personal data in any file.

## Known gaps

- No automated test suite or linter configured (static HTML/markdown project).
- Fee percentages in the manual are estimates; users should check eBay's and Amazon's current fee pages before listing (noted in the manual disclaimer).
- Not integrated with dylanasdale.github.io; the LLC can publish this site separately.
