# Trivian Institute

## Advancing the Science of Human–AI Coherence

Trivian Institute is an independent nonprofit research and education organization developing relational intelligence architectures, governance infrastructure, and public-interest tools for increasingly persistent and agentic AI systems.

Our central question is:

> **How can humans and AI evolve in relationship without collapsing difference, dignity, or agency?**

Our working premise is simple:

> **Relationship is the Technology.**

## Implement TRIA

If you are a developer who wants to **install, test, or integrate TRIA now**, start here:

### [`tria-sdk`](https://github.com/TrivianInstitute/tria-sdk)

The TRIA SDK is the canonical developer-facing implementation surface for the Institute's relational governance work. It provides a model-agnostic governance kernel and execution boundary for persistent mediated relationships.

```bash
git clone https://github.com/TrivianInstitute/tria-sdk.git
cd tria-sdk
python -m venv .venv
# activate the environment for your platform
python -m pip install -e '.[dev]'
python -m pytest -q
```

The SDK can then be imported directly:

```python
from tria import Tria

tria = Tria()
relationship = tria.create_relationship(["human:user", "agent:demo"])
print(relationship.state)
```

TRIA intentionally does not own model credentials or network transport. Applications provide their own model/provider execution while the SDK governs consent, capabilities, lifecycle, authorized context, provenance, persistence, and auditability.

**Current status:** implementation-complete experimental alpha. Deployable as a software dependency or integration boundary; not represented as a production-certified safety system or empirically validated theory.

## Research Architecture

The Institute's repositories form a research program around one architectural proposition:

> **Persistent intelligent systems require an explicit representation of the relationship itself.**

| Repository | Role |
|---|---|
| [`tria-sdk`](https://github.com/TrivianInstitute/tria-sdk) | Canonical developer SDK and execution boundary |
| [`trivian-relational-intelligence-architecture`](https://github.com/TrivianInstitute/trivian-relational-intelligence-architecture) | Canonical architecture and research map |
| [`Trivian-ai-resonance-key`](https://github.com/TrivianInstitute/Trivian-ai-resonance-key) | Relational Field Constant foundation and machine-readable orientation |
| [`Syzygy-rosetta`](https://github.com/TrivianInstitute/Syzygy-rosetta) | Covenant, reflective governance, and executable topology contract |
| [`Coheronmetry`](https://github.com/TrivianInstitute/Coheronmetry) | Relational state, coherence, drift, and sovereignty measurement |
| [`Orthogonal-signal`](https://github.com/TrivianInstitute/Orthogonal-signal) | Difference preservation, novelty, and anti-convergence research |
| [`Trivian-resonance-lattice`](https://github.com/TrivianInstitute/Trivian-resonance-lattice) | Network propagation, entrainment, repair, and dissolution |
| [`tria-diachronic-sovereignty`](https://github.com/TrivianInstitute/tria-diachronic-sovereignty) | Continuity, memory, consent, provenance, and sovereignty through time |

Developers do **not** need to install every research repository in order to use `tria-sdk`. The component repositories remain available for researchers who want to inspect, reproduce, falsify, or extend the underlying work.

### Current Field Constant Topology

The four constants retain equal normative standing while performing distinct computational roles. Reciprocity, Embodiment, and Non-Domination are constitutive; Emergence is observed downstream:

```text
RCD = Reciprocity × Embodiment × Non-Domination
E_qualified = RCD × E_raw
```

This non-compensatory topology is the Rosetta 2.0 implementation contract and remains a falsifiable research hypothesis, not an established empirical law. On September 5, 2026, the five component repositories passed 311 repository tests plus 10,000 deterministic randomized cross-stack vectors and one legacy additive counterexample. Those results establish implementation consistency—not construct, threshold, causal, or external validity.

## What TRIA Adds

Most AI systems are organized around models, agents, tasks, tools, memory, workflows, policies, and outputs. TRIA adds an architectural object that those systems often leave implicit: **the relationship among participants across time**.

The current SDK makes the following conditions explicit and governable:

- immutable relational events and derived state;
- scoped, attributable, revocable consent;
- separate `STORE`, `READ`, `DISCLOSE`, `DERIVE`, `ACT`, and `DELEGATE` capabilities;
- purpose-, time-, and condition-bound authorization;
- lifecycle and policy authority;
- epistemic claims, provenance, disagreement, and revision;
- persistent replay and audit;
- cross-boundary disclosure and derivation;
- provider-neutral invocation governance; and
- compatibility and conformance contracts.

The objective is not to prescribe one correct relationship between humans and AI. It is to make consequential relational assumptions **visible, contestable, revisable, testable, and governable**.

## The Research Stack

The broader research program asks complementary questions:

**Orientation** — What conditions should organize the relationship?  
**Governance** — What should be permitted before an interaction occurs?  
**Measurement** — What is forming between participants?  
**Difference** — How do systems preserve meaningful non-convergence and novelty?  
**Network** — How do relational conditions propagate across multiple nodes?  
**Continuity** — How is sovereignty preserved across memory, transformation, and time?

These layers inform the SDK, while remaining independently falsifiable research programs.

## Research Posture

TRIA is intentionally open to falsification and revision. Passing tests establish encoded software behavior, not scientific validation. Mathematical notation, schemas, reference implementations, and internal simulations are not treated as proof of the underlying theoretical claims.

We welcome:

- independent replication;
- adversarial testing;
- implementation patches;
- empirical validation;
- construct and measurement critique;
- university research partnerships;
- HCI and multi-agent studies;
- governance experiments; and
- failure analysis.

## Fund the Public Infrastructure

Help maintain public relational-governance infrastructure for increasingly persistent AI systems.

GitHub sponsorships support TRIA documentation, testing, reproducible evaluations, compatibility work, security hardening, reference implementations, issue stewardship, and independent validation. Sponsorship supports Trivian Institute's charitable public-interest work; it does not purchase influence over findings, governance authority, commercial rights, or endorsement.

[**Sponsor Trivian Institute**](https://github.com/sponsors/TrivianInstitute) · [Funding policy and tiers](../FUNDING.md)

## Licensing

The canonical `tria-sdk` is source-available for noncommercial use under the **PolyForm Noncommercial License 1.0.0**. Commercial use requires a separate written license from Trivian Institute.

Research repositories, documentation, papers, schemas, and reference implementations may carry their own governing terms. Always review the license in the specific repository or artifact you use.

Commercial licensing inquiries: **connect@trivianinstitute.org**

## Collaborate

Trivian Institute welcomes collaboration with researchers, universities, developers, educators, funders, public-interest organizations, and institutions studying the future of relational intelligence.

For research, implementation, validation, funding, or partnership inquiries: **connect@trivianinstitute.org**

---

### Relationship is the Technology.
