# Available .SHOW One-Word Domains (18,767)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C767%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .show one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,767 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,767 domains · **Median ask:** $17.59 · **High-demand under $2,500:** 2

**Last updated:** 2026-09-03
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

- `show.csv`, public CSV extract (1,000 rows)
- `show.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/show-oneword-domains/main/show.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| correct.show    | available | $17.99    | $56.99        | high           | low    | 7      | name.com          |
| ale.show        | available | $17.99    | —             | medium         | low    | 3      | name.com          |
| age.show        | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC - 34 |
| image.show      | premium   | $118.80   | $118.80       | high           | medium | 5      | namesilo          |
| ana.show        | available | $17.99    | —             | high           | low    | 3      | name.com          |
| bid.show        | resell    | —         | —             | high           | low    | 3      | DNSPod, Inc.      |
| active.show     | premium   | $17.99    | —             | high           | low    | 6      | name.com          |
| Ann.show        | available | $17.99    | —             | high           | low    | 3      | name.com          |
| bit.show        | resell    | —         | —             | high           | medium | 3      | GoDaddy.com, LLC  |
| outdoors.show   | premium   | $250      | $250          | high           | low    | 8      | name.com          |
| boo.show        | available | $17.99    | —             | high           | low    | 3      | name.com          |
| box.show        | resell    | —         | —             | medium         | high   | 3      | DNSPod, Inc.      |
| automobile.show | premium   | $242      | $242          | high           | low    | 10     | namesilo          |
| con.show        | available | $17.99    | —             | high           | low    | 3      | name.com          |
| bro.show        | resell    | —         | —             | medium         | low    | 3      | Sav.com, LLC - 15 |
| automotive.show | premium   | $500      | —             | high           | low    | 10     | name.com          |
| coy.show        | available | $17.99    | $56.99        | medium         | low    | 3      | name.com          |
| buy.show        | resell    | —         | —             | medium         | medium | 3      | DNSPod, Inc.      |
| conclusive.show | premium   | $17.99    | —             | medium         | low    | 10     | name.com          |
| don.show        | available | $17.99    | —             | high           | low    | 3      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,767 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/show?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/show?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list groups one-word domain names registered under the .show extension, an entertainment- and media-flavored TLD often used for shows, creators, and launch projects. Names like playin.show, getup.show, and cometrue.show illustrate the short, punchy style common across this set. With a median asking price near $20, this selection spans thousands of single-word options, giving founders a fast shortlist and investors a broad view of pricing and coverage before comparing individual listings.

- 11,587 one-word .show domains in this selection
- Median asking price near $20 across the full set
- Short, brandable names suited to shows and media brands
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOW One-Word Domains*. Version 2026-09-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOW page](https://unique.domains/domains/tld/show?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
