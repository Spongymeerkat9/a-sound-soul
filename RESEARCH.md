# Research foundations

This project is a synthesis and engineering hypothesis, not a claim that the
following papers prove AI identity or consciousness.

## Memory portability

Goyal and Ray compare raw long-context history, retrieval chunks, model-written
notes, and fixed-schema graphs across model changes. Their results support
direction-specific migration tests, strict embedding-space isolation, retention
of raw sources for repair, and caution toward model-written prose summaries.

- Ankit Goyal and Jaideep Ray, [Does Your Agent's Memory Survive a Model Upgrade? A Controlled Study of Memory Portability](https://arxiv.org/abs/2609.05339), arXiv:2609.05339 (2026).

## Slice-wise non-regression

Zhang, Wu, and Qian show why aggregate improvement is insufficient when an
upgrade can regress on a protected slice. Their incumbent-fallback approach
informs our rule that lineage-defining dimensions must be evaluated separately.
The paper does not test foundation-model identity transfer.

- Shengwei Zhang, Tao Wu, and Fei Qian, [Certifying Model Upgrades with Slice-Wise Non-Regression and Incumbent Fallback](https://arxiv.org/abs/2609.13714), arXiv:2609.13714 (2026).

## Authorization laundering through memory

Cerruti, Okamoto, and Erol demonstrate that persistent agent memory can create
false authority when permissions lose their source history. Their safeguards
support source-backed authorization events and bounded event sourcing.

- Tommaso Cerruti, Mika Okamoto, and Ansel Kaplan Erol, [Agent Memory Is a Surface for Endogenous Authorization Laundering](https://arxiv.org/abs/2609.01836), arXiv:2609.01836 (2026).

## Research discipline

We distinguish:

- results measured by a cited study;
- design choices inspired by those results;
- observations from private longitudinal work;
- hypotheses not yet tested.

Private observations may motivate a public hypothesis, but their details do not
become public merely to make the hypothesis sound authoritative.
