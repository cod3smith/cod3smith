## Kelyn Paul Njeri

Senior Software Engineer and Computational Biologist, in Nairobi, working remotely with teams in EU and US time zones.

I've spent nine years on production systems in payments, logistics and data platforms, and the last few building research software in causal inference and computational biology. The research exists because the infrastructure under it got built.

**Now:** Founder at [Neoforge Labs](https://www.neoforgelabs.tech/), 2024 to present. Technical co-founder and part-time CTO at [DataQRL](https://www.dataqrl.cloud/) since March 2025, where eight modules of financial-crime detection ship against 2,335 commits. Founding engineer on contract at Backbone Technologies since October 2022: p95 API latency under 100 ms, monthly cloud spend down 30%.

How I work: I make the architecture decision and I write down why, so the next person can see what it cost. And I'd rather tell you a thing isn't identifiable than hand you a number I can't defend. That's what the correction at the bottom of this page is.

### I'm taking contract work

| Engagement | Shape | From |
| --- | --- | --- |
| Data platform build | 8 to 16 weeks | $25k |
| Backend and API architecture | 6 to 12 weeks | $18k |
| ML and causal systems | project or retainer | $250/hr |
| Fractional CTO | 1 to 2 days a week, rolling | $250/hr |

Deliverables, scope, and the questions that usually arrive before a call: **[kelynnjeri.com/services](https://www.kelynnjeri.com/services)**

### Research software

- **[causalphylo](https://github.com/Neoforge-Labs/causalphylo)** · Pearl's backdoor criterion over knowledge graphs, separating the edges that can carry a causal claim from the ones that only assert co-occurrence. [PyPI](https://pypi.org/project/causalphylo/) · [docs](https://causalphylo.neoforgelabs.tech/) · source-available, non-commercial.
- **[SAWA](https://github.com/Neoforge-Labs/SAWA)** · Antiretroviral-resistance surveillance for sub-Saharan Africa. Version-pinned HIVdb Sierra calls, HXB2 K03455 alignment, per-subtype phylogenies, transmission clustering. A 32,115-sequence East Africa cohort aligns in under a minute on a laptop. MIT.
- **[ligase](https://github.com/Neoforge-Labs/ligase)** · Reads biological dimensions out of the files, propagates them, and then type-checks every edge in the graph. [PyPI](https://pypi.org/project/ligase-bio/) · [docs](https://ligase.neoforgelabs.tech) · MIT or Apache-2.0.
- **[hephaestus](https://github.com/Neoforge-Labs/hephaestus)** · Correctness primitives for money, canonical JSON, content hashing and webhook signatures. Rust core, Python bindings. Experimental, by its own admission. [hephkit.dev](https://www.hephkit.dev/) · MIT.
- **[karani](https://github.com/cod3smith/karani)** · A job-search agent over nine boards that drops roughly 95% of postings on deterministic rules before any model call, and never submits an application. [PyPI](https://pypi.org/project/karani/) · MIT.
- **[neorx](https://github.com/Neoforge-Labs/neorx)** · Drug-target identification over biomedical knowledge graphs. Under revision, and you should read the next section before you read the code.

### The NeoRx correction

I audited NeoRx in September 2026 and extended the audit in October. It found defects in the causal-inference stage, so I withdrew every quantitative result the paper made. The identification step got rewritten and republished on its own as CausalPhylo.

The retraction sits beside the claim it withdraws rather than filed somewhere quieter: [kelynnjeri.com/papers/neorx](https://www.kelynnjeri.com/papers/neorx).

### Elsewhere

[kelynnjeri.com](https://www.kelynnjeri.com/) · [LinkedIn](https://www.linkedin.com/in/kelyn-paul) · [Mindstate](https://mindstate.hashnode.dev) · [X](https://x.com/KelynNjeri) · kelyn@kelynnjeri.com
