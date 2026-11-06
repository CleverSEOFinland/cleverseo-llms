# cleverseo-llms

CleverSEO's `llms.txt`, following the [llms.txt convention](https://llmstxt.org/), for the
public website at [cleverseo.fi](https://cleverseo.fi/).

## What this repo contains

- `llms.txt` — a curated index of the site's key pages (company, CleverSEO for WP, services,
  contact, and legal/privacy pages) with a one-line description of each, so LLMs can find
  current, official information about CleverSEO.

## Deployment

`llms.txt` is deployed as a static file at the website's root, so it is served at
`https://cleverseo.fi/llms.txt`. It is copied to the server manually; this repo is the source
of truth and is not wired into any automated deploy.

## Maintenance

The file is rewritten by hand against the live site whenever cleverseo.fi's structure,
products or key pages change meaningfully — it is not generated automatically.
