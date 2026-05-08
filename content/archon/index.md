---
title: "Archon"
description: "A deterministic coordination layer for local AI agents. Operator-defined rules, enforced. Every action validated before execution."
icon: "/images/products/archon-icon-dark.svg"
---

> **Phase: Inactive.** Archon is no longer in active development. The Apache 2.0 release at [github.com/CustodyZero/Archon](https://github.com/CustodyZero/Archon) remains available. Current CustodyZero work focuses on [Type](/type/), [Valet](/valet/), [StationZero](/stationzero/), and [Factory](/factory/).

## What Archon is

Archon is a deterministic coordination layer for local AI agents. It enforces operator-defined rules, validates actions before execution, and logs all decisions locally.

The operator defines the boundaries. Archon enforces them. The logs prove it happened.

## What Archon is not

Archon is not an AI agent framework. It does not build agents. It does not host agents. It does not provide models or inference.

Archon governs the boundary between what agents want to do and what they are allowed to do. Everything else is the agent's problem.

## Why it exists

AI agents coordinate. They make decisions. They take actions. Without structural constraints, they drift. Emergent behavior replaces intentional behavior. The operator loses visibility. Control erodes.

The industry response is monitoring --- observe what the agents did, detect when something goes wrong, respond after the fact. This is reactive. It is insufficient.

Archon is preventive. The rules are defined before execution. Actions are validated before they happen. The operator does not discover what went wrong. The operator defines what is allowed.

## How it works

- **Operator-defined capability boundaries** --- what the agent can and cannot do
- **Deterministic rule enforcement** --- same inputs, same decisions, every time
- **Pre-execution validation** --- actions are checked before they run, not after
- **Local decision logging** --- every validation, every decision, inspectable on your machine

Archon does not send agent activity data to CustodyZero or any third party. The logs stay on your hardware.

## Why open source

The coordination layer that governs your agents should be auditable. That is the reason Archon is open source. Not because open source is fashionable. Because the alternative --- a proprietary black box deciding what your agents can do --- is structurally wrong.

## License

Apache 2.0.

[View on GitHub](https://github.com/CustodyZero/Archon)
