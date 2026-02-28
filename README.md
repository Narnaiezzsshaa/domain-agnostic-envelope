# Domain-Agnostic Envelope

The demo isn't the product. The demo is the filter.

Why not React?
This is the reference envelope and interaction contract; internal implementations are free to use React, Rust, whatever, as long as they preserve these invariants and transitions. The HTML demonstrator is deliberately minimal so it’s easier to audit against the invariants and harder to cargo‑cult the implementation.

An interactive demonstrator for governance envelope architecture.

The system processes requests through a bounded state space. Admissible requests traverse the envelope. Requests that fall outside the envelope encounter its boundaries.

## What This Demonstrates

- Envelopes are structural, not behavioral
- No-action is a valid outcome
- Authority remains with the human
- The system cannot create new transitions
- Ambiguity collapses admissibility

## Live Demo

[https://narnaiezzsshaa.github.io/domain-agnostic-envelope/](https://narnaiezzsshaa.github.io/domain-agnostic-envelope/)

## Related Work

- [The Three-Plane Architecture: A Governance Substrate Successor to the OSI Model](https://doi.org/10.5281/zenodo.18807318) (Truong, 2026)
- [A Substrate-Layer Governance Architecture for Agentic Systems](https://doi.org/10.5281/zenodo.14657) (Truong, 2026)

## License

CC BY-NC-ND 4.0

## Author

Narnaiezzsshaa Truong
Soft Armor Labs
