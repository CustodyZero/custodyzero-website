---
title: "Open Source"
description: "Tooling CustodyZero built for itself. Open because hoarding it would be a cargo cult."
---

## Why open source

CustodyZero builds the tools it needs to build CustodyZero products. The tooling that isn't itself a product we sell — the change-control system, for example — gets used internally and given back.

Most companies treat their internal tooling as competitive advantage. Most internal tooling isn't competitive advantage. It's the equipment you happen to work with. The hoard-by-default posture is a cargo cult.

If we wrote it, use it daily, and don't sell it — it's open. Apache 2.0.

---

## Factory

**A change-control system for AI-assisted development.**

We built Factory because we needed it. AI agents can write code; they cannot safely judge whether changes should ship. Factory governs the boundary between "implemented" and "accepted." Every change declares its intent and scope before implementation. Build, lint, and test gate every completion. Risk-proportional acceptance — small changes auto-accept; architectural changes require explicit human approval.

License: Apache 2.0.

[GitHub](https://github.com/CustodyZero/Factory)

---

## MCP Servers

**Best-practice corpora made queryable by coding agents.**

We built these because we needed them. AI coding agents work better when they can query authoritative knowledge instead of generating from memory. The workspace is a set of Rust-based Model Context Protocol servers, each fronting one corpus — ISO C++ Core Guidelines, C++ performance techniques, Rust API conventions, Node.js best practices — and returning indexed answers via semantic search.

License: Apache 2.0.

[GitHub](https://github.com/plainsight-systems/mcp-servers)

---

## C++ Performance Guidelines

**The technique layer below the ISO C++ Core Guidelines.**

We built this corpus because we needed it. The ISO C++ Core Guidelines tell you to minimize allocations and access memory predictably — they don't tell you how. This corpus owns the concrete technique layer: custom allocators, hardware-aware data layout, copy/move discipline, object lifetime, embedded constraints, concurrency, codegen, SIMD, and telemetry. Consumable directly, or via the cpp-perf-guidelines MCP server above.

License: Apache 2.0 (code), CC BY 4.0 (corpus content).

[GitHub](https://github.com/plainsight-systems/cpp-perf-guidelines)

---

## Contributing

These projects accept contributions. Start with the README in each repository. There is no CLA. The license is the agreement.
