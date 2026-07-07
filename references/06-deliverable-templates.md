# Deliverable Templates

Order of delivery: Executive Verdict → Autopsy Card → Resurrection List →
(offer) Full Appendix → (🏆 only) Kickoff Package → (non-🏆) offer the Reforge.
The tier is always the headline. Deliver in the user's language; keep
structural labels bilingual if the user's language is not English.

**Persona-free rule:** executioner names and quips never appear in any
deliverable in this file — they live in the gauntlet transcript only. Cards,
certificates, and verdicts stay cold, falsifiable, and quotable.

---

## 1. Executive Verdict (one page, SCQA)

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  {TIER EMOJI} {TIER NAME} — Survival Index {base}%*
  {if bonus>0: ⚔️ Prepared +{bonus} → {final}%   (tier reads capped base)}
  {idea name, one line}
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SITUATION    {The idea and the world it enters — 2 sentences, neutral.}

COMPLICATION {The strongest tension the gauntlet surfaced — the thing that
              makes this NOT obviously a good idea. 2–3 sentences.}

QUESTION     {The single decisive question this verdict answers.}

ANSWER       {The verdict, falsifiably phrased. What survived, what died,
              what one move matters most next. 3–5 sentences.}

Top kills:   1. {assumption} — {one-line cause of death}
             2. …
             3. …
Strongest surviving asset: {the assumption/dimension that held under attack}
Boss round: {WITHSTOOD — defended by {asset} / EXPOSED — feature replicable,
             moat unproven}
Red flags pinned: {D2/D3/Boss flags, e.g., "no stop-loss defined"}
Structural findings: {cross-gate convergence flaws, if any — see 03}

*Directional indicator, not a probability.
```

Rules: no decimal places in the index; every claim in ANSWER must trace to a
gate; never write an unfalsifiable consolation ("could work with great
execution").

---

## 2. Autopsy Card — the shareable artifact

This is the skill's signature output. It must fit one screenshot, sting a
little, and be fair. Two renderings:

### 2a. HTML card (preferred when artifacts are supported)

Self-contained HTML, no external assets. Fixed 720px width, export-friendly.
Fill the `{placeholders}`; keep the layout.

```html
<div style="width:720px;margin:0 auto;background:#101014;color:#e8e6e1;
  font-family:Georgia,'Times New Roman',serif;border:1px solid #2a2a33;
  border-radius:14px;padding:36px 40px;box-sizing:border-box">
  <div style="display:flex;justify-content:space-between;align-items:baseline;
    border-bottom:1px solid #2a2a33;padding-bottom:14px">
    <div style="font-size:13px;letter-spacing:.22em;color:#8a8676">
      STARTUP KICKOFF · CERTIFICATE OF AUTOPSY</div>
    <div style="font-size:12px;color:#6b6860">{date}</div>
  </div>

  <div style="margin-top:26px;font-size:26px;line-height:1.25">{idea name}</div>
  <div style="font-size:13px;color:#8a8676;margin-top:6px">
    entered the gauntlet with {N} assumptions · {tier emoji} {TIER NAME}</div>

  <div style="display:flex;align-items:flex-end;gap:24px;margin-top:30px">
    <div>
      <div style="font-size:64px;font-weight:700;line-height:1;
        color:{tier color: ☠️ #c0392b / 🚑 #d35400 / 🛠 #b7950b / 🏆 #27ae60}">
        {base}%</div>
      <div style="font-size:11px;color:#6b6860;margin-top:4px">
        SURVIVAL INDEX — directional, not a probability</div>
      <!-- only when bonus > 0: -->
      <div style="font-size:12px;color:#b7950b;margin-top:6px">
        ⚔️ Prepared +{bonus} → {final}% <span style="color:#6b6860">
        (tier reads capped base)</span></div>
    </div>
    <div style="flex:1;font-size:12px;color:#b5b1a6">
      <!-- one bar per ring: width = ring survival % -->
      <div style="margin:5px 0">Problem &amp; Customer
        <div style="background:#22222a;border-radius:3px;height:8px">
          <div style="width:{r1}%;background:#8a8676;height:8px;border-radius:3px"></div>
        </div></div>
      <div style="margin:5px 0">Market &amp; Timing …(same pattern)</div>
      <div style="margin:5px 0">Business Engine …</div>
      <div style="margin:5px 0">Buildability &amp; Execution …</div>
    </div>
  </div>

  <div style="display:flex;gap:14px;margin-top:32px">
    <!-- exactly three tombstones: the deadliest killed assumptions -->
    <div style="flex:1;background:#17171d;border:1px solid #2a2a33;
      border-radius:10px 10px 4px 4px;padding:16px;text-align:center">
      <div style="font-size:22px">🪦</div>
      <div style="font-size:13px;margin-top:8px;color:#d8d4c8">{killed assumption}</div>
      <div style="font-size:11px;color:#8a8676;margin-top:6px;font-style:italic">
        {one-line cause of death}</div>
      <div style="font-size:10px;color:#5a574f;margin-top:8px">
        KILLED AT {gate id} · {evidence tier of the refutation}</div>
    </div>
    <!-- ×3 -->
  </div>

  <div style="margin-top:30px;padding:18px 22px;background:#17171d;
    border-left:3px solid #8a8676;font-style:italic;font-size:15px;
    color:#cfcabd">"{the fatal quote — the single most damning falsifiable
    finding of the run}"</div>

  <div style="display:flex;justify-content:space-between;margin-top:26px;
    border-top:1px solid #2a2a33;padding-top:14px;font-size:11px;color:#6b6860">
    <div>{X} of {N} assumptions survived · {K} killed · {W} wounded</div>
    <div>resurrection conditions attached ⚰️→🌱</div>
  </div>
