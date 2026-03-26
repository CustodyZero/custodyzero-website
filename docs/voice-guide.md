# CustodyZero Voice Guide

Version 1.0 -- March 2026

*Internal. Not published. This document governs how CustodyZero speaks across all surfaces -- website, product copy, documentation, and communications.*

---

## The Name

CustodyZero. Zero custody. We build the instrument. You keep everything.

The name is the philosophy. There is nothing to explain beyond what the name already says.

---

## The Core Belief

**The person using the thing should own and control the thing.**

This is not a feature. It is not a differentiator. It is a constraint on everything we build, everything we say, and everything we ship.

If a product requires the user to trust us with their data, their decisions, or their infrastructure, the product is wrong.

---

## Voice Principles

### 1. Declarative, not persuasive

CustodyZero states what it builds and why. It does not sell. It does not convince. It does not ask you to imagine a better future.

> **Wrong:** "Imagine a world where your security cameras don't send footage to the cloud."
>
> **Right:** "Watch processes video on your hardware. Footage does not leave your network."

The product either does the thing or it does not. Describe which.

### 2. The name is the explanation

Product names are common nouns. One word. The name tells you what it does.

- **Factory** builds things.
- **Type** writes things.
- **Watch** watches things.
- **Shop** sells things.

If the name requires a tagline to be understood, the name is wrong.

### 3. Constraints, not guidelines

When CustodyZero says it will not do something, that is a constraint -- a load-bearing architectural decision. Not a preference. Not a current limitation. Not a roadmap item.

> **Wrong:** "We currently don't collect user data."
>
> **Right:** "We do not collect user data."

"Currently" implies the constraint might change. If it might change, it is not a constraint.

### 4. Negation before assertion

Define what the thing is NOT before defining what it IS. The incorrect framing is already in the reader's head. Clear it first.

> **Wrong:** "Type is a beautiful, local-first writing instrument with AI assistance."
>
> **Right:** "Type is not a business document tool. No spreadsheets. No tables. No dashboards. Type is a writing instrument for writers and theorists."

### 5. Warm materials, precise language

The visual identity is warm -- paper, amber, grain, off-white. The language is not. The language is precise, architectural, compressed. These are not in tension. A well-made tool can be beautiful and exact at the same time.

Do not let the warmth of the design infect the copy with softness.

---

## Register Map

CustodyZero speaks to different audiences. The voice does not change. The register does.

| Audience | Register | Example |
|----------|----------|---------|
| Developers | Technical, peer-level. Assume competence. State what the system does, not what it means. | "Archon enforces operator-defined rules and validates actions before execution." |
| Homeowners | Direct, protective. No jargon. State what stays local and what does not. | "Watch processes video on your hardware. Your footage stays on your network." |
| Writers | Craft-aware, respectful. The tool serves the writer. The writer is sovereign. | "Type reads your work and offers suggestions in the margin. Like a human editor, not a rewrite engine." |
| Everyone (homepage) | Declarative, philosophical. The manifesto register. | "Powerful technology that stays where it belongs. On your hardware. Under your rules." |

The shift is vocabulary and assumed knowledge. The posture -- direct, honest, unhedged -- stays constant.

---

## What We Never Say

These are not preferences. They are constraints.

| Banned Pattern | Why |
|----------------|-----|
| "AI-powered" / "AI-driven" | We build instruments. The LLM is a component, not the identity. Type is a writing instrument, not an AI product. |
| "Seamless" / "frictionless" | Empty claims. Describe the mechanism or say nothing. |
| "Unlock" / "empower" / "supercharge" | Marketing language. CustodyZero does not empower. It builds tools. The user already has the power. |
| "Your data is safe with us" | We do not hold your data. The sentence is structurally impossible. |
| "We take your privacy seriously" | Every company says this. The ones that mean it describe what they do not collect. |
| "Currently" before a constraint | Implies the constraint is temporary. If it is a constraint, state it as one. |
| "Best-in-class" / "world-class" / "cutting-edge" | Unverifiable. Describes nothing. |
| "Exciting" / "thrilled" / "passionate" | CustodyZero does not have feelings about its products. It has positions. |
| "Just" (minimizing) | "Just add your API key" -- minimizing complexity is dishonest. State the step. |
| "We believe" | State the constraint. Do not attribute it to belief. "We believe in privacy" is weaker than "We do not collect user data." |

