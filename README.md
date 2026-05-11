# Available .SHOW One-Word Domains (11,585)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C585%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .show one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,585 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,585 domains · **Median ask:** $21.01 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/show`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/show?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./show.csv">CSV</a> / <a href="./show.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SHOW search](https://unique.domains/domains/tld/show?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SHOW search](https://unique.domains/domains/tld/show?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SHOW one-word domain catalog.

### Files

- `show.csv` — public CSV extract (1,000 rows)
- `show.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/show-oneword-domains/main/show.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| Trex.show        | available | $47.98    | —             | 80             | 24     | 5      | namecheap         |
| barup.show       | available | $17.99    | —             | 82             | 2      | 6      | name.com          |
| forces.show      | available | $17.99    | —             | 82             | 12     | 6      | name.com          |
| geton.show       | available | $17.99    | —             | 82             | 10     | 6      | name.com          |
| follow.show      | available | $17.99    | —             | 84             | 28     | 6      | name.com          |
| Apples.show      | available | $47.98    | —             | 90             | 16     | 6      | namecheap         |
| useit.show       | available | $17.99    | —             | 94             | 7      | 6      | name.com          |
| gearup.show      | available | $17.99    | —             | 80             | 16     | 7      | name.com          |
| stirup.show      | available | $17.99    | —             | 82             | 3      | 7      | name.com          |
| leaveon.show     | available | $17.99    | —             | 80             | 1      | 8      | name.com          |
| presents.show    | available | $17.99    | —             | 80             | 9      | 8      | name.com          |
| Snickers.show    | available | $47.98    | —             | 80             | 10     | 8      | namecheap         |
| pictures.show    | available | $17.99    | —             | 82             | 17     | 8      | name.com          |
| inspiration.show | available | $17.99    | —             | 88             | 30     | 11     | name.com          |
| online.show      | resell    | —         | —             | 70             | 62     | 7      | Dynadot Inc       |
| jobs.show        | premium   | $1,000    | —             | 79             | 42     | 4      | name.com          |
| quotes.show      | available | $17.99    | —             | 58             | 29     | 6      | name.com          |
| events.show      | resell    | —         | —             | 68             | 37     | 6      | Sav.com, LLC - 23 |
| SanDiego.show    | premium   | $118.80   | $118.80       | 74             | 29     | 9      | namesilo          |
| Cats.show        | resell    | —         | —             | 59             | 33     | 4      | DNSPod, Inc.      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,585 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/show?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/show?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These domains are all built on the .show extension, so the best candidates are words that naturally pair with presentation, entertainment, events, demos, or visible outcomes. In this set, the strongest picks tend to read cleanly as a phrase, such as useit.show or finals.show, rather than forcing an awkward construction. Founders should favor words that stay memorable when spoken aloud and still look credible with this niche ending. Investors should focus on words with obvious end-user fit, broad commercial use, and realistic resale appeal within a specialized TLD. Plural forms, command words, and generic nouns can work, but only when the full domain feels intentional.

- Best fits are words that pair naturally with .show
- Median ask is 21.01 across 11,578 domains
- Check if the full phrase sounds clear when spoken
- Favor obvious commercial words over forced pairings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOW One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOW page](https://unique.domains/domains/tld/show?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
