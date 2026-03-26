---
title: "Philosophy"
description: "The constraints that govern everything CustodyZero builds. Local-first. Deterministic. Zero custody."
---

## The constraint

The person using the thing should own and control the thing.

This is not a feature. It is not a differentiator. It is a constraint on everything we build, everything we say, and everything we ship.

If a product requires you to trust us with your data, your decisions, or your infrastructure, the product is wrong.

## What custody means

Most technology companies want custody of your data. That is their business model. Your footage lives on their servers. Your documents sync to their cloud. Your agents report to their infrastructure. You get the capability. They get the control.

The industry called this progress. We call it a bad trade.

CustodyZero exists because the trade was never necessary. The capability and the control were never in conflict. The industry separated them because separation is profitable --- not because it is required.

## Local-first is not a feature

Local-first is an architectural constraint. It means:

- Data and processing stay on your hardware by default.
- No cloud account is required for core functionality.
- No telemetry. No analytics. No phone-home.
- If data leaves your machine, that behavior is explicit, opt-in, and documented.

This is not "local-optional." It is not "works offline too." The system is designed to run on your hardware, under your control, without requiring you to trust anyone else.

## Determinism is a design requirement

If a system cannot produce the same output from the same input, it cannot be trusted.

CustodyZero products are deterministic by default. Sources of time, randomness, and external state are explicit and controlled. Hidden state is a design failure. Ambient configuration is forbidden.

This matters because systems that behave unpredictably cannot be governed. And systems that cannot be governed should not be deployed.

## Governance is not bureaucracy

Governance is the structural enforcement of constraints. It exists to reduce ambiguity, not add friction.

When CustodyZero says a product "enforces operator-defined rules," that is governance. When Factory requires every change to declare its intent before execution, that is governance. When Type lets the writer invoke the Assist explicitly rather than running it in the background, that is governance.

The operator decides what happens. The system enforces the decision. The logs prove it happened.

## Open source is an architectural decision

When CustodyZero open sources a project, it is making a structural claim: this system's behavior should be inspectable, reproducible, and modifiable by the people who depend on it.

Open source is not generosity. It is not a growth strategy. It is a transparency constraint applied to systems where auditability matters more than commercial control.

The coordination layer that governs your agents should be auditable. The change-control system that gates your deployments should be auditable. These are not gifts. They are architectural positions.

## The instrument model

CustodyZero builds instruments, not platforms.

An instrument is a tool with craft. You buy it. It is yours. It does not stop working if you stop paying. You own what you produce with it. The manufacturer does not have a kill switch.

A platform is a thing you build on top of. The platform owner controls the foundation. They can change the rules. They can revoke access. They can raise prices. You are a tenant.

CustodyZero does not build platforms. CustodyZero builds instruments.

## Perpetual ownership

CustodyZero sells perpetual licenses. You buy the product. It is yours. It does not stop working.

Updates --- new features, new capabilities, new integrations --- are a separate, ongoing relationship. If you stop paying for updates, the product you bought continues to work exactly as it did the day you bought it. Nothing is revoked. Nothing degrades.

Security patches continue for as long as the codebase can support them. The limit is practical, not commercial: when the product has evolved far enough that backporting a fix is no longer technically viable, support for that version ends. This is stated plainly and in advance.

A subscription that kills the product on cancellation is a form of custody. The vendor holds a kill switch. CustodyZero does not hold kill switches.

## What we never do

These are not guidelines. They are constraints.

- **No collecting data we do not need.** If a product works without it, we do not collect it.
- **No gating local functionality behind a subscription.** Core processing runs on your hardware, always.
- **No silent data transmission.** If data leaves your machine, you opted in and you know where it goes.
- **No kill switches.** Products you buy continue to work. Period.
- **No making AI the identity.** We build instruments. The LLM is a component, not the product.

## The position

Every product decision runs through one filter. If it empowers us more than it empowers you, it does not ship.

The capability is yours.
