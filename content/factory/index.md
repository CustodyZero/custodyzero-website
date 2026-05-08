---
title: "Factory"
description: "A change-control system for AI-assisted development. Every change declares its intent. Every acceptance is risk-proportional."
icon: "/images/products/factory-icon-dark.svg"
---

## What Factory is

Factory is a governance artifact store designed to separate AI implementation from human acceptance decisions. It enforces that all work is scoped, intentional, and accepted through a risk-proportional process before it is considered done.

AI agents can write code. They cannot safely judge whether changes should ship. Factory solves this by requiring every change to declare its intent and scope upfront, with acceptance criteria determined by risk classification rather than implementer preference.

## What Factory is not

Factory is not a project management tool. It is not a CI pipeline. It is not a code review tool.

Factory governs the boundary between "implemented" and "accepted." Everything before that boundary is the implementer's problem. Everything after it is the operator's decision.

## Risk-proportional acceptance

Changes flow through four categories with corresponding approval paths:

- **Trivial changes** auto-accept upon verification success
- **Local changes** auto-accept upon verification success
- **Cross-cutting changes** auto-accept with audit capability for reversal
- **Architectural changes** require explicit human approval

The risk classification determines the process. Not the implementer. Not the reviewer. The classification.

## Invariants, not guidelines

A guideline asks you to behave well. An invariant guarantees the system cannot violate it. Factory's rules — about who can accept what, about what must be true before a change is accepted, about what cannot be deleted once it is referenced — are enforced by the system, not by convention.

## Phase

Live and continuously updated.

## License

Apache 2.0. The change-control system that gates your deployments should be auditable.

[View on GitHub](https://github.com/CustodyZero/Factory)
