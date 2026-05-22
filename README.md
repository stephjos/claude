[README.md](https://github.com/user-attachments/files/28131559/README.md)
# Pre-Engagement Intelligence System

A personal Claude skill for marketing-communications-PR practitioners to prepare deeply and deliberately for first client meetings — before anyone is in the room.

---

## The problem this solves

Most practitioners arrive at a first meeting having done surface research: a scan of the website, a look at social media, perhaps a read of recent press. That preparation produces competence. It rarely produces the moment where everyone in the room says *"we hadn't even considered that in that light before."*

This skill is built for that second outcome. It is a structured thinking companion that walks a practitioner through five progressive layers of pre-engagement inquiry — from the world the company inhabits to the single question that reframes their situation for everyone in the room. It does not generate a report. It produces a prepared practitioner.

---

## How it works

The system moves through five layers in sequence. Each layer builds on the one before it. Each layer is held to the same triple standard before the practitioner proceeds.

| Layer | Driving Question |
|-------|-----------------|
| 1: The World | What world does this company live in? |
| 2: The Identity | What does this company say it is, and what does its behaviour suggest it actually is? |
| 3: The Tensions | Where are the live contradictions the company is too close to see? |
| 4: The People | Who will be in the room, and what do they most need to hear? |
| 5: The Generative Question | What is the single question that lifts the fog for everyone simultaneously? |

### The Triple Standard

Every output of every layer must pass three tests before proceeding.

- **Lucid.** Can it be stated plainly, without jargon or hedging?
- **Grounded.** Can it be supported by at least two concrete, observable data points — not hypothesis?
- **Oriented toward flourishing.** Does it serve the client's genuine good?

### The Guardianship Spine

A vertical lens that travels through all five layers simultaneously. It is not a checklist. It is a posture — the practitioner's ongoing responsibility to the brand's integrity, its stakeholders, and its genuine good. At each layer it asks a specific question about what this brand is responsible for and whether the evidence suggests it is meeting that responsibility.

---

## Design principles

This skill was purpose-built through a structured design process. Several principles shaped its architecture.

**The system carries the structure. The practitioner brings the presence.** The skill is designed for a practitioner who does not rely on memory to hold a framework together. It holds the framework so the practitioner can be fully present in the room.

**Depth through questions, not through information.** The fog-lifting moment comes not from knowing more than the client but from seeing something in their situation that they have been too close to see themselves. Every layer is designed to sharpen perception, not merely accumulate data.

**Lucidly grounded optimism.** Every finding must be tied to concrete, observable evidence. And every finding must be oriented toward what becomes possible, not merely what is broken. This is the standard the system holds the practitioner to at every stage.

**Digital footprints as cross-layer evidence.** The company's full digital presence — website, social media, review platforms, employee signals, search behaviour, earned media, archived content — is treated as evidence that feeds into multiple layers simultaneously, not as a separate audit track.

---

## File structure

```
pre-engagement-intelligence/
├── README.md                        — This file
├── SKILL.md                         — Core skill: system overview, triple standard,
│                                      guardianship spine, layer table, sequencing
└── references/
    ├── layer-1-world.md             — Industry, cultural moment, competitive landscape,
    │                                  macro forces, digital signals
    ├── layer-2-identity.md          — Stated identity, lived identity, external testimony,
    │                                  full digital footprint audit, message architecture,
    │                                  content ecosystem
    ├── layer-3-tensions.md          — All tension types, digital divergence signals,
    │                                  guardianship severity assessment, root cause
    │                                  orientation
    ├── layer-4-people.md            — Stakeholder profiling, digital person-reading,
    │                                  room dynamics, charity-grounded framing
    └── layer-5-question.md          — Synthesis method, reframe identification,
                                       question formulation, grounding check,
                                       the surprise question
```

---

## Installation

1. Download `pre-engagement-intelligence.skill` from the releases section of this repo.
2. In Claude, go to **Settings** and navigate to **Skills**.
3. Upload the `.skill` file.
4. The skill is now active.

---

## How to use it

Speak naturally. The skill is designed to trigger on the phrases you would actually use, not on a formal command.

Any of the following will activate it:

- *"I have a meeting with [company name]. Help me prepare."*
- *"New client: [company name]. Let's run the system."*
- *"I need to understand [company name] before I meet them."*
- *"Help me prepare for [company name]."*
- *"New client brief — [company name]."*

Claude will ask for the company name if not already given, and any initial context already in hand. If there is none, the system starts from zero. Claude then walks through all five layers in sequence, prompting for concrete data at each stage and building clarity progressively.

---

## Intended use and ownership

This skill was designed for a specific practitioner's context — a marketing-communications-PR consultant operating at the intersection of brand strategy, client advisory, and communications practice. It reflects a particular standard of preparation, a particular epistemological posture, and a particular understanding of what good practitioner work produces.

It may be adapted for other practitioners, but should be understood as a purpose-built system rather than a generic template. The methodology behind it is intentional at every level.

---

## Compatibility

Requires Claude (claude.ai or Claude API). No external tools or dependencies needed. Works within any Claude project or standard conversation where the skill is installed.

---

## Version

`1.0.0` — Initial release.
