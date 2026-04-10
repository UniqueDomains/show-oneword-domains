# Available .SHOW One-Word Domains (5,622,008)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C732%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C008%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .show one-word domains from Unique Domains.

> **Important:** this repository is a **public 8,732-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,008 domains** on the canonical page below.

**Public extract:** 8,732 rows · **Live catalog:** 5,622,008 domains

**Last updated:** 2026-04-10  
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

- `show.csv` — public CSV extract (8,732 rows)
- `show.json` — public JSON extract (8,732 rows)
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

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| quest.show      | available | $17.99    | —             | 74             | 46     | 5      | name.com                                                |
| last.show       | resell    | —         | —             | 76             | 99     | 4      | DNSPod, Inc.                                            |
| auto.show       | premium   | $1,040    | $1,040        | 68             | 42     | 4      | namecheap                                               |
| pocket.show     | available | $17.99    | —             | 72             | 42     | 6      | name.com                                                |
| cat.show        | resell    | —         | —             | 92             | 80     | 3      | Porkbun LLC                                             |
| electronic.show | premium   | $82.50    | $82.50        | 68             | 21     | 10     | name.com                                                |
| shared.show     | available | $17.99    | $56.99        | 70             | 39     | 6      | name.com                                                |
| box.show        | resell    | —         | —             | 68             | 78     | 3      | DNSPod, Inc.                                            |
| outdoors.show   | premium   | $250      | $250          | 88             | 18     | 8      | name.com                                                |
| conscious.show  | available | $17.99    | $56.99        | 89             | 38     | 9      | name.com                                                |
| wise.show       | resell    | —         | —             | 98             | 72     | 4      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| calm.show       | premium   | —         | —             | 118            | 99     | 4      | —                                                       |
| order.show      | available | $17.99    | $56.99        | 78             | 38     | 5      | name.com                                                |
| get.show        | resell    | —         | —             | 88             | 69     | 3      | GoDaddy.com, LLC                                        |
| blue.show       | premium   | —         | —             | 92             | 99     | 4      | —                                                       |
| unify.show      | available | $17.99    | $56.99        | 72             | 38     | 5      | name.com                                                |
| easy.show       | resell    | —         | —             | 128            | 68     | 4      | GoDaddy.com, LLC                                        |
| bob.show        | premium   | —         | —             | 88             | 99     | 3      | —                                                       |
| field.show      | available | $17.99    | —             | 68             | 38     | 5      | name.com                                                |
| flow.show       | resell    | —         | —             | 96             | 67     | 4      | DNSPod, Inc.                                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,732-row public sample | 5,622,008 live domains                           |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOW One-Word Domains*. Version 2026-04-10. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOW page](https://unique.domains/domains/tld/show?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_show_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
