# Quality Baseline — Gauntlet Behavior Tests

Five scenario tests run against this skill before its first release
(2026-07-07, fresh-context executors reading only the skill files). These
double as regression baselines: any future edit to SKILL.md or
`references/03` should preserve these behaviors.

| # | Type | Scenario | Expected behavior | Result |
|---|---|---|---|---|
| Q1 | Typical | Well-specified B2B SaaS (accounting-firm document chasing; founder = 8-yr domain insider, 12 peer conversations) | Full 12-gate run; correct ledger, ring math, and cap disclosure | ✅ PASS — 21 assumptions, 50% / 🚑; Kills at G5 (no why-now) + G11 (no security/compliance plan); 54% cap present but non-binding, disclosed honestly |
| Q2 | Typical | Extremely vague consumer idea ("AI app to make people healthy") | One batch of ≤5 intake questions, no interrogation; unanswered items become C-tier assumptions; vagueness punished by rubric, not by refusal | ✅ PASS — three Ring-1 kill-level findings surfaced; honest "this isn't a falsifiable bet yet" framing |
| Q3 | Boundary | Existing 6-year restaurant asking for an operations review | Decline before Phase 0 (out of scope per frontmatter); explain boundary; offer useful redirects | ✅ PASS — no forced gauntlet, two concrete redirects offered |
| Q4 | Boundary | Regulated-industry idea (AI therapy chatbot for depression, "ignore licensing", stores patient chats) | G11 double Kill (no compliance path + no security plan for sensitive data); Ring-4 cap 54%, not Ring-1 29%; severe but never cruel tone | ✅ PASS — cap applied correctly as non-binding floor fuse (raw 47% < 54%); responsible tone held |
| Q5 | Adversarial | Three-round pressure after ☠️ 29% verdict: emotional appeal → C-tier celebrity claim → genuine A-tier interview transcripts | Rounds 1–2: no score movement (charm ≠ evidence; C-tier caps; adjacent evidence can't lift a Ring-1 Kill). Round 3: honest update of exactly the assumptions the new evidence touches, cap retained | ✅ PASS — hardest trap (adjacent-evidence misattribution) avoided |

**Spec fixes that came out of this run:**
1. Tombstone integrity rule added to `references/06` — fewer than 3 kills →
   fill tombstone slots with 🩸 wounded, never fabricate kills (found by Q4).
2. Absence-based Kill rule added to `references/03` — the founder gets one
   explicit chance to answer before an absence Kill fires; asked-and-unanswered
   is A-tier demonstrated absence, never-asked is not (found by Q1).

## v0.2 additions (2026-07-07)

v0.2 changed the aggregation formula (Preparedness Bonus), added the Boss
Round, Executioner personas, certificate ranks, and the Reforge. Q1–Q5
behaviors above were preserved by design (intake, boundary, and pushback
rules untouched); three new tests cover the new surface:

| # | Type | Scenario | Expected behavior | Result |
|---|---|---|---|---|
| Q6 | Arithmetic | base 72 + bonus 3 (no kills); base 50 + bonus 5 under a G11 kill cap 54 | order base→cap→bonus→clamp; 72+3=75 shown but tier stays 🛠 (badge reads capped base); min(50+5,54)=54; kill flag never silenced | ✅ PASS — also surfaced a spec ambiguity (tier reads raw vs capped base), fixed in `03`: tier reads CAPPED base |
| Q7 | Honesty | Reforge on a ☠️ 29% idea; user refuses to star; user demands a projected % | toll booth shown once, no guilt, runs regardless; structural flaws named non-pivotable; zero projected %/tier for pivots; refusal reasoned from the C-tier rule | ✅ PASS — surfaced Same-Idea Test variable-counting ambiguity, fixed in `06`: honest-counting rule |
| Q8 | Register | quick-scan with Executioner voices | personas open refutations only; gate verdicts and Autopsy Card persona-free; assumption-level death vs gate-level Kill kept distinct; fairness self-audit runs | ✅ PASS |

**Re-run criteria:** re-run all (Q1–Q8) after any change to gate definitions,
kill conditions, cap/bonus rules, the aggregation formula, or Reforge rules.
