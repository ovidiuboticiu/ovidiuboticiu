# Ovidiu Boticiu

**Independent researcher exploring AI agents, memory, reliability, and experimental evaluation.**

I build small, auditable research artifacts around a practical question: **how can we tell when an AI agent is actually reliable, rather than merely appearing reliable?**

My work focuses on controlled experiments, explicit stopping rules, preserved negative results, reproducibility, and careful separation between observed behavior and stronger mechanistic claims.

## Selected public research

### [Intra-Agent Evidence Recycling (IAER)](https://github.com/ovidiuboticiu/intra-agent-evidence-recycling)
Tests whether repeated derivative memory from a single source can gain excess behavioral weight in an LLM agent-style system. The main reported effect is deliberately narrow and configuration-specific; later cross-family qualification did not establish generalization.

### [Verification-Status Overclaiming (VSO)](https://github.com/ovidiuboticiu/verification-status-overclaiming-public)
A reproducible experiment on a specific agent failure: declaring that available evidence is sufficient when a frozen experimental oracle says it is insufficient.

### [MEES — Minimal Epistemic Ecology Search](https://github.com/ovidiuboticiu/mees-minimal-condition-search)
Searches for minimal sufficient conditions, functional substitutions, and behavioral boundaries in artificial ecologies under a bounded query budget. Failed stages and scope limitations are retained alongside successful results.

### [Order-Necessity Gate](https://github.com/ovidiuboticiu/order-necessity-gate)
A structural test for whether adaptive information-seeking truly requires ordered interaction history, or whether a compressed count-based representation can match the unrestricted optimum.

## Research principles

- Separate **behavioral observations**, **provenance judgments**, and **mechanistic interpretations**.
- Freeze decision rules before confirmatory runs when the design permits it.
- Keep failed, aborted, and negative-result stages instead of silently removing them.
- Use adversarial review, recomputation, and explicit scope limits.
- Withdraw or narrow claims when later evidence no longer supports them.
- Treat reproducibility and auditability as part of the result, not as an afterthought.

## Scope

These repositories are primarily **experimental research artifacts**, not production-ready agent frameworks. Their conclusions apply to the tested protocols, models, and environments unless broader generalization is independently demonstrated.

My current interests include agent reliability, verification, memory, experimental harnesses, failure localization, and architectures that reduce error propagation in tool-using AI systems.

## AI assistance

Some projects are human-led and AI-assisted. Where AI tools materially contributed to methodology, coding, review, analysis, or documentation, the relevant repositories include explicit disclosure and provenance notes.
