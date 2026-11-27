# bionpact_site_beta

beta site for **BionPact Pte Ltd** — GitHub Pages.

| | |
|---|---|
| Custom domain | `beta.bp.truesight.me` |
| Pages source | branch `main`, folder `/` (root) |
| Static build | none (plain HTML/CSS/JS) |

Base repository. `bionpact_site_prod` is a **fork** of this repo; promote with a
non-force upstream merge so the two differing `CNAME` files both survive.

## Editing

Push to `main`, or open a feature branch and PR. Pages redeploys automatically.

## Domain setup

The `CNAME` file in the repo root pins the custom domain — do not delete it.
DNS records required for `beta.bp.truesight.me` are documented in
`bionpact_dns_config.pdf` (A records for the apex, `bionpact-pte-ltd.github.io`
CNAME for `www`), then enable **Enforce HTTPS** under Settings → Pages.
