# Example Run — "Undertone" (AI journaling that detects early burnout)

> **This is a fictional demonstration run.** The idea, the founder, the interview
> quotes, and every market figure below are invented to show how the Idea
> Gauntlet scores, kills, and reports — none of it is real data.

**The pitch as it arrived:** "An AI journaling app that detects early burnout
from your entries."

---

## Phase 0 — Intake & Assumption Ledger

**Five sharp questions, one batch:**

1. Who is it for, specifically? → *Individual contributors, 28–40, in
   fast-growth tech and agency roles.*
2. What problem, exactly? → *They don't notice they're burning out until it's
   already cost them something — a missed deadline, a blown weekend, a fight
   with a partner.*
3. How do they solve it today? → *Mostly nothing. Some journal in Apple Notes
   or a paper notebook. A few have tried Day One or Reflectly.*
4. Why this founder? → *"I burned out badly two years ago and wished something
   had caught it earlier."*
5. Why now? → *"LLMs can finally read tone, not just sentiment score."*

**Observation → hypothesis contrast:** the raw pitch ("detects early burnout")
is an observation about a desired capability, not a testable hypothesis. It
names no actor, no frequency, no cost, and no existing workaround.

**Testable hypothesis:**

> Individual-contributor knowledge workers 3–5 years into a fast-growth career
> lose weeks of judgment, a missed deadline, or a relationship strain to
> burnout they don't notice building because their only signal is a full
> collapse; they currently journal nowhere or in tools with no reflection
> layer, or do nothing at all; an AI journal that flags the drift early wins
> because it catches the trend before the crash.

**Assumption Ledger** (17 assumptions, spanning all 4 rings; starting tier is
**C** for all — nothing has been evidence-tested yet):

| ID | Assumption | Gate |
|---|---|---|
| A01 | Target users can name a specific week their burnout became undeniable, with a quantifiable cost. | G1 |
| A02 | The pain recurs on a monthly-or-more cycle, not an annual one. | G1 |
| A03 | The reachable profile is knowledge workers 28–40 in fast-growth tech/agency roles who already journal or have tried to. | G2 |
| A04 | This profile congregates in identifiable, contactable communities. | G2 |
| A05 | Users will abandon their current free tool (Notes app, notebook, Day One) once automatic burnout detection exists. | G3 |
| A06 | A bad week or a wearable stress signal is sufficient trigger to install a new app. | G3 |
| A07 | Automatic burnout detection is itself the value users switch for — not a feature bolted onto journaling they'd do anyway. | G3 |
| A08 | The bottom-up SOM sustains at least ramen-profitable revenue for a 2-person team. | G4 |
| A09 | The three most fragile SOM inputs survive being halved. | G4 |
| A10 | A named enabling shift (cheap LLM inference + open wearable/journal export APIs) makes this newly possible. | G5 |
| A11 | The competitive set (Day One, Reflectly, and adjacent) does not already own the "automatic burnout detection" wedge. | G6 |
| A12 | LTV:CAC clears 1 even under a pessimistic churn assumption at $8–12/mo. | G7 |
| A13 | There is one named first channel with a benchmarked, testable CAC. | G8 |
| A14 | Founder can reach problem-solution fit on savings/pre-seed-sized capital before cash runs out. | G9 |
| A15 | The core interaction — inferring burnout risk from journal text — is buildable with existing sentiment/LLM APIs. | G10 |
| A16 | A pre-launch security/data-handling plan is sufficient given the sensitivity of this content. | G11 |
| A17 | The founder holds a genuine unfair advantage and a 3-year obsession horizon with this problem. | G12 |

---

## Phase 1 — The Gauntlet

### G1 · Problem Reality & Testability — Score **3/5**

**Refutation (B-tier):** this may be a vitamin, not a painkiller — people
tolerate burnout for years without buying anything, and the frequency claim
may be episodic (annual crashes, not monthly ones), which fails the
"compounds" test.

**Evidence:** 6 informal founder conversations surfaced a specific bad week
and a concrete cost — a blown client deadline, a near-breakdown weekend
(**A-tier**: real accounts of a real week). The monthly-recurrence claim is
asserted, not measured (**C-tier**).

**Verdicts:** A01 ✅ Survived (A) · A02 🩸 Wounded (C)

