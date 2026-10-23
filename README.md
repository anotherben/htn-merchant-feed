# htn-merchant-feed

Hosts the product feed for Google Merchant Center (account 458331991) for [Hunt The Night](https://huntthenight.com.au).

- `htn-gmc-feed.tsv` — tab-separated product feed, one row per variant, refreshed daily by an automated job.
- Fetch URL: <https://raw.githubusercontent.com/anotherben/htn-merchant-feed/main/htn-gmc-feed.tsv>

The feed only contains product data that is already public on huntthenight.com.au. Please don't edit by hand; the file is overwritten on every run. GitHub Actions is intentionally disabled for this repo.
