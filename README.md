# Available .HOT One-Word Domains (12,907)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C907%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .hot one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,907 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,907 domains · **Median ask:** $296.87 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/hot`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/hot?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./hot.csv">CSV</a> / <a href="./hot.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HOT search](https://unique.domains/domains/tld/hot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HOT search](https://unique.domains/domains/tld/hot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HOT one-word domain catalog.

### Files

- `hot.csv`, public CSV extract (1,000 rows)
- `hot.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/hot-oneword-domains/main/hot.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| aide.hot | available | $51.99    | $51.99        | high           | low    | 4      | namesilo  |
| ago.hot  | premium   | $3,125    | $3,125        | medium         | low    | 3      | name.com  |
| blob.hot | available | $51.99    | $51.99        | medium         | low    | 4      | namesilo  |
| apt.hot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| camo.hot | available | $51.99    | $51.99        | high           | low    | 4      | namesilo  |
| are.hot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| choc.hot | available | $51.99    | $51.99        | high           | low    | 4      | namesilo  |
| bed.hot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| cyan.hot | available | $51.99    | $51.99        | high           | low    | 4      | namesilo  |
| bio.hot  | premium   | $3,125    | —             | high           | medium | 3      | name.com  |
| mist.hot | available | $51.99    | $51.99        | medium         | low    | 4      | namesilo  |
| bit.hot  | premium   | $3,125    | —             | high           | medium | 3      | name.com  |
| neat.hot | available | $51.99    | $51.99        | medium         | low    | 4      | namesilo  |
| box.hot  | premium   | $3,125    | —             | medium         | high   | 3      | name.com  |
| omit.hot | available | $51.99    | $51.99        | high           | low    | 4      | namesilo  |
| bud.hot  | premium   | $1,107    | $1,107        | high           | low    | 3      | namesilo  |
| pity.hot | available | $31.99    | $79.99        | high           | low    | 4      | name.com  |
| cod.hot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| rang.hot | available | $51.99    | $51.99        | low            | low    | 4      | namesilo  |
| did.hot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,907 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/hot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/hot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=related_pricing)

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

This list holds 12,907 one-word domain names on the .hot extension, ranging from concrete nouns like tips.hot and edamame.hot to punchy phrases like makehappen.hot and jetblack.hot. The median asking price across the set is about $297, giving a quick reference point when comparing options. Because every entry is a single word, the names read as clean, easy-to-say, and easy-to-remember — traits that matter whether you're shortlisting a brand or sizing up buyable inventory. When comparing these domains, weigh asking price against renewal cost, check for existing trademark use, and favor spellings that are hard to mistype or mishear.

- 12,907 one-word .hot domain names in this list
- Median asking price near $297 across the set
- Everyday words like tips, gearup, and edamame
- Check price, renewal, and spelling before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HOT One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HOT page](https://unique.domains/domains/tld/hot?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_hot_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
