# 05 — Weeks (practical)

Goal of week 1: **understand boundaries**, **set up a minimal environment**, and **make one small, correct contribution or clarification**—not to redesign the protocol.

---

## Day 1–2: Read (do not skip)

1. This repository:
   - [01-what-is-aic.md](01-what-is-aic.md)
   - [02-is-and-is-not.md](02-is-and-is-not.md)
   - [03-map-of-repos.md](03-map-of-repos.md)
   - [04-glossary.md](04-glossary.md)
2. Principle materials (“is and is not”, entity ≠ immunity) in the relevant vision/principles repo.
3. Skim Covenant criteria / go-live checklist **as criteria**, not as a launch announcement.

Write down three things AIC is **not**, in your own words. Keep them.

---

## Day 2–3: Environment (minimal)

Only set up what you need for the area you want to touch.

**Documentation / orientation only**
- Git, a text editor, ability to open Markdown and open PRs.

**TestNet / C++ oriented**
- CMake, a C++17 compiler, ability to run the project’s documented smoke tests.
- Follow the TestNet README; do not assume production deployment steps exist.

**Python / metrics / transparency sketches**
- Python 3, virtualenv/venv, pytest if tests are present.

**Website (VitePress or similar)**
- Node.js as required by that repo’s README; local preview only.

Do not run experimental nets against real users or real funds. There should be no real funds in scope under current under-claim posture.

---

## Day 3–5: One concrete action

Pick **one** of the following (not all):

| Option | Example |
|--------|---------|
| Fix or improve docs | Typo, broken link, unclear sentence in Start-Here or principles—submit a small PR. |
| Clarify an issue | Comment on an existing “good first issue” with a precise question or a minimal reproduction. |
| Add a test | One focused unit or property test in an area that already has test scaffolding. |
| Glossary / FAQ | Propose a missing term or FAQ answer with references to existing docs. |
| Map accuracy | Correct a stale repository description in the map after checking the target README. |

Avoid:

- Large architectural rewrites in week 1.
- New tokenomics, “mainnet” plans, or binding policy invented in a PR description.
- Silent changes to fail-closed or human-gate behavior.

---

## Day 5–7: Reflect and communicate

- Re-read your three “is not” statements. Still accurate?
- If you opened a PR or issue, respond to review; prefer small follow-ups.
- If something in the public narrative feels over-claimed, document the gap with links instead of only discussing it in private chat.

---

## Success criteria for week 1

You have:

1. Read the orientation and boundary documents.
2. Avoided over-claim language in anything you published.
3. Completed one small, reviewable contribution **or** one high-quality clarifying question with references.
4. Not treated any experimental component as production or Covenant-live.

That is enough. Depth comes later.

---

## Next

[06-how-to-contribute.md](06-how-to-contribute.md)