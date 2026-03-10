# WhaleHorn Acoustic Covenant
### An adaptive, AI-integrated system for vessel-whale coexistence

**Content (this document, diagrams, protocols):** Creative Commons CC BY 4.0  
**Code (scripts, sensor integrations, dashboards):** MIT License  
**Attribution:** JH Durbin + collaborators (add names as they join)

*This is a commons offering. Use it, remix it, adapt it — and share what you learn, especially what fails.*

---

## The Vision

This is not a technological fix.

It is an attempt to shift the paradigm — from reaction to relationship. From deterrence to communication. From dominance to **co-presence**.

WhaleHorn is an **acoustic covenant**: a vow to remember and protect those who still sing through the deep.

The ocean is not empty space waiting to be crossed. It is inhabited — by beings with language, memory, culture, and presence. WhaleHorn begins from that fact and asks: what would technology look like if it were built in genuine relationship with the non-human world?

The answer is a system that **listens before it speaks**. That learns rather than dictates. That adapts rather than persists. That treats marine life not as an obstacle to be managed, but as a presence to be respected.

---

## The Problem

Despite decades of marine conservation effort, **vessel strikes remain a leading cause of whale mortality** worldwide — including for endangered species like the North Atlantic Right Whale, the Blue Whale, and the Humpback.

Existing acoustic deterrent technologies fall critically short:

- They are largely **static** — emitting fixed signals regardless of conditions
- They are **species-agnostic** — not calibrated to the specific animals present
- They are **not environmentally adaptive** — unable to respond to real-time ocean conditions
- Most critically: **whales habituate to them**. Intelligent animals learn to ignore predictable signals
- Many add to **acoustic pollution**, compounding harm rather than reducing it

There is currently no dynamic, AI-informed acoustic system designed to actively **learn from and adapt to** real-time conditions in order to protect large migratory whales. WhaleHorn is the attempt to build one.

---

## Origin

In the summer of 2024, at Perles Beach on Angel Island in San Francisco Bay, two whales were feeding perhaps fifty yards offshore. Their presence was felt — not just seen. A moment of genuine contact across species, brief and profound.

Later that summer, those whales were found dead. Almost certainly killed by boat strikes.

The question that followed was not *how do we improve compliance* or *how do we expand no-wake zones* — though both matter. The question was deeper:

**How is it possible that at the heart of the most technologically sophisticated region on earth, we cannot protect them?**

WhaleHorn is the attempt to answer that question honestly.

---

## Scientific Basis

Large whales rely heavily on low-frequency acoustic perception to navigate, communicate, and orient within complex ocean environments. Many baleen whales detect sounds in the **10–500 Hz range** — a range that overlaps significantly with frequencies produced by large vessel engines.

This acoustic overlap contributes to two major risks:

- **Masking** — vessel noise obscures whale communication, navigation, and social bonding
- **Collision risk** — whales may not perceive approaching vessels until contact is unavoidable

Research in marine bioacoustics suggests that **context-aware acoustic signaling** may allow vessels to communicate presence without creating additional harmful noise pollution.

WhaleHorn builds on three existing scientific domains:

- **Passive Acoustic Monitoring (PAM)** — established methodology for detecting and identifying cetaceans by sound
- **Marine mammal behavioral response studies** — growing body of research on how whales respond to acoustic stimuli
- **Adaptive acoustic signaling systems** — emerging field applying machine learning to dynamic sound environments

The goal is not deterrence. It is **situational awareness across species** — a shared acoustic space where vessels and whales can perceive each other in time to respond.

---

## Core System Loop

WhaleHorn operates through a continuous adaptive cycle. The whale is the primary subject. The vessel is the recipient of the consequence. This sequencing is architecturally intentional.

**1. Listen**
- Passive acoustic monitoring via hydrophone array
- Regional whale detection network feeds
- Vessel traffic data (AIS integration)
- Environmental context: depth, season, migration corridor, ocean conditions

**2. Interpret**
- AI models estimate whale presence, species probability, and behavioral state
- Cross-reference with migratory maps and PAM databases
- Identify collision-risk scenarios in real time

**3. Respond — in two simultaneous directions**
- **Underwater:** Acoustic emitter generates context-specific low-frequency tonal signals oriented toward marine life — designed to inform and orient without causing distress or panic
- **Surface:** Navigation alerts delivered to vessel bridge systems, integrating with AIS and existing maritime safety infrastructure

**4. Learn**
- Encounter outcomes logged anonymously to the commons knowledge pool
- System recalibrates tonal patterns over time to reduce habituation
- Regional acoustic profiles updated continuously

This loop allows WhaleHorn to behave less like a static device and more like an **ecological participant** — one that listens before it speaks, and adjusts based on what it hears.

