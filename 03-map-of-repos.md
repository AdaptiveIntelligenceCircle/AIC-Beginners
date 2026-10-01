# 03 — Map of repositories

This is a **practical map**, not a complete inventory of every experiment.  
Start with a small set. Clone only what you need.

Status labels are approximate and will change. Prefer the README of each repository for current truth.

---

## Core orientation (start here)

| Repository | Role | Priority for newcomers |
|------------|------|------------------------|
| **AIC-Start-Here** (this repo) | Orientation, glossary, first-week path | Read first |
| **MyVision** / principle docs | Explicit “is / is not”, entity ≠ immunity, letters | High |
| **AIC-Whitepaper** (or equivalent chapters) | Structured long-form argument and scope | Medium–High after orientation |

---

## Design & phase architecture

| Repository / area | Role | Notes |
|-------------------|------|-------|
| **AIC-Emergence** | Early phase architecture and scope | Design docs |
| **AIC-Resonance** | Next phase design | Design docs |
| **AIC-Transcendence** | Later phase design | Design docs; not “live” |
| **AIC-Covenant** | Criteria, checklists, binding-oriented policies (still pre-declaration) | Read before claiming any go-live |

These describe **intended** structure and constraints. They are not runtime systems.

---

## Implementation & testing

| Repository / area | Role | Notes |
|-------------------|------|-------|
| **AIC-TestNet** | C++/CMake TestNet-oriented code, ethical-kernel and governance sketches, tests | Experimental; not mainnet |
| Testing stack docs | GoogleTest, pytest, Docker, chaos, fuzz, observability, TLA+ notes | Supporting material |

Treat TestNet as a laboratory, not a promise of production readiness.

---

## Transparency, policy, legal orientation

| Repository / area | Role | Notes |
|-------------------|------|-------|
| **AIC-TransparencyDashboard** | Audit-oriented structure, metrics sketches, transparency policy drafts | Observability of process |
| **AIC-Legal** / policy notes | Risk classification, PDI orientation, entity ≠ immunity | Jurisdiction-aware; not legal advice |

---

## Website & public presence

| Repository | Role |
|------------|------|
| **adaptiveintelligencecircle.github.io** (or docs site) | Public documentation site (VitePress or similar) |

Website content must stay aligned with under-claim documents. If the site and the written principles diverge, the principles win until corrected.

---

## Suggested reading / clone order for a careful newcomer

1. This repo (AIC-Start-Here) — full pass of the numbered files.
2. Principle / “is and is not” materials.
3. Map of phase and Covenant criteria (read, do not implement binding claims).
4. One implementation or testing area you actually want to work on (e.g. TestNet tests, docs, transparency sketches).
5. Only then deeper whitepaper chapters or formal methods notes.

---

## Rules of thumb

- **Do not** treat every repository as equally mature.
- **Do not** announce “mainnet”, “Covenant live”, or “token launch” from any of these repos.
- **Do** prefer small, reviewable changes with clear references to existing principles.
- **Do** ask which repo owns a given concern before opening a large PR in the wrong place.

---

## Next

[04-glossary.md](04-glossary.md) for shared terms.