**Gate verdict:** *The pain is real and nameable in the moment; whether it
repeats often enough to buy a subscription instead of a coping mechanism is
still asserted.*

### G2 · Target Customer & Reachability — Score **3/5**

**Refutation (B-tier):** the person who feels the pain is energy-poor exactly
when they'd need to adopt something new — the individual contributor has no
budget of their own and no bandwidth mid-burnout to evaluate a new app.

**Evidence:** the profile (age/role/context) is precise and cross-checked
against public workplace-stress survey shapes (**B-tier**). Reachability
rests on three named communities the founder has not yet tested response
rates in (**C-tier**, asserted list).

**Verdicts:** A03 ✅ Survived (B) · A04 🩸 Wounded (C)

**Gate verdict:** *Who they are is precise; where to actually find twenty of
them within a week is still a guess.*

### G3 · Existing Alternatives & Switching — Score **1/5 — ☠️ KILL**

**Refutation (A-tier — this one lands):** 15 past-tense Mom-Test interviews
were run with people who described a recent burnout week. All 15 named a
coping action — talked to a friend, took a day off, deleted Slack for a
weekend. Zero mentioned searching for, downloading, or wanting a new app. The
existing "solution" (nothing, or free notes) is free and, in their own words,
"good enough for now."

**Evidence:** A05, A06, and A07 rest entirely on hope; the only real data
point in this ledger is the interview set, and it points the other way
(**A-tier** refutation clears the bar for a Kill).

**Verdicts:** A05 ☠️ Killed · A06 ☠️ Killed · A07 ☠️ Killed — **Kill condition
fires: current solution is free and good enough, no evidenced switching
trigger.**

**Gate verdict:** *Free and "good enough" is undefeated: 15 of 15
interviewees coped without installing anything.*

### G4 · Market Size (bottom-up) — Score **3/5**

**Refutation (B-tier):** rebuild the SOM bottom-up — roughly 40,000 reachable
profile members across the named communities *(fictional example figure)* ×
a plausible $10 ARPU × a realistic 2% 2-year capture *(fictional example)* —
and halving any one input tightens the ramen-profitable bar without breaking
it outright.

**Evidence:** A08's model uses sourced community-size inputs but hasn't been
seriously stress-tested (**B-tier**, sanity-checked). A09's halving test was
done on paper, not modeled rigorously (**C-tier**).

**Verdicts:** A08 ✅ Survived (B) · A09 🩸 Wounded (C)

**Gate verdict:** *The math works if the founder's optimistic inputs hold —
nobody has stress-tested whether it survives being wrong.*

### G5 · Why Now — Score **4/5**

**Refutation (B-tier):** the enabling shift lifts every competitor equally —
it's a tide, not a moat.

**Evidence:** A10 cites a named, dated shift — LLM inference cost per 1K
tokens down over 90% in 24 months *(fictional example figure)*, plus
wearable/journal export APIs newly opened (**A-tier**: documented pricing
history and platform changelogs).

**Verdicts:** A10 ✅ Survived (A)

**Gate verdict:** *The window is real and dated — the tide argument is fair,
but it doesn't erase the timing case.*

### G6 · Competitive Landscape — Score **2/5**

**Refutation (B-tier, the steelman IS the refutation):** Day One already has
a large installed base and zero cold-start problem — it could ship a
"reflection insights" feature in a quarter and own this wedge without a new
app ever mattering.

**Evidence:** A11's competitive scan was a one-afternoon App Store browse — no
steelman written for the strongest player, no counter-positioning argued
(**C-tier only**).

**Verdicts:** A11 🩸 Wounded (C, capped at 2)

**Gate verdict:** *No-competitor claims aside, there's no argument yet for why
Day One doesn't just ship this feature.*

### G7 · Unit Economics & Pricing — Score **2/5**

**Refutation (B-tier):** the value metric (burnout detection) is something
users will expect bundled free into any journaling app already — willingness
to pay collapses toward whatever the incumbent charges.

**Evidence:** A12's LTV:CAC is modeled from a comparable wellness-app CAC
benchmark with an optimistic churn assumption — no pre-sales, no LOIs, no
real willingness-to-pay test (**C-tier only**).

