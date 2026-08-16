# dino.markets — not listed

This repository is a removal notice. dino.markets is **not listed** in the APIs.io
catalog. It is kept only so inbound links to this URL do not dangle.

## What happened

dino.markets was submitted to the APIs.io Add-API form on **2026-07-08** and
auto-published by the intake gate before human review. That review happened on
**2026-08-16**, and the listing was removed.

## Why

The service is unreachable and had been for the five and a half weeks between
submission and review:

- `dino.markets` — 404
- `www.dino.markets` — 404
- `api.dino.markets` — 525 (Cloudflare cannot reach the origin)

The declared base URL, the OpenAPI at `api.dino.markets/openapi.json`, and the
documentation at `dino.markets/docs` are all unreachable. DNS still resolves, but
nothing serves.

Until this removal, apis.io published a Kin Score of 12.2 against it. Publishing a
rating for an API that cannot be called is the defect being corrected.

## Coming back

This is a `catalog-hygiene` removal, recorded with `relisting: standard`. Nobody asked
for it and nothing was taken from anyone. **If the service comes back, it re-enters
through the normal harvest at no charge** — no fee, no engagement.

Questions or removal requests: kin@apievangelist.com

— Kin Lane, API Evangelist · 2026-08-16
