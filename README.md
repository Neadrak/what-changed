# What Changed?

Understand what changed between two CSV exports without comparing spreadsheets cell by cell.

## Release candidate

- Upload an older and newer CSV.
- Files are parsed locally in the browser; file contents are not uploaded to a backend.
- Automatically suggests a likely key column such as SKU, ID, email or code.
- Classifies records as added, removed, modified or unchanged.
- Shows field-level old → new values.
- Produces deterministic human-readable insights for frequently changed and numeric columns.
- Downloads a CSV change report.
- Responsive, dependency-free static site.
- Handles malformed CSV structure, quoted multiline fields, delimiter detection, duplicate/blank keys, hostile HTML-like cell values, and spreadsheet-formula-safe report export.

## Run locally

Open `index.html` in a modern browser. No build step or dependencies are required.

## Current scope

This release candidate supports CSV and has been regression-tested across large files, schema changes, malformed input, multiline quoted fields, key-safety cases, hostile cell content and repeated state changes. XLSX support, richer explanations and optional AI summaries can be evaluated after validating real usage.

## Product direction

Free comparison should remain useful and privacy-friendly. Future monetization can come from a lightweight Pro tier (larger files, richer reports, saved workflows/exports) and, only after meaningful traffic exists, carefully placed advertising.
