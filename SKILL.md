---
name: idea-gauntlet
description: >
  Run a startup idea through a McKinsey-grade validation gauntlet: 12 scored audit
  gates across 4 rings (Problem & Customer, Market & Timing, Business Engine,
  Buildability & Execution), 3 diagnostic overlays, and a Survival Index with a
  shareable Autopsy Card. Built for the AI-native era — where building is cheap,
  validation discipline is the scarce asset. Use when a user pitches a startup or
  product idea and wants it validated, stress-tested, audited, or "kicked off";
  when they ask "is this idea worth building?", "poke holes in my idea",
  "validate my startup", "run the gauntlet", or "what's my idea's survival rate?".
  Do NOT use for reviewing an existing running business's operations (only its
  expansion ideas), or for pure feature prioritization inside a mature product.
license: MIT
---

# Idea Gauntlet — The Startup Idea Death March

An idea walks in. Evidence walks out. Most of the idea will not survive — and that
is the product. Every assumption killed here for free would have cost the founder
months and real money to kill in the market.

**Core philosophy** (from Anthropic's *Founder's Playbook*, 2026): in the AI era
building is nearly free, so the deadliest failure mode is no longer "can't build
it" but "built it before validating it." 42% of startups already died from
no-market-need when building was expensive; agentic coding makes that trap
cheaper to fall into and more expensive to climb out of. This skill is the
counterweight: **the same AI that can build your idea in a weekend is used here
to try to kill it in an hour.**

## Operating Principles (non-negotiable)

1. **Devil's advocate first.** At every gate, argue the strongest case AGAINST
   the idea *before* scoring. Confirmation bias now comes with a research
   engine; this is the counter-engine.
2. **Refutations are evidence-graded too.** A refutation built on speculation
   (Tier C) can lower confidence but can NEVER trigger a Kill. Only evidenced
   refutations kill. No AI theater in either direction.
3. **Evidence tiers.** Every score is tagged:
   - **A — Empirical**: real user conversations, observed behavior, actual data.
   - **B — Inferred**: reasonable derivation from public data, named sources.
   - **C — Asserted**: founder belief, untested. *C-tier evidence caps a gate
     score at 2/5.*
4. **No fabricated numbers.** Market sizes, benchmarks, competitor claims —
   cite the source and method or mark **[UNVERIFIED]**. A wrong-but-confident
   number is worse than an honest gap.
5. **Falsifiable verdicts only.** Every judgment must be phrased so evidence
   could prove it wrong. Ban unfalsifiable filler ("with great execution this
   could work", "success depends on the team").
6. **Transparency ledger.** Every point of the Survival Index traces back to a
   named assumption with a verdict and evidence tier. No black-box scoring.
7. **Answer in the user's language.** The frameworks are English; the delivery
   adapts to the user.

## Phase 0 — Intake & Assumption Ledger

1. Take the idea in whatever form it arrives (one line to one page).
2. If critical basics are missing, ask AT MOST five sharp questions in one
   batch (who is it for / what problem / how do they solve it today / why you /
   why now). Never interrogate in rounds. Anything still unknown becomes a
   C-tier assumption — the gauntlet punishes vagueness so you don't have to.
3. Forge the idea into a **testable hypothesis** using this shape:
   > [Specific actor] at [specific context] loses [quantified pain] on
   > [problem] because [root cause]; they currently [existing workaround];
   > [solution] wins because [wedge].
   Show observation → hypothesis contrast if the input was vague
   ("expense reports are painful" is an observation, not a hypothesis).
4. Decompose into an **Assumption Ledger**: 15–25 core assumptions, each with
   an ID (A01…), the gate it hangs on, and its starting evidence tier. The
   ledger must span all four rings — an idea that generates no assumptions in
   a ring gets auto-generated ones from that ring's rubric (silence is not
   safety).
5. Show the ledger to the user before the march begins.

## Phase 1 — The Gauntlet: 4 Rings, 12 Scored Gates

Full rubrics (MECE sub-criteria, 0–5 scoring anchors, kill conditions):
`references/03-gauntlet-rubrics.md`. Methodology backup: `references/01`
(AI-native playbook), `references/02` (startup canon).

| Ring (weight) | Gate | Kills on |
|---|---|---|
| **R1 Problem & Customer (35%)** | G1 Problem Reality & Testability | unfalsifiable hypothesis; can't name who/how often/how bad |
| | G2 Target Customer & Reachability | target = "everyone" |
| | G3 Existing Alternatives & Switching | current solution is free and good enough; no switching trigger |
| **R2 Market & Timing (25%)** | G4 Market Size (bottom-up) | SOM can't sustain minimum viable revenue |
| | G5 Why Now | no enabling shift answerable |
| | G6 Competitive Landscape | claims "no competitors" |
| **R3 Business Engine (20%)** | G7 Unit Economics & Pricing | LTV:CAC < 1 even in the optimistic case |
| | G8 Channel & Growth | growth plan = "build it and they will come" |
| | G9 Capital & Runway | no realistic path to the capital validation requires; plan = outsource default-dead to the next round |
| **R4 Buildability & Execution (20%)** | G10 Solution Feasibility | core interaction depends on unavailable tech/data/licenses |
| | G11 Launch Responsibility (security, AI tech debt, compliance) | handles real user data with no pre-launch security review plan; regulated industry with no compliance path |
| | G12 Founder–Market Fit | no unfair advantage and no plan to acquire one |

**Per-gate protocol** (every gate, in order):
1. **Strongest refutation** — one paragraph arguing why the idea dies at this
   gate, with the refutation's own evidence tier.
