# Available .PINK One-Word Domains (12,150)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C150%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pink one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,150 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,150 domains · **Median ask:** $31.97 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `pink.csv` — public CSV extract (1,000 rows)
- `pink.json` — public JSON extract (1,000 rows)
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

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| homes.pink     | available | $14.99    | —             | 86             | 34     | 5      | name.com         |
| finals.pink    | available | $14.99    | —             | 80             | 7      | 6      | name.com         |
| forces.pink    | available | $14.99    | —             | 82             | 12     | 6      | name.com         |
| geton.pink     | available | $14.99    | —             | 82             | 10     | 6      | name.com         |
| popup.pink     | available | $14.99    | —             | 84             | 29     | 6      | name.com         |
| Apples.pink    | available | $31.48    | —             | 90             | 16     | 6      | namecheap        |
| gearup.pink    | available | $14.99    | —             | 80             | 16     | 7      | name.com         |
| playin.pink    | available | $14.99    | —             | 80             | 10     | 7      | name.com         |
| playon.pink    | available | $14.99    | —             | 80             | 14     | 7      | name.com         |
| toneup.pink    | available | $14.99    | —             | 80             | 5      | 7      | name.com         |
| watches.pink   | available | $14.99    | —             | 84             | 19     | 7      | name.com         |
| getlife.pink   | available | $14.99    | —             | 80             | 5      | 8      | name.com         |
| leaveon.pink   | available | $14.99    | —             | 80             | 1      | 8      | name.com         |
| shortcuts.pink | available | $14.99    | —             | 48             | 41     | 10     | name.com         |
| online.pink    | resell    | —         | —             | 70             | 62     | 7      | Porkbun LLC      |
| farmers.pink   | premium   | $82.50    | —             | 54             | 59     | 7      | name.com         |
| prompts.pink   | available | $14.99    | —             | 54             | 39     | 7      | name.com         |
| studios.pink   | resell    | —         | —             | 54             | 21     | 7      | GoDaddy.com, LLC |
| etc.pink       | premium   | $82.50    | —             | 58             | 34     | 3      | name.com         |
| aliens.pink    | available | $14.99    | —             | 56             | 35     | 6      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,150 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is defined by a single trait: every name uses the .pink extension and reads as a one-word domain. That creates a distinct profile. Some names are literal and category-led, such as homes.pink or jewels.pink. Others are broader or more suggestive, such as getup.pink or finals.pink. When comparing these domains, focus first on whether the word carries meaning without explanation, whether .pink strengthens or limits that meaning, and whether the ask leaves room for long-term renewal comfort. For founders, the best picks are memorable and easy to say. For investors, the better candidates are clean words with clear end-user relevance at sensible entry prices.

- All names in this set use the .pink extension
- Examples include homes.pink, jewels.pink, and ladies.pink
- Median ask is 31.97 across 12,150 domains
- Favor words that stay clear when paired with .pink

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PINK One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PINK page](https://unique.domains/domains/tld/pink?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pink_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
