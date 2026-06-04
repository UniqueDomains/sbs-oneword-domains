# Available .SBS One-Word Domains (12,255)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C255%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .sbs one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,255 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,255 domains · **Median ask:** $54.40 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/sbs`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/sbs?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./sbs.csv">CSV</a> / <a href="./sbs.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SBS search](https://unique.domains/domains/tld/sbs?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SBS search](https://unique.domains/domains/tld/sbs?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SBS one-word domain catalog.

### Files

- `sbs.csv` — public CSV extract (1,000 rows)
- `sbs.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sbs-oneword-domains/main/sbs.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| deck.sbs        | premium   | $19.60    | $39.20        | 94             | 29     | 4      | namecheap |
| look.sbs        | premium   | $282.88   | $565.76       | 80             | 33     | 4      | namesilo  |
| times.sbs       | premium   | $154.70   | $309.40       | 80             | 24     | 5      | namecheap |
| Crayola.sbs     | premium   | $282.88   | $565.76       | 80             | 61     | 7      | namesilo  |
| two.sbs         | premium   | $103.12   | $137.50       | 80             | 27     | 3      | name.com  |
| imagine.sbs     | premium   | $154.70   | $309.40       | 100            | 41     | 7      | namecheap |
| auditory.sbs    | available | $1.49     | —             | 88             | 6      | 8      | name.com  |
| wealth.sbs      | premium   | $141.44   | $282.88       | 84             | 33     | 6      | namesilo  |
| appreciate.sbs  | available | $1.49     | —             | 84             | 13     | 10     | name.com  |
| vacuum.sbs      | available | $1.49     | —             | 90             | 18     | 6      | name.com  |
| wireless.sbs    | premium   | $143.65   | $574.60       | 106            | 24     | 8      | namecheap |
| overjoy.sbs     | available | $1.49     | —             | 102            | 3      | 7      | name.com  |
| lookup.sbs      | premium   | $384      | $768          | 82             | 30     | 7      | namesilo  |
| culture.sbs     | premium   | $143.65   | $287.30       | 98             | 39     | 7      | namecheap |
| cordial.sbs     | available | $1.49     | $24.99        | 98             | 12     | 7      | name.com  |
| binding.sbs     | available | $1.49     | —             | 92             | 8      | 7      | name.com  |
| coat.sbs        | premium   | $282.88   | $565.76       | 100            | 11     | 4      | namesilo  |
| learn.sbs       | premium   | $309.40   | $618.80       | 82             | 42     | 5      | namecheap |
| lightweight.sbs | premium   | $32.45    | $65.45        | 113            | 9      | 11     | namesilo  |
| hate.sbs        | premium   | $16.52    | $33.04        | 86             | 22     | 4      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,255 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/sbs?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/sbs?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=related_pricing)

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

This set is entirely focused on one-word .sbs domains. The names lean short, direct, and brandable, with examples ranging from action phrases like getin.sbs, geton.sbs, and getup.sbs to dictionary-style words like finals.sbs and edamame.sbs. With a median ask of 37.44, the selection sits in a low entry-price range, which can suit founders who want an ownable option now and investors testing low-cost inventory. When comparing these domains, focus on memorability, spelling clarity, meaning, and whether the word feels commercially usable without extra explanation.

- All results are one-word domains on the .sbs extension
- Median ask across this set is 37.44
- Examples include finals.sbs, getup.sbs, and edamame.sbs
- Best judged on spelling, recall, and price discipline

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SBS One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SBS page](https://unique.domains/domains/tld/sbs?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sbs_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