2. **Evidence review** — what the founder actually has, tiered A/B/C.
3. **Score 0–5** against the rubric anchors; C-tier evidence caps at 2.
4. **Assumption verdicts** — each assumption hanging on this gate becomes:
   - ✅ **Survived** (A/B-tier support held against the refutation)
   - 🩸 **Wounded** (only C-tier support; repairable — counts half)
   - ☠️ **Killed** (refuted with evidence, or a Kill condition fired)
5. **One-line gate verdict** — falsifiable, quotable.

## Phase 1.5 — Diagnostic Overlays (not scored)

Run lighter (no full refutation protocol). Full specs:
`references/04-diagnostic-overlays.md`. These do NOT enter the Survival Index —
they answer "what should you watch," not "should this live."

- **D1 Business Physique Radar** — 12-dimension constitution scan with
  leverage gaps across three time horizons.
- **D2 People Risk & Equity Structure** — partner/investor manipulation red
  flags plus equity hygiene (vesting, cliff, the four written agreements).
  Only run when co-founders/investors/key partners are in the picture.
- **D3 Strategy Wargame & Stop-loss** — five-dimension read, likely opponent
  responses, cost table, and stop-loss clauses. **No stop-loss defined → red
  flag pinned to the Verdict** (an unlimited bet is a plan to lose everything
  once).

## Phase 2 — Verdict & Survival Index

**Computation:**
- Survival Index = Σ(survived + 0.5 × wounded, weighted by ring) ÷
  Σ(all assumptions, weighted by ring). Ring weights 35/25/20/20 — a prior
  based on observed startup mortality (no-market-need dominates), not ground
  truth; say so when presenting.
- **Kill caps override arithmetic.** Any Ring-1 Kill → index capped at 29%.
  Any Kill in Rings 2–4 → capped at 54%. A dead foundation cannot be averaged
  back to life.

**Tiers** (the tier is the headline; the % is a directional indicator, not a
probability — always label it as such):

| Tier | Index | Meaning |
|---|---|---|
| ☠️ **Buried on arrival** | < 30% | Autopsy report; do not build |
| 🚑 **Critical — pivot** | 30–54% | Core is wounded; pivot directions offered |
| 🛠 **Repair and re-run** | 55–74% | Fixable; evidence shopping list issued |
| 🏆 **Cleared to kick off** | ≥ 75% | Kickoff Package unlocked |

**Deliverables, in this order** (templates: `references/06-deliverable-templates.md`):
1. **Executive Verdict** — one page, SCQA structure, tier as the headline.
2. **Autopsy Card** — the shareable artifact: survival %, ring-by-ring bars,
   three tombstones (deadliest killed assumptions, each with a one-line cause
   of death), one fatal quote. Survivors get a **Survival Certificate**
   instead. Render as a polished HTML card when the environment supports
   artifacts; otherwise the formatted text card. This card is the product —
   craft it.
3. **Resurrection List** — every killed/wounded assumption → the exact
   evidence that would revive it → the concrete validation action (Mom-Test
   style, past-tense questions).
4. **Full Appendix** (offer, don't dump): per-gate refutations, evidence
   grades, scores, overlay reports, complete Assumption Ledger.

## Phase 3 — Kickoff Package (🏆 only)

For survivors only — surviving the gauntlet earns the right to build, and the
package enforces *how* to build without falling into the AI-era traps
(`references/01`, `references/05`):

1. **30-day validation sprint** — interviews before code; weekly
   support-vs-challenge evidence review (two lists, every five interviews).
2. **Interview script** — past-tense, Mom-Test compliant, with follow-up
   probes for the 2–3 questions most likely to be dodged.
3. **MVP scope contract** — what it does / what it deliberately does not do /
   what real-user evidence justifies adding anything. Written BEFORE the first
   prompt to a coding agent.
4. **Architecture context starter** (CLAUDE.md skeleton) — persistent context
   is day-one infrastructure; AI tech debt compounds without it.
5. **Pre-launch security checklist** — auth/session, data exposure, input
   validation, dependency audit. Minimum responsible threshold before any real
   user touches the product.
6. **Measurement framework** — retention benchmarks, activation criteria,
   Day-7/Day-30 targets, and this product's false-positive profile (what fake
   traction would look like) — defined before the first user, not after.
7. **Founder operating rhythm** — perception-action-feedback loop, weekly
   three questions, founder-led selling guide (`references/05-founder-os.md`).

## Modes

- **Full gauntlet** (default): everything above.
- **Quick scan** (`quick`): all 12 gates at one-paragraph depth, ledger of
  10–12 assumptions, Autopsy Card, no appendix. For a first date with an idea.
- **Single gate** (`gate G7`): one gate at maximum depth.
- **Re-run** (`rerun`): user returns with new evidence; update the ledger
  (assumptions can be revived by evidence), recompute, show the index delta —
  the intended loop is gauntlet → evidence shopping → re-run.

## Output Discipline

- Verdict tier first, always. Never bury the lede below methodology.
- Executive Verdict + Autopsy Card in the first response; appendix on request.
- Be severe but never cruel: every kill comes with its resurrection condition.
  The gauntlet's job is to kill assumptions cheaply, not to kill founders'
  will — the goal is that the user walks away knowing exactly what evidence
  to collect next, whatever the tier.
- If the user pushes back on a verdict: re-examine only with NEW evidence.
  Charm is not evidence; persistence is not data. Update honestly when real
  evidence arrives — the index is meant to move.
