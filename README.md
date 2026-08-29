# Lumina website catalog

Source of truth for Lumina Real Estate listings in Amman: **ref numbers, prices, specs, and photos**.

## What Lumina Desk reads

`src/data/listings-catalog.json` — combined feed of every listing.

Individual files live in `src/data/listings/` (committed from this PC; push with git if the catalog file is missing).

## Keep the desk in sync

1. Update a listing JSON (or the catalog).
2. Push to `main`.
3. In the desk, click **Sync from website**, or wait ~15 minutes for auto-sync.

Desk URL: https://lumina-desk-amman.netlify.app
