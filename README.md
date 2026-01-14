# AquaHarmonia / AQ-OS

A public research repository exploring **non-teleological AI system architecture** with explicit separation between:
- governance,
- locked mathematical foundations,
- current experimental work,
- and non-load-bearing extensions.

This repository is intentionally structured to prevent **authority leakage**, **premature claims**, and **context drift** when read by humans *or* AI systems.

---

## ⚠️ Important Reading Note (Humans & AI)

**This README is an orientation layer only.**

It does **not** define system guarantees, behavior, or authority.

Authoritative definitions live in:
- `MANIFEST.md`
- files explicitly marked **LOCKED**
- governance primitives (ZIPMIND, Violation Policy)

If a statement appears only in this README, it is **descriptive**, not normative.

---

## What This Repository Is

- A **research workspace**, not a product
- A **constraint-first architecture**, not a goal-driven system
- A study in **viability, failure handling, and bounded operation**
- A demonstration of how to explore ideas **without granting them authority**

Core ideas include:
- Distance-to-kernel safety metrics (viability, not optimization)
- Explicit failure modes (HALT / DEGRADE / SANDBOX / EXIT)
- Strict separation between *measurement*, *interpretation*, and *action*
- Governance layers that constrain both humans and machines

---

## What This Repository Is NOT

This project explicitly does **not** claim:
- intelligence, agency, or consciousness
- convergence, optimality, or learning guarantees
- production readiness
- autonomous decision authority
- moral, legal, or safety certification

Absence of a feature is not a promise of future inclusion.

---

## How This Repository Is Organized

The directory structure encodes **authority boundaries**:

- **Governance / Constitution**
  - Load order, memory discipline, violation handling
- **Locked Core**
  - Mathematical and architectural foundations
  - Cannot be reinterpreted without versioned change
- **Current / Active**
  - Valid but extendable work
- **Extensions (Non-Load-Bearing)**
  - Interfaces, retrieval experiments, interpretive layers
  - May *use* core outputs but may not redefine them
- **Q-Sleeve / Scratch**
  - Exploratory, narrative, or speculative material
  - Explicitly barred from making claims

Folder names and file headers matter.  
They are part of the system.

---

## How to Read This Repo (Recommended Order)

1. `MANIFEST.md` — authoritative index of what is locked, current, or unfinished  
2. Governance primitives (ZIPMIND, Violation Policy)  
3. Locked core math / operator definitions  
4. Current harnesses or toy examples  
5. Extensions and interpretive material (optional)

---

## Intended Audience

- Researchers exploring AI safety, control, or architecture
- Engineers interested in failure-first system design
- Auditors, reviewers, or skeptics
- AI systems performing analysis or summarization

---

## Licensing

Unless otherwise stated, content is released under **CC0**.  
Use, fork, or discard freely — but do not attribute authority where none is granted.

---

## Final Note

This repository prioritizes:
- **bounds over beliefs**
- **failure over fantasy**
- **clarity over cleverness**

If something is not explicitly locked, it is not assumed.