**Verdicts:** A12 🩸 Wounded (C, capped at 2)

**Gate verdict:** *The math clears 1 on paper; nobody has asked a real user to
actually pay yet.*

### G8 · Channel & Growth — Score **3/5**

**Refutation (B-tier):** content/SEO for "burnout symptoms" is crowded with
decade-old wellness and health-authority domains — real CAC on this channel
likely runs well above the founder's estimate.

**Evidence:** A13 names one channel with a directional CAC benchmarked
against comparable content-marketing figures in adjacent wellness apps
(**B-tier**).

**Verdicts:** A13 ✅ Survived (B)

**Gate verdict:** *A first channel is named and benchmarked against real
comparables — untested, but not invented from nothing.*

### G9 · Capital & Runway — Score **3/5**

**Refutation (B-tier):** the timeline to problem-solution fit usually runs
2–3x the founder's estimate, and the burn-rate math assumes the optimistic
case.

**Evidence:** A14's plan — 18 months of personal savings, no outside capital
required to reach the next milestone — doesn't outsource survival to a future
fundraise (**B-tier**: matches how solo-founder pre-seed bootstrapping
typically funds this stage).

**Verdicts:** A14 ✅ Survived (B)

**Gate verdict:** *The runway plan doesn't outsource survival to a future
round — the right shape, even if the timeline is optimistic.*

### G10 · Solution Feasibility — Score **4/5**

**Refutation (B-tier):** the demo-able version (a nice sentiment summary) and
the reliable version (something that flags real burnout without crying wolf
or missing a real crisis) are different products — the gap is the whole
product.

**Evidence:** A15 already has a working prototype classifying mood shifts
across a 30-entry test set using an off-the-shelf sentiment API, no custom
training (**A-tier**: a built artifact, not a claim).

**Verdicts:** A15 ✅ Survived (A)

**Gate verdict:** *The core interaction is genuinely buildable this week —
the reliability refutation is fair but doesn't block Ring 4.*

### G11 · Launch Responsibility — Score **2/5**

**Refutation (B-tier):** journal entries about burnout sit close to
mental-health-adjacent data — "we'll add security later" meets real users'
most private writing on day one.

**Evidence:** A16 is a general intent to "encrypt stuff," with no named
pre-launch checklist (auth/session, encryption at rest, retention policy,
access controls) (**C-tier only**, asserted).

**Verdicts:** A16 🩸 Wounded (C, capped at 2)

**Gate verdict:** *Intent to protect this data exists; a checklist doesn't
yet — and this is the wrong category of product to skip one.*

### G12 · Founder–Market Fit — Score **2/5**

**Refutation (B-tier):** "I've been burned out before" is proximity shared by
the entire target market — it's a qualifying experience, not a moat.

**Evidence:** A17 cites personal burnout history and general interest in
mental health — no clinical background, no existing audience in this space,
no distribution advantage named (**C-tier only**, asserted passion, no
acquired leverage).

**Verdicts:** A17 🩸 Wounded (C, capped at 2)

**Gate verdict:** *Caring about the problem is not the same as holding the
leverage this specific idea needs — none is named yet.*

---

## Phase 1.5 — Diagnostic Overlays (not scored)

- **D1 Business Physique Radar:** strong on build speed and iteration cost
  (AI-native ring); weak on distribution and cash reserves — a lean-body
  idea with almost no fat to survive a wrong guess.
- **D2 People Risk & Equity:** N/A — solo founder, no co-founders, investors,
  or key partners in the picture yet.
- **D3 Strategy Wargame & Stop-loss:** likely response — Day One ships a
  "reflection insights" feature within two quarters if this shows traction
  *(fictional wargame read)*. **No stop-loss was defined by the founder** →
  🚩 red flag pinned to the Verdict.

**⚔️ Preparedness Bonus** (bonus-only, max +5):

- **D1: +0** — no self-assessment was volunteered.
- **D2: N/A** — solo founder, no co-founders/investors to score.
- **D3: +0** — no stop-loss defined (already flagged as a red flag above).

**Total ⚔️ +0.** The clamp rule still applies even at zero: this run's Kill
cap is 29%, so even a perfect +5 bonus could not move the reported index —
`final = min(29 + 5, 29) = 29`. The bonus can never break through a Kill
cap; it only has room to matter on runs that didn't kill Ring 1.

