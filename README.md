# Available .PINK One-Word Domains (9,206)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C205%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C206%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pink one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,205-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,206 domains** on the canonical page below.

**Public extract:** 9,205 rows · **Live catalog:** 9,206 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/pink`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/pink?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./pink.csv">CSV</a> / <a href="./pink.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PINK search](https://unique.domains/domains/tld/pink?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PINK search](https://unique.domains/domains/tld/pink?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PINK one-word domain catalog.

### Files

- `pink.csv` — public CSV extract (9,205 rows)
- `pink.json` — public JSON extract (9,205 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/pink-oneword-domains/main/pink.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar               |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------- |
| fortune.pink  | available | $14.99    | —             | 72             | 48     | 7      | name.com                |
| trade.pink    | resell    | $31.48    | —             | 116            | 46     | 5      | GoDaddy.com, LLC        |
| easy.pink     | premium   | $14.99    | $37.99        | 128            | 62     | 4      | name.com                |
| snap.pink     | available | $14.99    | $37.99        | 90             | 46     | 4      | name.com                |
| best.pink     | resell    | —         | —             | 82             | 99     | 4      | Porkbun LLC             |
| ace.pink      | premium   | $82.50    | $82.50        | 88             | 57     | 3      | name.com                |
| genius.pink   | available | $14.99    | $37.99        | 98             | 45     | 6      | name.com                |
| white.pink    | resell    | —         | —             | 102            | 98     | 5      | Porkbun LLC             |
| abc.pink      | premium   | $650      | $650          | 102            | 50     | 3      | namecheap               |
| strategy.pink | available | $31.48    | —             | 74             | 43     | 8      | namecheap               |
| apple.pink    | resell    | —         | —             | 98             | 88     | 5      | DNSPod, Inc.            |
| gold.pink     | premium   | $1,300    | $1,300        | 72             | 48     | 4      | namecheap               |
| track.pink    | available | $14.99    | $37.99        | 94             | 42     | 5      | name.com                |
| box.pink      | resell    | —         | —             | 68             | 78     | 3      | Unstoppable Domains Inc |
| car.pink      | premium   | $2,600    | $2,600        | 94             | 46     | 3      | namecheap               |
| banana.pink   | available | $14.99    | —             | 86             | 41     | 6      | name.com                |
| discover.pink | resell    | —         | —             | 66             | 75     | 8      | NameCheap, Inc.         |
| auto.pink     | premium   | $5,200    | $5,200        | 68             | 45     | 4      | namecheap               |
| content.pink  | available | $14.99    | $37.99        | 138            | 40     | 7      | name.com                |
| matt.pink     | resell    | —         | —             | 72             | 71     | 4      | Sav.com, LLC            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,205-row public sample | 9,206 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/pink?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/pink?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .PINK One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PINK page](https://unique.domains/domains/tld/pink?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