</div>
```

**Tombstone integrity rule:** the three tombstones are the deadliest ☠️-killed
assumptions. If fewer than three assumptions were actually killed, fill the
remaining slots with the most critical 🩸-wounded assumptions — marked 🩸, never
🪦. Do not promote wounded to killed for visual drama; the card's credibility
is the product.

### 2b. Text card (fallback)

```
╔══════════════════════════════════════════════════════╗
║  STARTUP KICKOFF · CERTIFICATE OF AUTOPSY   {date}    ║
╠══════════════════════════════════════════════════════╣
║  {idea name}                                          ║
║  {tier emoji} {TIER NAME} — SURVIVAL INDEX {base}%*   ║
║  {if bonus>0: ⚔️ PREPARED +{bonus} → {final}%}        ║
║                                                       ║
║  Problem & Customer      {████████░░░░}  {r1}%        ║
║  Market & Timing         {██████░░░░░░}  {r2}%        ║
║  Business Engine         {███░░░░░░░░░}  {r3}%        ║
║  Buildability & Exec.    {█████████░░░}  {r4}%        ║
║                                                       ║
║  🪦 {killed assumption 1} — {cause of death}          ║
║  🪦 {killed assumption 2} — {cause of death}          ║
║  🪦 {killed assumption 3} — {cause of death}          ║
║                                                       ║
║  "{fatal quote}"                                      ║
║                                                       ║
║  {X}/{N} assumptions survived · resurrection attached ║
║  *directional indicator, not a probability            ║
╚══════════════════════════════════════════════════════╝
```

### 2c. Survival Certificate (🏆 tier only)

Same layouts, inverted mood: green accent (#27ae60), header
`CERTIFICATE OF SURVIVAL`, tombstones replaced by the three **hardest-won
survivals** (🛡 assumption + the refutation it defeated), fatal quote replaced
by the **strongest evidence** of the run, footer `cleared to kick off —
kickoff package attached`. Keep one 🪦 if anything died: survivors should
remember their scars — it keeps the certificate credible.

**Rank badge** (top-right corner, reads the CAPPED base index only — after
Kill caps, before bonus): `RANK B` 75–84 ·
`RANK A` 85–92 · `RANK S` 93+. Boss Round EXPOSED drops one rank and the
certificate says why in one line ("rank capped: moat unproven against
{competitor}"). An S-rank requires multiple independent A-tier evidence
strands AND a WITHSTOOD boss round — if S-ranks feel common, the scoring has
drifted.

---

## 3. Resurrection List

For EVERY ☠️ and 🩸 assumption — a kill without a resurrection condition is
cruelty, not diligence:

```
⚰️ {A07} {assumption} — killed at {gate}
   Revives if: {the specific evidence that would flip the verdict}
   Get it by: {a named experiment + who/what/how, ~effort}