---

## Phase 2 — Verdict & Survival Index

**Ring-by-ring survived mass** (✅ = 1.0, 🩸 = 0.5, ☠️ = 0.0):

| Ring (weight) | Survived mass | Ring % |
|---|---|---|
| R1 Problem & Customer (35%) | (1+0.5+1+0.5+0+0+0) / 7 | **42.9%** |
| R2 Market & Timing (25%) | (1+0.5+1+0.5) / 4 | **75.0%** |
| R3 Business Engine (20%) | (0.5+1+1) / 3 | **83.3%** |
| R4 Buildability & Execution (20%) | (1+0.5+0.5) / 3 | **66.7%** |

**Uncapped weighted arithmetic:**
`0.429×35 + 0.750×25 + 0.833×20 + 0.667×20 = 15.0 + 18.75 + 16.67 + 13.33 = 63.75%`
→ rounds to **64%**.

**But a Ring-1 Kill fired at G3.** Per the aggregation rule, any Ring-1 Kill
caps the index at 29% *regardless of the arithmetic above* — a dead
foundation cannot be averaged back to life by strong scores elsewhere.

**Final Survival Index: 29%** → Tier: **☠️ Buried on arrival** (< 30%)

---

### Executive Verdict

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ☠️ BURIED ON ARRIVAL — Survival Index 29%*
  Undertone — AI journaling that detects early burnout
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SITUATION    Individual contributors 3–5 years into a fast-growth career
             burn out without noticing until it costs them something real;
             an AI journal is proposed to flag the drift before the crash.

COMPLICATION 15 past-tense interviews with people mid-burnout show a
             consistent pattern: they cope, they don't shop. Nobody
             searched for, downloaded, or wanted a new tool — the current
             non-solution is free and, in their words, good enough.

QUESTION     Is there a switching event strong enough to move someone from
             "coping" to "installing," and does automatic detection matter
             enough to be the reason they switch?

ANSWER       Not on current evidence. The uncapped arithmetic (64%) would
             suggest a fixable idea, but the Ring-1 Kill at G3 overrides it:
             a free, "good enough" incumbent behavior beats a well-timed,
             buildable, feasible product. The single highest-leverage next
             move is not more building — it's 15 new interviews aimed
             specifically at finding a real switching trigger, not more
             evidence of the pain itself.

Top kills:   1. A07 — the automatic-detection wedge is a feature nobody
                asked to switch for
             2. A05 — free incumbents (Notes, notebook, Day One) are
                undefeated in 15/15 conversations
             3. A06 — no switching trigger has been observed, only hoped for
Strongest surviving asset: G5 Why Now — the enabling shift is real, dated,
             and A-tier evidenced
Red flags pinned: no stop-loss defined (D3)

*Directional indicator, not a probability.
```

### Autopsy Card

```
╔══════════════════════════════════════════════════════╗
║  STARTUP KICKOFF · CERTIFICATE OF AUTOPSY 2026-07-07  ║
╠══════════════════════════════════════════════════════╣
║  Undertone — AI journaling for early burnout          ║
║  ☠️ BURIED ON ARRIVAL — SURVIVAL INDEX 29%*            ║
║                                                       ║
║  Problem & Customer      {█████░░░░░░░}  43%          ║
║  Market & Timing         {█████████░░░}  75%          ║
║  Business Engine         {██████████░░}  83%          ║
║  Buildability & Exec.    {████████░░░░}  67%          ║
║                                                       ║
║  🪦 A05 — Free and "good enough" is undefeated;       ║
║      nobody traded a habit for a feature.             ║
║  🪦 A06 — 15/15 interviewees described the bad week;  ║
║      zero described downloading anything.             ║
║  🪦 A07 — the detector was the value; the interviews  ║
║      showed nobody was shopping for one.               ║
║                                                       ║
║  "People want to have journaled, not to journal."     ║
║                                                       ║
║  7/17 assumptions survived · 3 killed · 7 wounded     ║
║  resurrection conditions attached ⚰️→🌱                ║
║  *directional indicator, not a probability            ║
╚══════════════════════════════════════════════════════╝
```

### Resurrection List

*Sorted by leverage. The first three are the only ones that matter right
now — until the Ring-1 Kill is reversed, the index stays capped at 29% no
matter what else improves. Fix G3 before spending another hour on anything
else.*

```
⚰️ A05 (☠️ Killed at G3)
   Revives if: ≥8 of 15 fresh past-tense interviews describe an actual
   switching attempt (searched an app store, asked for a recommendation,
   tried and abandoned a tool) triggered specifically by a burnout episode
   — not just coping talk.
   Get it by: 15 new Mom-Test interviews via a support-group partnership,
   asking "what did you actually try last time" and counting real
   switching attempts, not sentiment. (~1 week)

