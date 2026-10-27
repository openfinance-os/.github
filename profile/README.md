# OpenFinance-OS

**The community home for UAE Open Finance**

[![Website](https://img.shields.io/badge/website-openfinance--os.org-0D4F4F)](https://openfinance-os.org)
[![Observatory data](https://img.shields.io/badge/observatory%20data-CC--BY--4.0-blue)](https://openfinance-os.org/observatory)
[![Discussions](https://img.shields.io/badge/discussions-join-brightgreen)](https://github.com/openfinance-os/community-website/discussions)

---

## What is this?

OpenFinance-OS is a **community-driven initiative** that brings visibility, resources and collaboration to the UAE Open Finance ecosystem.

We are **not** a regulator, scheme operator or financial institution. We are developers, fintechs, bankers and enthusiasts who believe open ecosystems thrive on transparency.

**We link to official sources. We don't replace them.**

---

## 🔭 What's on openfinance-os.org

### [Observatory](https://openfinance-os.org/observatory)
Independent tracking of who is registered in the production trust-framework directory, which roles and API families they publish, and how that changes over time. Every number is derived from the public directory and explained in the [methodology](https://openfinance-os.org/observatory/methodology). The underlying data is published as open datasets (CC-BY-4.0):

- [`registry-latest.json`](https://openfinance-os.org/observatory/data/registry-latest.json) — latest snapshot with summary statistics and full participant list
- [`registry-history.json`](https://openfinance-os.org/observatory/data/registry-history.json) — observations over time
- [`registry-changelog.json`](https://openfinance-os.org/observatory/data/registry-changelog.json) — what changed between snapshots

### [Commons](https://openfinance-os.org/commons)
Community-contributed tools, templates, references and insights that anyone building in UAE Open Finance can reuse. Current contributions:

| Contribution | Type | What it is |
|---|---|---|
| [Open Finance Data Sandbox](https://openfinance-os.org/commons/data-sandbox) | Utility | Synthetic UAE Open Finance corpus and explorer: 38 personas across Bank Data Sharing and all seven Insurance Data Sharing lines, an ATM directory, three LFI populate-rate profiles, an MCP server and pinnable fixture packages. No sandbox credentials needed. |
| [Ecosystem Watcher](https://openfinance-os.org/commons/ecosystem-watcher) | Utility | Dashboard showing which licensed financial institutions are demonstrably live against each CBUAE mandate release, based on observed API traffic. |
| [Open Finance Hackathon Docs](https://openfinance-os.org/commons/demo-tpp-starter-kit) | Utility | Documentation hub for the ADCB & Nebras UAE Open Finance Hackathon: quick start, API references, starter kit and project examples. |
| [The UX of Consent Models in Open Banking](https://openfinance-os.org/commons/consent-ux-patterns-reference) | Reference | Analysis of consent UX patterns from the UK Open Banking Implementation Entity, with lessons for Al Tareq. |
| [Open Finance Data for Credit Underwriting](https://openfinance-os.org/commons/open-finance-underwriting-insights) | Insight | A practical framework for combining Open Finance transaction data with traditional credit assessment. |
| [TPP Customer Terms & Conditions Template](https://openfinance-os.org/commons/tpp-terms-conditions-template) | Artifact | A starting template for TPP customer-facing terms for Open Finance data access in the UAE. |

Have something to share? See [how to contribute to the Commons](https://openfinance-os.org/commons/contribute).

### [News](https://openfinance-os.org/news)
Community-curated news on regulatory changes, ecosystem milestones and international developments, plus a weekly digest. Always linked to primary sources.

### [Learn](https://openfinance-os.org/learn)
[Getting started](https://openfinance-os.org/learn/getting-started), a [TPP guide](https://openfinance-os.org/learn/tpp-guide), a [bank guide](https://openfinance-os.org/learn/bank-guide), an [API guide](https://openfinance-os.org/learn/api-guide), a [glossary](https://openfinance-os.org/learn/glossary) and an [FAQ](https://openfinance-os.org/learn/faq). Filling the gaps that official docs don't cover.

### [Global](https://openfinance-os.org/global)
Benchmarking UAE progress against the [UK](https://openfinance-os.org/global/uk), the [EU](https://openfinance-os.org/global/eu) and the [GCC](https://openfinance-os.org/global/gcc).

---

## 📦 Public repositories

| Repository | What it is | Tech | License |
|---|---|---|---|
| [community-website](https://github.com/openfinance-os/community-website) | The source of [openfinance-os.org](https://openfinance-os.org): Observatory, Commons, News, Learn and Global. Home of our [GitHub Discussions](https://github.com/openfinance-os/community-website/discussions), [contributing guide](https://github.com/openfinance-os/community-website/blob/main/docs/CONTRIBUTING.md), [editorial policy](https://github.com/openfinance-os/community-website/blob/main/docs/EDITORIAL.md) and [governance](https://github.com/openfinance-os/community-website/blob/main/docs/GOVERNANCE.md). | Astro | — |
| [data-sandbox](https://github.com/openfinance-os/data-sandbox) | Synthetic UAE Open Finance corpus, client-side explorer, local mock server, labs and MCP server. Validated against Standards v2.1 with the official consolidated errata. Hosted at [openfinance-os.github.io/data-sandbox](https://openfinance-os.github.io/data-sandbox/). | JavaScript, Python | MIT |
| [ofbo](https://github.com/openfinance-os/ofbo) | Open Finance Back Office: a bank-neutral reference back office covering both the LFI and TPP-of-record roles, with four-eyes approvals, reconciliation, analytics, compliance reporting and an audit trail. Includes a live synthetic-data demo. | TypeScript | — |
| [docs](https://github.com/openfinance-os/docs) | Documentation for the ADCB & Nebras UAE Open Finance Hackathon, built with Mintlify. | MDX | MIT |
| [the-finance-wrapper](https://github.com/openfinance-os/the-finance-wrapper) | Small Express example of an idempotent payment runner with a bounded queue and worker pool. | JavaScript | MIT |
| [.github](https://github.com/openfinance-os/.github) | This organisation profile. | — | — |

---

## 🚀 Quick start

- **Explore the ecosystem** → [openfinance-os.org](https://openfinance-os.org)
- **Play with realistic payloads, no credentials needed** → [Data Sandbox](https://openfinance-os.github.io/data-sandbox/)
- **Build for a hackathon** → [Hackathon docs](https://github.com/openfinance-os/docs)
- **See what a bank's back office needs** → [OFBO](https://github.com/openfinance-os/ofbo)
- **Contribute a tool, template or insight** → [Commons contribution guide](https://openfinance-os.org/commons/contribute)
- **Ask a question** → [GitHub Discussions](https://github.com/openfinance-os/community-website/discussions)

---

## 🤝 Contributing

We welcome contributions from everyone:

- **📝 Content** — news items, guides, glossary entries
- **🧰 Commons** — tools, templates, references and insights other builders can reuse
- **💻 Code** — improvements to any public repository above
- **🔍 Data** — help verify Observatory data and spot errors
- **📣 Spread the word** — share with others who might benefit

Start with the [contributing guide](https://github.com/openfinance-os/community-website/blob/main/docs/CONTRIBUTING.md) and the [Commons contribution guide](https://openfinance-os.org/commons/contribute), or open an issue in the relevant repository. All participation is covered by our [code of conduct](https://github.com/openfinance-os/community-website/blob/main/CODE_OF_CONDUCT.md).

---

## 🏛️ Governance

OpenFinance-OS is community-owned and community-funded.

- **No corporate sponsors**
- **No paid placements**
- **No editorial influence from funding**

Decisions are made transparently by maintainers with input from the community. Read the [governance document](https://github.com/openfinance-os/community-website/blob/main/docs/GOVERNANCE.md) and the [About page](https://openfinance-os.org/about).

---

## 🔗 Official resources

We complement, never replace, official channels:

| Resource | Link |
|---|---|
| CBUAE (regulator) | [cbuae.gov.ae](https://cbuae.gov.ae) |
| Al Tareq (trust framework) | [altareq.ae](https://altareq.ae) |
| Nebras (API Hub operator) | [nebras-open-finance.com](https://nebras-open-finance.com/) |
| Open Finance UAE Standards | [openfinanceuae.atlassian.net](https://openfinanceuae.atlassian.net/wiki/spaces/OF) |
| Trust-framework directory (data source for the Observatory) | [data.directory.openfinance.ae](https://data.directory.openfinance.ae) |

---

## ⚠️ Disclaimer

This is a **community project**.

- Not affiliated with CBUAE, Al Tareq, Nebras or any financial institution
- Data is derived from public sources and may not be complete or current
- Nothing here constitutes financial, legal or regulatory advice
- Official information should always be verified with primary sources

---

## 📊 Ecosystem snapshot

From the production trust-framework directory, observed 26 October 2026:

| Metric | Count |
|---|---|
| Active production registrations | 29 |
| Registrations with a published authorization server | 12 |
| Registrations claiming the LFI role | 21 |
| API families published | accounts, payments, products, confirmation of payee, ATM, insurance |

Registrations are directory IDs, not deduplicated legal entities. A published authorization server does not mean verified live traffic. Definitions are in the [methodology](https://openfinance-os.org/observatory/methodology) and inside every dataset file.

→ [Observatory](https://openfinance-os.org/observatory)

---

## 💬 Connect

- **Website:** [openfinance-os.org](https://openfinance-os.org)
- **Discussions:** [GitHub Discussions](https://github.com/openfinance-os/community-website/discussions)
- **Issues:** report bugs or suggest features in the relevant repository

---

<p align="center">
  <strong>Built by the community, for everyone.</strong><br>
  <sub>Open source · Independent · UAE</sub>
</p>
