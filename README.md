# Available .CYOU One-Word Domains (17,426)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C426%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cyou one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,426 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,426 domains · **Median ask:** $49.25 · **High-demand under $2,500:** 67

**Last updated:** 2026-08-19
**Canonical page:** `https://unique.domains/domains/tld/cyou`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cyou?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cyou.csv">CSV</a> / <a href="./cyou.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CYOU search](https://unique.domains/domains/tld/cyou?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CYOU search](https://unique.domains/domains/tld/cyou?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CYOU one-word domain catalog.

### Files

- `cyou.csv`, public CSV extract (1,000 rows)
- `cyou.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cyou-oneword-domains/main/cyou.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| christmas.cyou | premium   | $282.88   | $565.76       | high           | low    | 9      | namesilo                                     |
| sorry.cyou     | available | $1.79     | $11.95        | high           | low    | 5      | namesilo                                     |
| abaft.cyou     | available | $1.39     | $25.98        | low            | low    | 5      | namecheap                                    |
| pay.cyou       | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| ada.cyou       | premium   | $282.88   | $565.76       | medium         | medium | 3      | namesilo                                     |
| acrid.cyou     | available | $1.39     | $25.98        | low            | low    | 5      | namecheap                                    |
| help.cyou      | resell    | —         | —             | medium         | medium | 4      | Xiamen ChinaSource Internet Service Co., Ltd |
| ago.cyou       | premium   | $107.25   | $143          | medium         | low    | 3      | namecheap                                    |
| aloof.cyou     | available | $1.39     | $25.98        | low            | low    | 5      | namecheap                                    |
| music.cyou     | resell    | —         | —             | high           | medium | 5      | Xiamen ChinaSource Internet Service Co., Ltd |
| ape.cyou       | premium   | $384      | $768          | medium         | low    | 3      | namesilo                                     |
| annoy.cyou     | available | $1.79     | $14.95        | high           | low    | 5      | namesilo                                     |
| business.cyou  | resell    | —         | —             | high           | medium | 8      | Xiamen ChinaSource Internet Service Co., Ltd |
| ask.cyou       | premium   | $65.45    | $140.80       | high           | medium | 3      | namesilo                                     |
| apart.cyou     | available | $19.48    | —             | high           | low    | 5      | namecheap                                    |
| developer.cyou | resell    | —         | —             | high           | low    | 9      | Dynadot LLC                                  |
| Ava.cyou       | premium   | $282.88   | $565.76       | high           | medium | 3      | namesilo                                     |
| apish.cyou     | available | $1.39     | $25.98        | low            | low    | 5      | namecheap                                    |
| azo.cyou       | premium   | $192      | $384          | low            | low    | 3      | namesilo                                     |
| areal.cyou     | available | $1.39     | $25.98        | low            | low    | 5      | namecheap                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,426 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 67 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cyou?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cyou?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=related_pricing)

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

This list of .CYOU domain names focuses on one-word and short compound options like getup.cyou, playin.cyou, and stirup.cyou, alongside longer descriptive picks such as coffeewoman.cyou and makehappen.cyou. With 12,479 domains in this set and a median ask near $58.68, pricing stays low enough for early-stage projects while leaving room to compare spelling, length, and memorability before committing to a specific name.

- 12,479 one-word .CYOU domains in this set
- Median ask near $58.68 across the list
- Mix of short, compound, and phrase-style names
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

> Unique Domains. *Available .CYOU One-Word Domains*. Version 2026-08-19. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CYOU page](https://unique.domains/domains/tld/cyou?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