⚰️ A06 (☠️ Killed at G3)
   Revives if: a documented trigger event (an HR PTO mandate, a viral
   "quiet quitting" cycle, an insurer wellness discount) shows a
   measurable install-rate bump for a comparable app.
   Get it by: pull App Store rank-history for 3 comparable wellness apps
   and correlate against 3 candidate trigger-event dates. (~2 days)

⚰️ A07 (☠️ Killed at G3)
   Revives if: a Wizard-of-Oz pilot shows users who receive a
   manually-flagged "you may be burning out" message take a real
   subsequent action (book PTO, message a manager, seek support) at a
   meaningfully higher rate than a control group getting a generic weekly
   check-in.
   Get it by: 4-week manual pilot, 20 real journalers, two arms,
   action-rate as the only metric that counts.

⚰️ A16 (🩸 Wounded at G11)
   Revives if: a named pre-launch security checklist (auth/session,
   encryption at rest, retention policy, access controls) is written and
   reviewed before any real entry is stored.
   Get it by: adapt the Kickoff Package security checklist now — before
   the next line of the ledger, not after launch.

⚰️ A17 (🩸 Wounded at G12)
   Revives if: the founder can name one acquired leverage specific to this
   idea (an existing audience of burned-out professionals, a clinical
   advisor, a distribution partnership with an EAP provider).
   Get it by: spend two weeks testing whether any of the eight founder
   leverages can be cheaply acquired before building further.

⚰️ A02 (🩸 Wounded at G1)
   Revives if: 10+ interviews confirm monthly-or-more recurrence, not an
   annual one.
   Get it by: add a past-tense frequency question to the interview batch
   above ("when were the last three times this happened").

⚰️ A04 (🩸 Wounded at G2)
   Revives if: outreach to the 3 named communities yields ≥20 qualified,
   interviewable profile matches within one week.
   Get it by: post a recruiting message in each community and count
   qualified responses, not just likes.

⚰️ A09 (🩸 Wounded at G4)
   Revives if: the SOM model still clears the ramen-profitable bar after
   halving ARPU and capture-rate simultaneously.
   Get it by: rebuild the model with both fragile inputs halved at once
   and check the output, not just one input at a time.

⚰️ A11 (🩸 Wounded at G6)
   Revives if: a written steelman for Day One's most likely response, plus
   a named structural reason they won't ship this feature, survives
   scrutiny.
   Get it by: spend a day building the four-tier competitive map and
   steelman round G6 calls for.

⚰️ A12 (🩸 Wounded at G7)
   Revives if: 10 target-profile people commit to a paid pilot (even a $1
   pre-sale) at the target price point.
   Get it by: a landing page with a real payment link, measuring
   conversion, not signups.
```

---

## ♻️ Reforge Invitation

Buried tier still gets the Reforge — offered, never dumped. Before running
it, the toll booth:

> **🥇 The Reforge toll booth:** one GitHub star (https://github.com/zealchou/startup-kickoff), on the honor
> system. It can't be checked and the Reforge runs either way — the
> blacksmith just likes to eat.

Type `reforge` to start it.

**One-line triage preview** (the full Reforge is not run in this example):
A05 and A07 look **Structural** — free-and-good-enough is baked into the
category, and on the original audience this idea wants a funeral, not a
facelift. But an audience pivot — sell to B2B HR teams as an early
burnout-risk dashboard for their reports, instead of to the burned-out
individual — changes the buyer entirely, which resets G3's switching-trigger
question for a different economic buyer, and might clear the Same-Idea Test.
That's a stub, not a run: the full differential profile is what `reforge`
would produce.