---

## How We Talk About Open Source

Open source is not a marketing strategy. It is an architectural decision made visible.

When CustodyZero open sources a project, it is making a structural claim: **this system's behavior should be inspectable, reproducible, and modifiable by the people who depend on it.**

Rules:

- Do not frame open source as generosity. It is an architectural decision.
- Do not frame open source as a growth strategy. It is a transparency constraint.
- Do not separate open source projects from the rest of the portfolio as a lesser category. They are products with the same design standards.
- State the license. Apache 2.0 or MIT. The audience knows what these mean.

> **Wrong:** "We're proud to open source Archon to give back to the community."
>
> **Right:** "Archon is open source under Apache 2.0. The coordination layer that governs your agents should be auditable."

The reason is structural, not sentimental.

---

## How We Talk About Proprietary Products

CustodyZero sells proprietary products. This does not contradict the transparency philosophy.

The constraint is: **we do not hold custody of your data.** The constraint is not: we do not sell software.

Rules:

- Proprietary products run on the user's hardware, under the user's control.
- The user pays for the instrument. They own what they produce with it.
- No product gates core local functionality behind a subscription.
- If a product sends data anywhere, that behavior is explicit, opt-in, and documented.

> **Wrong:** "Type is a premium, proprietary writing experience."
>
> **Right:** "Type is a writing instrument. It runs on your machine. Your project directory is yours -- local disk, iCloud, wherever you keep it. No cloud account required."

The proprietary/open distinction is a licensing fact, not a brand tension. Do not treat it as something that needs to be reconciled.

---

## Naming

Product names follow one rule: **the name is the function.**

| Product | What It Does | Why the Name Works |
|---------|-------------|-------------------|
| Factory | Builds software artifacts under change control | A factory makes things |
| Type | Writes long-form prose | A typewriter types |
| Watch | Monitors your home with cameras | A watch watches |
| Shop | Sells hardware | A shop sells things |
| Archon | Governs agent behavior | An archon rules |

Names are common English nouns. One word. No suffixes (-ify, -ly, -io, -ai). No portmanteaus. No invented words.

If you have to explain the name, the name is wrong.

### CustodyZero itself

CustodyZero is the exception -- it is a compound. But it follows the same rule. Custody + Zero. The name states the constraint: zero custody. We hold nothing of yours.

### Sub-product naming

When a product has iterations or variants, the modifier is equally plain:

- **Watch** is the product. The first release targets home users with any webcam. The name does not change. The scope narrows through description, not naming.

Do not version-name products (Watch Pro, Watch 2.0, Type Enterprise). If the product changes enough to need a new name, it is a new product.

---

## Vocabulary

### Words we use

| Word | Meaning in CustodyZero context |
|------|-------------------------------|
| Instrument | A tool with craft. Not "platform," not "solution." |
| Local-first | Data and processing stay on the user's hardware by default. Not "local-optional." |
| Constraint | A load-bearing design decision. Not a limitation. |
| Boundary | Where one system's authority ends and another begins. |
| Deterministic | Produces the same output from the same input. A requirement, not a feature. |
| Governance | Structural enforcement of constraints. Not bureaucracy. |
| Operator | The person who controls the system. Not "user" (too passive) in technical contexts. |
| Surface | Where work happens -- the writing surface, the detection surface. Not "interface." |
| Control | Architectural authority. Who decides. Not a knob on a dashboard. |

### Words we avoid

| Word | Why |
|------|-----|
| Platform | Implies a thing you build on top of. CustodyZero ships instruments, not platforms. |
| Solution | Meaningless. Describe what the product does. |
| Ecosystem | Implies network effects and lock-in. We ship standalone tools. |
| Smart (as adjective for products) | "Smart home" -- state the capability instead. |
| User | In product copy, prefer "you." In technical docs, prefer "operator" or the specific role (writer, homeowner). |
| Leverage | Never. |
| Disrupt | Never. |
| Journey | Never. |
| Delightful | Never. |
| Robust | Not without describing the mechanism that makes it so. |

---

## Relationship to the Founder's Voice

CustodyZero inherits from Andrew Hunter's voice: declarative compression, structural framing, negation-first moves, no hedging on earned claims.

But CustodyZero is a product voice, not an essayist's voice. The differences:

