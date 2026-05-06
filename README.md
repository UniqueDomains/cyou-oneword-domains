# Available .CYOU One-Word Domains (12,475)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C475%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cyou one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,475 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,475 domains · **Median ask:** $47.10 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `cyou.csv` — public CSV extract (1,000 rows)
- `cyou.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cyou-oneword-domains/main/cyou.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                          |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------- |
| finals.cyou   | available | $1.79     | $11.95        | 80             | 7      | 6      | namesilo                           |
| dogsit.cyou   | available | $19.48    | —             | 96             | 2      | 6      | namecheap                          |
| edamame.cyou  | available | $1.79     | $11.95        | 80             | 9      | 7      | namesilo                           |
| toneup.cyou   | available | $19.48    | —             | 80             | 5      | 7      | namecheap                          |
| hangon.cyou   | available | $19.48    | —             | 82             | 6      | 7      | namecheap                          |
| pierogi.cyou  | available | $19.48    | —             | 82             | 7      | 7      | namecheap                          |
| dogsick.cyou  | available | $19.48    | —             | 90             | 1      | 7      | namecheap                          |
| headout.cyou  | available | $19.48    | —             | 82             | 6      | 8      | namecheap                          |
| beawake.cyou  | available | $19.48    | —             | 84             | 3      | 8      | namecheap                          |
| dogstail.cyou | available | $19.48    | —             | 94             | 1      | 8      | namecheap                          |
| aloevera.cyou | available | $19.48    | —             | 80             | 10     | 9      | namecheap                          |
| backyard.cyou | available | $19.48    | —             | 80             | 27     | 9      | namecheap                          |
| bedframe.cyou | available | $19.48    | —             | 80             | 3      | 9      | namecheap                          |
| jobs.cyou     | resell    | —         | —             | 79             | 42     | 4      | Global Domains International, Inc. |
| nets.cyou     | premium   | $19.60    | $39.20        | 54             | 81     | 4      | namecheap                          |
| echoes.cyou   | available | $1.79     | $11.95        | 56             | 24     | 6      | namesilo                           |
| tokens.cyou   | resell    | —         | —             | 51             | 36     | 6      | Dynadot LLC                        |
| insight.cyou  | premium   | $309.40   | $618.80       | 76             | 69     | 8      | namecheap                          |
| Mikey.cyou    | available | $19.48    | —             | 70             | 21     | 5      | namecheap                          |
| texts.cyou    | resell    | —         | —             | 52             | 13     | 5      | Dynadot LLC                        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,475 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cyou?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cyou?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .cyou domains. The set includes short action phrases such as geton.cyou and useit.cyou, product-like words such as matcha.cyou and edamame.cyou, and more open-ended brandables like barup.cyou and toneup.cyou. With a median ask of $47.10, the pricing signal is low enough to support broad exploration, but the extension itself is outside the mainstream. When comparing these domains, focus on whether the word carries clean recall, whether the phrase reads naturally with “cyou,” and whether the name can justify any extension-related trust tradeoff for your use case or resale thesis.

- All names in this selection use the .cyou extension
- Median ask is $47.10 across 12,475 domains
- Examples include finals.cyou, getup.cyou, matcha.cyou
- Best picks read cleanly and stay easy to recall

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CYOU One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CYOU page](https://unique.domains/domains/tld/cyou?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cyou_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
