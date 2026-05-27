# Available .CARDS One-Word Domains (11,469)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C469%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cards one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,469 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,469 domains · **Median ask:** $13.02 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-27  
**Canonical page:** `https://unique.domains/domains/tld/cards`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cards?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cards.csv">CSV</a> / <a href="./cards.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CARDS search](https://unique.domains/domains/tld/cards?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CARDS search](https://unique.domains/domains/tld/cards?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CARDS one-word domain catalog.

### Files

- `cards.csv` — public CSV extract (1,000 rows)
- `cards.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cards-oneword-domains/main/cards.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| geton.cards       | available | $3.99     | —             | 82             | 10     | 6      | name.com         |
| Apples.cards      | available | $48.98    | —             | 90             | 16     | 6      | namecheap        |
| useit.cards       | available | $3.99     | —             | 94             | 7      | 6      | name.com         |
| playin.cards      | available | $3.99     | —             | 80             | 10     | 7      | name.com         |
| dogsick.cards     | available | $3.99     | —             | 90             | 1      | 7      | name.com         |
| getlife.cards     | available | $3.99     | —             | 80             | 5      | 8      | name.com         |
| leaveon.cards     | available | $3.99     | —             | 80             | 1      | 8      | name.com         |
| rumcake.cards     | available | $3.99     | —             | 81             | 2      | 8      | name.com         |
| skills.cards      | available | $3.99     | —             | 58             | 47     | 6      | name.com         |
| girls.cards       | resell    | —         | —             | 83             | 23     | 5      | Porkbun LLC      |
| jobs.cards        | premium   | $123.75   | —             | 79             | 42     | 4      | name.com         |
| letsgo.cards      | available | $3.99     | —             | 57             | 31     | 7      | name.com         |
| pestcontrol.cards | resell    | —         | —             | 74             | 16     | 12     | GoDaddy.com, LLC |
| partners.cards    | premium   | $500      | —             | 61             | 31     | 8      | name.com         |
| SanDiego.cards    | available | $3.99     | —             | 74             | 29     | 9      | name.com         |
| tips.cards        | premium   | $500      | —             | 80             | 26     | 4      | name.com         |
| Jim.cards         | available | $48.98    | —             | 78             | 28     | 3      | namecheap        |
| reports.cards     | premium   | $123.75   | —             | 58             | 24     | 7      | name.com         |
| dogs.cards        | available | $3.99     | —             | 76             | 28     | 4      | name.com         |
| coupons.cards     | premium   | $500      | —             | 52             | 24     | 7      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,469 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cards?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cards?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .cards domains. The names range from clear dictionary-style terms such as finals.cards and jewels.cards to more playful or abstract options like hahaha.cards and barup.cards. For founders, the main question is whether .cards fits the product, community, or campaign closely enough to feel natural and memorable. For investors, the key test is narrower: whether the word pairs cleanly with .cards and leaves room between acquisition cost and likely resale demand. The median ask is 13.02, so price alone is not enough. Compare clarity, commercial relevance, and whether the term creates an obvious use case on this extension.

- Prefer words that pair naturally with the .cards extension
- Check if the term is memorable without extra explanation
- Weigh low ask against renewal fit and resale depth
- Be cautious with playful terms that narrow buyer demand

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CARDS One-Word Domains*. Version 2026-05-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CARDS page](https://unique.domains/domains/tld/cards?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cards_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