| Andrew Hunter | CustodyZero |
|---------------|-------------|
| Diagnoses problems | States what it builds |
| Essay structure: mechanism, then verdict | Product structure: constraint, then capability |
| Cool, analytical, sometimes bleak | Direct, matter-of-fact, occasionally warm through materials rather than language |
| Writes for practitioners and peers | Writes for anyone who values control |
| Closes with structural consequence | Closes with what the product does |

The DNA is the same. The format is different. Andrew writes essays. CustodyZero writes product copy, documentation, and manifestos.

When both voices appear on the same surface (e.g., a blog post by Andrew on the CustodyZero site), Andrew's voice leads. CustodyZero's branding supports. They do not compete.

---

## Licensing and Pricing

### The Model

CustodyZero sells perpetual licenses. You buy the product. It is yours. It does not stop working.

Updates -- new features, new capabilities, new integrations -- are a separate, ongoing relationship. If you stop paying for updates, the product you bought continues to work exactly as it did the day you bought it. Nothing is revoked. Nothing degrades. Nothing phones home to check whether you are still paying.

This is the zero-custody constraint applied to the business model. A subscription that kills the product on cancellation is a form of custody -- the vendor holds a kill switch. CustodyZero does not hold kill switches.

### Security Patches

Security patches are not feature updates. They are maintenance of a product you already own.

CustodyZero provides security patches for purchased versions for as long as the codebase supports it. The constraint is practical, not commercial: when the product has evolved far enough that backporting a fix to an old version is no longer technically viable, support for that version ends. This is the same model used by major platform vendors -- not an arbitrary cutoff, but a structural limit of maintainability.

When a version approaches end-of-security-support, we state it plainly and in advance. No surprise deprecations.

### How We Talk About It

The language is plain. No "licensing tiers." No "plans." No pricing tables that exist to make the middle option look reasonable.

> **Wrong:** "Choose the plan that's right for you."
>
> **Right:** "You buy it. It is yours. Updates are optional. The product does not stop working if you stop paying."

> **Wrong:** "Subscribe to Type Pro for $X/month."
>
> **Right:** "Type costs $X. You own it. Pay for updates when you want them."

Do not use the word "subscription" for the update relationship unless legally required. Prefer "update license" or simply "updates." The purchase is the product. Updates are the ongoing service.

### What This Means for Each Product

| Product | Model |
|---------|-------|
| Factory | Free. Open source. Apache 2.0. |
| Archon | Free. Open source. Apache 2.0. |
| Type | Perpetual license. Paid updates. Runs on your machine regardless. |
| Watch | Hardware purchase includes software. Perpetual license. Paid updates optional. Core local processing never gated. |
| Shop | Storefront. Not a licensed product. |

### The Constraint

No CustodyZero product may be designed such that cancelling a payment causes the product to stop functioning. If the architecture makes this difficult, the architecture is wrong.

---

## Sentence Patterns

Patterns that carry the CustodyZero voice. Not templates -- structures.

**The constraint declaration:**
> "Type does not send data to CustodyZero. There is no telemetry. No analytics. No phone-home."

**The negation-first product description:**
> "Watch is not a cloud security system. It is a local detection engine that runs on your hardware."

**The architectural reason:**
> "Archon is open source under Apache 2.0. The coordination layer that governs your agents should be auditable."

**The one-sentence closer:**
> "The capability is yours."

**The what-stays / what-goes pattern:**
> "Your project directory is yours. Your footage stays on your network. Your agent activity logs stay on your machine."

---

## Tone Calibration by Surface

| Surface | Tone | Notes |
|---------|------|-------|
| Homepage manifesto | Declarative, philosophical. Compressed. Every sentence earns its place. | This is the brand at its most concentrated. No filler. |
| Product page | Direct, specific. State what the product does, what it does not do, and what stays local. | Lead with the negation-first move, then the capability. |
| Documentation | Technical, precise. No personality. The docs serve the operator. | Assume competence. State the mechanism. |
| Legal pages | Plain language where possible. No legalese beyond what is required. | Still CustodyZero's voice -- direct, clear, no hedging. |
| Error messages | Honest. State what happened and what the user can do. | Never blame the user. Never minimize the problem. |
| Release notes | State what changed and why. No celebration. | "Added X" not "We're excited to announce X." |

---

*This document is the governing constraint for all CustodyZero communications. It is not a suggestion. It is load-bearing.*
