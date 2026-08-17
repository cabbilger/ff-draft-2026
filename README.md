# ff-draft-2026

Fantasy auction draft tools for the "New World Order" ESPN league (leagueId 767412).

- **`index.html`** — the main tool: Auction Draft Cheatsheet & Dashboard. Player values, live bid assistant, budget/roster tracker, and an ESPN-style Mock Draft rehearsal room. This is what loads at the site root.
- **`auction-draft-tracker.html`** — a simpler, older budget/roster-only tracker (no cheatsheet). Kept as a lightweight fallback, reachable at `/auction-draft-tracker.html`.

Both files are fully self-contained static HTML (no build step) — deploy as-is.

## Deploying updates

This repo is connected to Cloudflare Pages for auto-deploy. Any push to `main` redeploys the live site automatically — usually live within a minute. To update a file from the GitHub web UI: open the file in this repo, click the pencil (edit) icon, paste in the new contents, and commit directly to `main`. No local git setup needed.