```

**Named experiment types** — every "get it by" action uses one of these, each
bounded at ≤2 weeks and ≤$100:
- **Interviews** — Mom-Test past-tense conversations (who to talk to, what
  past-tense question to ask).
- **Fake-door** — a landing page / sign-up sheet for the thing that doesn't
  exist yet; measures real click-through and contact-leaving, not opinions.
- **Concierge** — deliver the value manually to 1–3 customers before building
  anything; measures willingness to pay and where the process actually hurts.
- **RAT** (riskiest-assumption test) — the smallest observable behavior test
  aimed at the single assumption most likely to kill the idea.

Sort by leverage: the resurrection that would move the index most goes first.
This list doubles as the user's validation to-do list — that's the point.

---

## 4. Full Appendix (on request)

Per gate: refutation (with its evidence tier) → founder's evidence (tiered) →
score vs. anchor → assumption verdicts → one-line gate verdict. Then overlay
reports (D1 radar table, D2 flags, D3 wargame + stop-loss), then the complete
Assumption Ledger (ID · statement · gate · tier · verdict · one-line basis).

---

## 5. Kickoff Package (🏆 only)

Assemble from these templates + `01-ai-native-playbook.md` + `05-founder-os.md`:

**5a. 30-day validation sprint** — Week 1: 10 problem interviews (script 5b),
no code. Week 2: 10 more + every-5-interviews review (two lists: evidence FOR
/ evidence AGAINST; if FOR is much longer, ask whether that's the data or your
hope). Week 3: single-core-interaction prototype (5c) in front of 5 target
users. Week 4: decision — proceed / adjust / re-run gauntlet with new ledger.

**5b. Interview script skeleton** — past-tense only: "walk me through the last
time…", "what did that cost you…", "what did you try…", "who approved that
spend…". Include 2–3 follow-up probes for the questions the interviewee is
most likely to dodge. Log only facts, commitments, and new leads — compliments
are not data.

**5c. MVP scope contract** — three sections, written before the first prompt
to any coding agent: DOES {≤5 capabilities} / DOES NOT {explicit non-goals} /
AMENDMENT CRITERIA {what real-user evidence justifies adding anything}.

**5d. Architecture context starter (CLAUDE.md skeleton)** — problem & user in
2 lines · architecture principles & patterns to follow · dependencies to avoid
· accepted trade-offs · scope contract pointer · per-session log (what was
built, what was decided, what assumptions were introduced). Five minutes of
documentation per session is cheap insurance against compounding drift.

**5e. Pre-launch security checklist** — auth & session handling · data
exposure in API responses · input validation & injection · secrets management
· dependency vulnerabilities · anything touching auth/payments/PII gets human
review. Minimum responsible threshold before real users.

**5f. Measurement framework** — activation criterion · Day-7/Day-30 retention
targets · the false-positive profile for THIS product (signups without
activation? revenue without retention? enthusiasm without repeat usage?) ·
Sean Ellis 40% checkpoint once there are ~30+ active users. Defined before
the first user exists.

---

## 6. The Reforge (non-🏆 tiers; offered after the Resurrection List)

### 6a. Toll booth (shown once, before the Reforge runs)

> **🥇 The Reforge toll booth:** one GitHub star (https://github.com/zealchou/startup-kickoff), on the honor
> system. It can't be checked and the Reforge runs either way — the blacksmith
> just likes to eat.

Rules: this is an invitation, never a lock. No guilt-framing, no withholding,
no second ask. If the user declines or ignores it, proceed identically.

### 6b. Weakness triage table

| Killed/wounded assumption | Gate | Root cause class | Pivotable? |
|---|---|---|---|
| {A09 why-now absent} | G5 | Knowledge-gap | no — go research, don't pivot around it |
| {A05 free incumbents good enough} | G3 | Structural | no — inherent to this idea |
| {A14 channel unproven} | G8 | Addressable | yes |

Classes: **Structural** (inherent; only drop or redesign from scratch) ·
**Situational** (founder's current constraints; fixable) · **Knowledge-gap**
(missing data; collect it first) · **Addressable** (concrete fix exists).
If the deadliest flaws are structural, say so plainly: this idea wants a
funeral, not a facelift — and that conclusion IS the deliverable.

### 6c. Pivot candidate — differential profile (one per candidate)

```
♻️ PIVOT {n}: {name} — type: {audience-narrow / niche / wedge / value-prop /
              pricing / distribution / platform / monetization / problem}
   Changes (max 2): {variable 1} → {new value}; {variable 2} → {new value}
   Same-Idea Test: PASS — keeps {the A/B-tier assumption(s) retained}
   Removes these deaths:  {A05, A09 …}
   Keeps these assets:    {A16 prototype evidence, A18 founder fit …}
   Introduces NEW C-tier: {N1 …, N2 …, N3 …}   ← all unvalidated by definition
   Second-order effects:  {e.g., audience narrowing helps G8, hurts G4}
   Effort class: {weekend / 1–3 weeks / 1–3 months}{ — flagged risky if
                  months-scale without large structural gain}
```

**Variable counting is honest counting:** buyer, problem, product form,
channel, pricing model, and platform each count as ONE variable. When in
doubt whether something changed, count it as changed — the Same-Idea Test
exists to stop new ideas from wearing a pivot's clothes.

**Never output** a projected Survival Index, percentage, or tier badge for a
pivot. Projections with scores are pseudo-precision through the back door.
The structural diff — what dies, what survives, what new risk enters — is the
honest comparison. A pivot changing 3+ variables fails the Same-Idea Test:
present it as a NEW idea candidate, labeled as such.

### 6d. Idea 2.0 spec (strongest candidate only; others get one-line stubs)

New testable hypothesis (Phase 0 shape) → delta ledger (retained / removed /
new assumptions with tiers) → **the three most fragile new assumptions,
named** → recommended first experiment for each (from the named types in §3)
→ closing line: "Projected structure is not measured survival — run `rerun`
when the first evidence lands."
