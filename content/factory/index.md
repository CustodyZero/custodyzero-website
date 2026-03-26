---
title: "Factory"
description: "A change-control system for AI-assisted development. Every change declares its intent. Every acceptance is risk-proportional."
---

## What Factory is

Factory is a governance artifact store designed to separate AI implementation from human acceptance decisions. It enforces that all work is scoped, intentional, and accepted through a risk-proportional process before it is considered done.

AI agents can write code. They cannot safely judge whether changes should ship. Factory solves this by requiring every change to declare its intent and scope upfront, with acceptance criteria determined by risk classification rather than implementer preference.

## What Factory is not

Factory is not a project management tool. It is not a CI pipeline. It is not a code review tool.

Factory governs the boundary between "implemented" and "accepted." Everything before that boundary is the implementer's problem. Everything after it is the operator's decision.

## How it works

The system uses six artifact types stored as JSON files:

- **Packets** define work units with scope and rationale
- **Completions** provide implementation evidence with verification results
- **Acceptances** record human approval
- **Rejections** audit reversals of auto-accepted changes
- **Evidence** documents satisfied environment dependencies
- **Features** decompose high-level intents into ordered packets

## Risk-proportional acceptance

Changes flow through four categories with corresponding approval paths:

- **Trivial changes** auto-accept upon verification success
- **Local changes** auto-accept upon verification success
- **Cross-cutting changes** auto-accept with audit capability for reversal
- **Architectural changes** require explicit human approval

The risk classification determines the process. Not the implementer. Not the reviewer. The classification.

## Invariants

Factory maintains ten formal invariants covering artifact integrity, acceptance rules, execution governance, and structural consistency. These include protections against cyclic dependencies and orphaned records.

Invariants are not guidelines. They are structural constraints enforced by the system.

## License

Apache 2.0. The change-control system that gates your deployments should be auditable.

[View on GitHub](https://github.com/CustodyZero/Factory)
