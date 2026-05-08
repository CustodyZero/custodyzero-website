---
title: "Open Source"
description: "CustodyZero's open source projects. Systems where auditability matters more than commercial control."
---

## Why open source

When CustodyZero open sources a project, it is making a structural claim: this system's behavior should be inspectable, reproducible, and modifiable by the people who depend on it.

Open source is not generosity. It is not a growth strategy. It is an architectural decision --- a transparency constraint applied to systems where auditability matters more than commercial control.

---

## Factory

**A change-control system for AI-assisted development.**

Factory is a governance artifact store that separates AI implementation from human acceptance decisions. Every change declares its intent and scope upfront. Acceptance criteria are determined by risk classification, not implementer preference.

- Scope-first work units with declared rationale
- Risk-proportional acceptance (trivial auto-accepts, architectural requires human approval)
- Full audit trail of every acceptance, rejection, and reversal
- Ten formal invariants covering artifact integrity and execution governance

License: Apache 2.0

[GitHub](https://github.com/CustodyZero/Factory)

---

## Archon

**A deterministic coordination layer for local AI agents. Inactive.**

Archon enforces operator-defined rules, validates actions before execution, and logs all decisions locally. It does not send agent activity data to CustodyZero or any third party.

The coordination layer that governs your agents should be auditable. That is the reason Archon is open source. Not because open source is fashionable. Because the alternative --- a proprietary black box deciding what your agents can do --- is structurally wrong.

- Operator-defined capability boundaries
- Deterministic rule enforcement
- Every decision logged and inspectable
- Local-first, no cloud dependency

**Phase:** Inactive. The Apache 2.0 release remains available; the project is not under active development.

License: Apache 2.0

[GitHub](https://github.com/CustodyZero/Archon)

---

## Contributing

Both projects accept contributions. Start with the README in each repository. We do not have a CLA. The license is the agreement.