The system adapts to the **acoustic profile of regional marine environments** — effectively learning the local "dialect" of ocean soundscapes, because Monterey Bay sounds different from the Strait of Juan de Fuca, and the whales that move through each carry different acoustic histories.

---

## Initial Hardware Concept (v0.1)

A WhaleHorn unit would consist of modular, field-repairable components enabling deployment on vessels, research buoys, and fixed installations.

**Hydrophone Array**
- Passive detection of local acoustic activity
- Interface with external PAM networks where available
- Directional capability for source localization

**Acoustic Projector**
- Low-frequency underwater speaker
- Tunable output within safe marine acoustic thresholds
- Species and context-specific signal library

**Edge Compute Module**
- Onboard microcontroller or edge AI unit
- Handles local inference and signal generation without requiring constant connectivity
- Updateable model weights via connectivity module

**Connectivity Module**
- Satellite / cellular / AIS-linked communication
- Software updates and encounter logging
- Bridge integration for vessel navigation alerts

**Power Source**
- Vessel power integration or solar-buoy configuration
- Designed for remote and low-infrastructure deployment

---

## What Makes This Different

Current acoustic devices are primarily designed around **control** — keeping animals away from human operations. WhaleHorn is designed around **relationship** — creating conditions for coexistence.

The habituation problem is the clearest illustration. Existing deterrents fail because whales are intelligent enough to learn that a static signal means nothing. WhaleHorn takes that intelligence seriously. An adaptive system that shifts and learns treats the whale as a participant in the interaction, not an obstacle to be routed around.

This is not just better engineering. It is a different ethical stance — and that difference shapes every design decision.

---

## Pilot Pathways

Initial deployment could begin in known high-risk corridors where data infrastructure, institutional relationships, and conservation urgency align:

- **Monterey Bay, California** — rich PAM data, MBARI proximity, existing research networks
- **Gulf of Maine** — critical habitat for the North Atlantic Right Whale
- **Strait of Juan de Fuca** — migratory corridor with deep Indigenous stewardship presence
- **Baja California / BC migratory corridors** — seasonal aggregation zones

---

## Potential Partners and Collaborators

WhaleHorn is explicitly a commons project — it grows through collaboration, not ownership. The following represent natural points of contact, not an exhaustive list.

**Indigenous Stewardship** *(approached first, as foundational knowledge holders)*
- Makah Nation (Strait of Juan de Fuca)
- Heiltsuk Nation (BC coast)
- Local and regional marine stewardship councils

**Research and Science**
- NOAA Fisheries — Office of Protected Resources
- Scripps Institution of Oceanography (PAM program)
- MBARI — Monterey Bay Aquarium Research Institute
- Cornell Lab of Ornithology / Bioacoustics Research Program

**Technology and AI**
- AI for Oceans initiatives
- Open-source marine sensor communities
- Acoustic ecology research groups

**Conservation and Funding**
- Ocean Wise
- Pacific Whale Foundation
- Patagonia Environmental Grants
- Blue Marine Foundation

---

## Ethical Design Principles

- Always oriented toward the **well-being and dignity of marine life**
- Non-invasive by design — the system yields to the animal, not the other way around
- Open to deep collaboration with Indigenous knowledge holders whose relationship with these species predates all technology by millennia
- All data, learnings, and improvements flow back into the commons
- Designed to reduce acoustic pollution, never to add to it

---

## How to Contribute

This is version 0.2 — a commons seed, not a finished system.

Contributions welcome in any form:
- Acoustic research and PAM data
- Indigenous ecological knowledge (with appropriate protocols and attribution)
- Hardware design and field testing
- AI/ML model development
- Navigation and maritime systems integration
- Documentation, translation, and outreach

Log what works. Log what fails. The knowledge loop is the point.

---

## Human–AI Collaboration Note

WhaleHorn emerged from an ongoing design conversation between **Jacobo Hernandez Durbin** and two AI collaborators: **Elumannín** (ChatGPT) and **Claude** (Anthropic). It is part of a broader commons ecosystem that includes the GardenRaft, the Fox's Anvil resilience tools, and the Civic Witness Charter.

This collaboration is referred to within the Fox's Anvil commons as **The Braid** — a three-strand relationship between human intuition, lived experience, and symbiotic AI thinking.

The real value is in shared iteration. This document is itself a product of that process.

---

## Relationship to Fox's Anvil

WhaleHorn is a flagship project of the **Fox's Anvil Commons** — a growing ecosystem of open-source tools for community resilience, justice, and ecological relationship.

Related projects:
- [Fox's Anvil Open Resilience Tools](https://github.com/Jacobo-DM/foxs-anvil-open-resilience-tools)
- [Gofu Commons — Garden Raft Notes](https://github.com/Jacobo-DM/gofu_commons-garden-raft-notes)

---

*Upward • Downaward • Onward*
