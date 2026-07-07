# Startup Canon — Core Methodology Reference

> Purpose: a working reference of established startup methodology, distilled into a form you can apply directly during an evaluation — each framework gets a one-line positioning plus operable criteria, steps, or thresholds. This is not a glossary; every entry should tell you what to *do* or what *number* to check.
> Source lineage: classic, publicly documented startup theory (Lean Startup, Y Combinator canon, The Mom Test, Sean Ellis PMF survey, TAM/SAM/SOM, standard unit-economics and cap-table practice, CB Insights/Startup Genome failure research). No proprietary or internal frameworks.

**How to use this reference during an evaluation**: don't read it front to back as theory. Pull the specific section that matches the claim being tested — a claim about market size gets checked against §5's bottom-up method and its worked example; a claim about traction gets checked against §4's false-positive list before it gets credited as a PMF signal; a claim about the team gets checked against §7's written-agreement checklist. Every section ends with something concrete enough to check a real answer against, not just a concept to recognize.

---

## 1. Lean Startup (Eric Ries) — Build-Measure-Learn

**One-line positioning**: A startup is an institution operating under extreme uncertainty; the job is to manage that uncertainty with the smallest possible experiment loop that produces *validated learning*, not to execute a plan flawlessly.

**Two distinct fits, often conflated**: problem-solution fit (evidence that a real, specific, frequent, severe problem exists and your proposed solution addresses it — established through discovery interviews, §3) is a different, earlier milestone than product-market fit (evidence that the market pulls the built product on its own, §4). Treat a strong problem-solution fit result as license to build an MVP, not as evidence that PMF has already been reached.

**The loop, reasoned backward**:
- Don't start with "Build." Start by deciding what you need to **Learn** (which hypothesis is riskiest right now) → work backward to what you need to **Measure** → work backward again to the smallest thing you need to **Build** to get that measurement.
- The metric to optimize is the loop itself: total cycle time. A faster loop produces more validated learning per unit of runway, independent of what any single experiment shows.

**MVP (Minimum Viable Product) criteria**:
- Definition: the version of a product that lets you complete one full Build-Measure-Learn loop with the least effort. Its job is to produce learning, not to be a small finished product.
- Operable test: "Does this version let me test my current riskiest assumption?" If yes, it's small enough. If no, it either has the wrong scope or too much scope.
- Failure modes to flag: treating the MVP as "v1 with fewer features" instead of a learning instrument; polishing before anyone has confirmed they want the thing at all.

**Two hypotheses to write down before building anything**:
- **Value hypothesis** — does a real user get value from this, once they try it?
- **Growth hypothesis** — how will new users discover and adopt it?

**Three engines of growth (frameworks for the growth hypothesis specifically)**:
- **Sticky engine**: growth comes from retaining existing customers longer than you lose them; the key metric is churn rate, and the operable target is for natural growth rate to exceed churn rate.
- **Viral engine**: growth is a byproduct of normal product use, not a separate marketing action (each user causes more than one additional user to join); the key metric is the viral coefficient, and the operable target is a coefficient above 1.0 for unassisted compounding growth.
- **Paid engine**: growth comes from spending on acquisition where marginal revenue per customer exceeds marginal cost per customer; this reduces to the unit-economics discipline in §6 (CAC, LTV, payback).
- Operable step: name which engine (or combination) the business is actually betting on, and evaluate traction against that engine's specific metric — a "sticky" claim backed only by paid-acquisition growth numbers is evidence of the wrong engine, not confirmation of the claimed one.

**Pivot criteria (when several loops produce no validated learning)**:
- A pivot is a structured correction to one core hypothesis, keeping what has already been learned — not scrapping everything and starting over.
- Common pivot types to recognize: zoom-in (a single feature becomes the whole product), zoom-out, customer segment, customer need, platform, business architecture, value capture, engine of growth, channel, technology.
- Signals it's time to consider one: experiment results are flat over multiple cycles; the team needs heroic effort just to sustain current numbers; a metric improves but the underlying business result doesn't move.
- Diagnostic question: "Are we making progress, or just making the same experiment look better?"

**Innovation accounting (avoiding vanity metrics)**:
- Ban vanity metrics that only ever go up and never explain a decision: cumulative signups, total downloads, raw pageviews.
- Use actionable metrics instead: cohort-based retention, conversion by cohort, per-customer economics.
- Three-step discipline: establish a baseline with real MVP data → tune the engine (iterate to move the number toward the target) → decide pivot or persevere based on whether tuning is working.

**Operable red flag**: if a metrics dashboard reports a cumulative total (a number that can only go up) as the headline, and no cohort-by-cohort breakdown exists anywhere, treat the reporting itself as unvalidated until a cohort view is produced.

---

## 2. Y Combinator Canon (Paul Graham et al.)

**One-line positioning**: Don't optimize for "how to start a company" — optimize for making something people want; nearly everything else follows from that or doesn't matter.

**Operable core principles**:
- **Make something people want**: the entire creed. If nobody wants the product, no amount of growth hacking, fundraising, or team quality saves it.
- **Talk to users** + **do things that don't scale**: deliberately do unscalable things early — hand-recruit your first users, give disproportionate white-glove support, onboard people one at a time yourself. The payoff is depth of learning and a small group of users who genuinely love the product, which is worth more than a large group that mildly likes it.
- **100 users who love you beats 1,000 who kind of like you**: optimize for intensity of want in a small cohort before optimizing for reach.
- **Launch early, iterate in small steps**: ship before it feels ready; don't hold a big reveal.
- **Founders' job, early on, is to write code and talk to users** — treat almost everything else as distraction in the earliest stage.
- **Growth is the sole measure of a startup's health** (Graham's "Startup = Growth"): a startup is definitionally a company designed for rapid growth. No growth means it isn't functioning as a startup, regardless of other vanity signals. Track and hold a weekly growth rate target — YC commonly discusses 5–7% week-over-week as a healthy early band.

**Default Alive vs. Default Dead** (Paul Graham):
- Definition: given your current revenue growth curve and current spending, will you reach breakeven before you run out of cash? Yes → default alive. No → default dead.
- Operable step: calculate this explicitly, as early as possible — most founders underestimate the odds that they are already default dead. If default dead, there are exactly two levers: accelerate revenue growth, or cut costs to extend runway. There is no third option that doesn't involve raising money you may not get.
- Failure mode to flag: "we'll just raise the next round" — outsourcing default-dead status to a future fundraise is one of the most common causes of death.

**Other frequently cited principles**:
- **Ramen profitability**: the minimum profit that covers founders' basic living costs — an important psychological and strategic milestone because it removes dependence on the next fundraise for survival.
- "Startups don't die when they run out of money, they die when the founders give up" — true as far as it goes, but runway management remains a hard constraint that determines how much room founders have before that choice is forced.
- **Schlep blindness**: founders systematically avoid ideas that require an unglamorous, tedious piece of execution (manual onboarding, cold outreach, regulatory paperwork), even when that schlep is exactly what keeps competitors away. Operable check: if an idea was rejected mainly because "it would require doing X, which is annoying," treat that as a reason to look harder, not a reason to discard it.
- **Monotonic growth as a health check**: a chart that should only go up (retained cohort revenue, total paying customers) that instead wobbles or declines is one of the fastest tells that something underneath is broken, even if the current absolute number still looks fine.

---

## 3. Customer Discovery: The Mom Test (Rob Fitzpatrick)

**One-line positioning**: A good customer interview is one that would give you honest signal even if the person you were interviewing was your own mother, incapable of hurting your feelings — because you ask about their real past and behavior, never their opinion of your idea.

**Three rules**:
1. **Talk about their life, not your idea.**
2. **Ask about specifics in the past, not generics or opinions about the future.**
3. **Talk less, listen more.**

**Bad → good question rewrites**:
- ❌ "Would you use a product that does X?" → ✅ "When's the last time this problem came up for you? What did you do about it?"
- ❌ "Do you think this is a good idea?" (people are polite and will say yes) → ✅ "How much time or money are you currently spending dealing with this? What tools are you using?"
- ❌ "Would you pay for this?" → ✅ "What's your current budget for solving this problem? Who has to approve that spend?"

**False positives to watch for**:
- Compliments, fluff ("I'd usually…" — vague future-tense statements), and ideas (the person designs features for you) are all non-committal and do not count as evidence.
- Real evidence = **commitment** (time, reputation, or money at stake) + **advancement** (a concrete next step: an introduction, a signed trial, a prepayment).

**Operable rule**: if an interview produces no disclosure of a specific past behavior plus an existing pain or spend, it produced zero signal — regardless of how enthusiastic the conversation felt. After each interview, record only facts, commitments, and new leads; do not record your own excitement as data.

**Always end with an advancement ask**: a discovery interview that ends without asking for something concrete (an intro to someone else with this problem, a follow-up demo slot, a small prepayment) has left the strongest available evidence on the table — enthusiasm that won't convert to a next step is itself a signal worth recording, not ignoring.

**Interview script skeleton (for reuse)**:
1. Open on their world, not your product: "Walk me through the last time [problem context] came up."
2. Drill into specifics: frequency ("how often"), cost ("what does that cost you in time or money"), current workaround ("what do you do about it today").
3. Probe severity honestly: "On a scale of things you deal with in a normal week, where does this rank?" — a problem that ranks low rarely gets budget or attention regardless of how much the person nods along.
4. Close with an ask for advancement, never with a pitch.

---

## 4. Product-Market Fit (PMF) Signals

**One-line positioning**: PMF is the state where the market pulls the product out of your hands instead of you pushing it into the market. Before PMF you are pushing; after PMF the market is pulling.

**Sean Ellis 40% test** (the most widely used quantitative proxy):
- Ask active users: "How would you feel if you could no longer use this product?" Options: very disappointed / somewhat disappointed / not disappointed.
- **Threshold: ≥40% answering "very disappointed" is a meaningful PMF signal.** Below 40% usually means the product isn't there yet.
- Advanced use: segment who the "very disappointed" respondents actually are (find the high-expectation customer persona) and re-focus product and messaging on that segment rather than the average user.

**Other PMF signals**:
- **Retention curve flattening ("smiling curve")**: cohort retention stops decaying toward zero after some point and levels off — one of the hardest pieces of PMF evidence available, more reliable than NPS or survey responses.
- **Organic pull / word of mouth**: unprompted referrals, growth with no paid acquisition behind it, users complaining loudly when the product goes down (a sign they depend on it).
- **The effort test**: before PMF, retention only holds up through heroic, manual intervention by the team; after PMF, the product sustains retention on its own.
- **Paid + returning must both be true**: signups with no activation, or revenue with no retention, are each false positives on their own.
- General rule: **no single metric confirms PMF** — look for a pattern that holds across multiple cohorts and multiple iteration cycles, not a one-time reading.

**When to build the measurement framework (critical timing point)**: define retention benchmarks, activation criteria, Day 7 / Day 30 targets, and what a false positive would look like for this specific product **before the first user arrives** — not after, when it's tempting to pick whichever metric already looks good.

**PMF is a range, not a binary switch**: treat it as a spectrum you are moving along rather than a single moment you either have or don't. Re-run the Sean Ellis survey periodically (not just once) — a score that climbs toward 40% over several cohorts is a different situation than one that already passed 40% once and has since drifted down, even though a single snapshot might look identical.

**Persona-driven follow-up (Rahul Vohra's extension to the 40% test)**: don't stop at the aggregate percentage — cross-tabulate "very disappointed" respondents against firmographic and usage data to find the highest-expectation customer segment, then ask that segment specifically what almost stopped them from using the product and what single benefit they'd be most upset to lose. Use those answers to sharpen product roadmap and messaging, not the average respondent's answers.

**Common false-positive patterns to name explicitly**:
- High signup volume driven by a single viral or paid spike, with no repeat usage behind it.
- Strong NPS or survey sentiment with flat or declining actual usage — people are polite about products they don't use.
- Revenue growth driven entirely by a small number of large, high-touch deals that required founder-level manual effort to close and won't repeat without that effort.

**Retention benchmarks vary by product type — don't apply one bar to everything**: a consumer social app with 25% Day-30 retention may be struggling, while a B2B tool used weekly by a small paid team with 70%+ monthly logo retention may be healthy but still pre-PMF on expansion. Set the specific benchmark from comparable products in the same category, not from a single universal number, and state which comparison was used when judging a retention figure.

---

## 5. Market Sizing and Timing: TAM / SAM / SOM + Why Now

**One-line positioning**: Market size numbers are not there to make a deck look impressive — they are a reasoning tool for whether a market is worth entering and winnable with your specific approach.

**Definitions and calculation**:
- **TAM (Total Addressable Market)**: the total annual revenue ceiling if every possible customer of this product category, worldwide, bought it.
- **SAM (Serviceable Addressable Market)**: the slice actually reachable given your product, business model, and geography.
- **SOM (Serviceable Obtainable Market)**: the share you could realistically capture in the next 1–3 years.
- **Cross-validate with two calculation methods**:
  - Top-down: start from an industry report's total figure and slice down. Prone to inflation — use this only as a sanity check, never as the primary number.
  - **Bottom-up (the more credible method)**: number of target customers × average annual revenue per customer (ARPU) × a realistic reachable percentage. This should be the primary basis for any claim.
- Operable threshold: investors commonly want TAM large enough that capturing even a small share could build a $100M+ revenue company. But the bottom-up SOM is the number you owe yourself honesty about — it's the one that determines whether the near-term business is viable at all.

**Why Now (the most underrated question in market timing)**:
- Core question: "Why is this business possible or necessary now, rather than five years ago or five years from now?"
- Operable step: identify the specific enabling shift — a technology breakthrough (e.g., agentic AI capability crossing a usability threshold), a regulatory change, a behavioral or demographic shift, or a cost curve dropping past a threshold. Without a clear why-now, the market is usually either not ready yet (too early) or already captured (too late).
- Assess market state: expanding / consolidating / mature — this determines whether the right competitive posture is differentiation or speed.
- Operable check: if the why-now answer describes something true about the world in general (e.g., "people need to save time") rather than something that changed recently, it isn't a why-now — it's a why-ever, and it doesn't explain the entry timing at all.

**Buyer landscape (mandatory for B2B)**: identify who controls budget, who influences the decision, and who is the actual day-to-day user — these are frequently three different people. Messaging and sales motion must be built around the economic buyer, not just the end user.
- Operable check: if a go-to-market plan or set of customer interviews only ever references "the user" with no distinct mention of who approves the purchase, treat the buyer landscape as unmapped, even if the user-facing product story is otherwise strong.

**Worked example of the bottom-up method** (illustrative, not a template to copy numbers from): if there are 50,000 companies in the target segment worldwide, 10% are realistically reachable in the near term given the go-to-market motion (SAM = 5,000 companies), average annual contract value is $12,000, and a credible 3-year capture rate is 4% of the reachable set, then SOM ≈ 5,000 × 4% × $12,000 = $2.4M in obtainable annual revenue. If that SOM can't support a viable business at the team's target scale, the issue is not sentiment about the idea — it's the arithmetic, and it needs to be fixed (larger ACV, larger reachable segment, or a different business model) before proceeding.

---

## 6. Business Model: Unit Economics + Pricing

**One-line positioning**: Whether a business can survive is first a question of whether acquiring one customer is profitable at all — scale only amplifies the sign (positive or negative) of the unit economics you already have.

**Core metrics and thresholds**:
- **CAC (Customer Acquisition Cost)**: the fully-loaded cost — sales plus marketing, allocated — to acquire one paying customer.
- **LTV (Lifetime Value)**: the present value of gross margin a customer contributes over their lifetime. Rough formula: `LTV ≈ (ARPU × gross margin %) / churn rate`.
- **LTV:CAC ratio**: healthy threshold is **≥ 3:1**. Below 1:1 means the business loses money on every customer it acquires; above roughly 5:1 can indicate under-investment in growth (spending too conservatively relative to the opportunity).
- **CAC payback period**: how long it takes to recover CAC from that customer's margin. Healthy SaaS threshold is typically **under 12 months** — shorter is better, especially pre-scale.
- **Churn / retention**: monthly churn directly compresses LTV. **Net revenue retention (NRR) above 100%** means the existing customer base expands on its own (upsell/expansion outweighing churn) — a strong moat signal independent of new-customer acquisition.
- **Gross margin**: software businesses typically target **70%+**. Gross margin determines how much of every revenue dollar is actually available to reinvest in growth.
- **Burn multiple**: net cash burned divided by net new ARR added. **Under 1 is excellent efficiency; above 2 is a warning sign** worth investigating before it compounds.

**Pricing fundamentals**:
- **Value-based pricing > cost-plus pricing > competitor-based pricing**: anchor price to the value the customer captures, not to your own costs. The diagnostic question is the same one from customer discovery: "What are you currently spending in time or money to deal with this problem?" — that answer indicates the value ceiling.
- **Choose the right value metric**: pick a pricing unit (seats, usage volume, percentage of transaction value, hours saved…) that scales up naturally as the customer's value from the product scales up. The wrong metric either penalizes the customer's growth or breeds resentment.
- **Price higher early rather than lower**: low prices are hard to raise later, attract the wrong customer segment, and obscure whether real value is being delivered. Raising prices is far harder than lowering them — price is the single strongest lever founders most commonly underuse.
- **Operable tests for willingness-to-pay**: Van Westendorp price sensitivity questioning, direct conversations with the economic buyer about existing budget and approval process, A/B testing across tiers. Sell to a small number of genuinely paying customers first to validate willingness-to-pay before standardizing a price.

**Reading the metrics together, not in isolation**: a single metric out of context is easy to misjudge — a payback period of 18 months looks bad in isolation, but is a materially different situation for a business with high NRR and low churn (the customer keeps paying and expanding for years) than for one with high churn (the customer may not stick around long enough to ever pay back). Always read CAC payback, churn, and NRR together before judging whether a business's unit economics are viable.

**Blended CAC vs. paid CAC**: blended CAC averages all acquisition spend (including founder time on organic channels, which is not free even if it's not a cash outlay) across all new customers; paid CAC isolates spend on paid channels only. A business that reports only its paid CAC while most of its customers actually arrive through founder-led manual outreach is understating true acquisition cost — ask which number is being presented before comparing it to the 3:1 LTV:CAC threshold.

---

## 7. Co-Founders and Equity

**One-line positioning**: A co-founder relationship is the highest-risk "marriage" a startup enters into, and equity is the single decision most likely to tear a team apart after the fact — both need a deliberate framework applied early, not resolved by default or by avoidance.

**Co-founder principles**:
- **Complementary, not overlapping, skills** (e.g., a builder paired with a seller) — but **values and work ethic must be highly aligned**, not just skills.
- **Work together before committing**: run a real stress-test project together before formalizing the partnership. Casual "founder dating" conversations are not sufficient; you need to see how the other person behaves under real conflict and real deadline pressure.
- **Put four things in writing explicitly**: each person's role and decision rights, full-time status, what happens if someone leaves, and how disagreements get resolved.

**Equity principles**:
- **Lean toward near-equal splits**: heavily unequal splits (e.g., 90/10) commonly plant resentment early, unless the difference in contribution or risk is genuinely enormous. The psychological value of an equal-feeling split usually outweighs the precision of "who technically did more."
- **Always add vesting**: standard is **4-year vesting with a 1-year cliff**, applied to every founder including yourselves. This is the only real mechanism that protects the team that stays from a co-founder who leaves after a few months but keeps a large equity stake.
- **Reserve an option pool**: plan for **10–20%** set aside for future employees, negotiated before the cap table is finalized.
- **Don't overpay advisors or part-timers in equity as a shortcut**: early equity is the most expensive currency the company has.
- Practical tools: dynamic-split frameworks (e.g., Slicing Pie) for pre-revenue equity questions, a standard vesting agreement template, and legal counsel engaged early rather than after a dispute starts.

**Why the 1-year cliff matters mechanically**: under a standard 4-year/1-year-cliff schedule, a co-founder who leaves before the 12-month mark walks away with zero vested equity, and after that point vests monthly (or quarterly) for the remaining three years. Without this mechanism, a co-founder who leaves after three months keeps whatever raw percentage was agreed at the start — full ownership, zero time served. Every founding round should confirm this schedule is actually documented in writing, not just verbally agreed.

**Co-founder red flags to check for explicitly**:
- No shared answer to "what happens if one of us wants to leave in year one" — silence on this question is itself the red flag, not just a bad answer.
- One founder consistently makes unilateral decisions on matters the group agreed should be joint.
- Equity or role conversations are being avoided because the relationship "feels too good to complicate with paperwork" — this is precisely the situation vesting and written agreements are designed to protect.
- A founder holding significant equity is not full-time and has no written plan or timeline for becoming full-time — unresolved part-time status among people holding founder-level equity is a common source of later conflict and should be treated as an open item, not a minor detail.

---

## 8. Top-12 Early-Stage Killers

**One-line positioning**: Most startups are not killed by competitors — they die from predictable, self-inflicted failure patterns. Recognizing the pattern early is most of the defense.

1. **No market need** — building something nobody wants. The single largest cause of death in post-mortem research (CB Insights found this behind roughly 42% of startup failures). *Antidote → §3 (Mom Test discovery) and §4 (PMF signals) before building.*
2. **Running out of cash / bad fundraising timing** — poor runway management, realizing too late that the company is default dead. *Antidote → calculate default alive/dead early (§2), control burn.*
3. **Not the right team** — co-founder conflict, missing critical skills, equity disputes. *Antidote → §7.*
4. **Getting outcompeted / competitor neglect** — being so focused on your own vision that you ignore how competitors will respond. *Antidote → actively argue the strongest case for why a leading competitor beats you, don't assume no serious competition exists.*
5. **Pricing / cost structure issues** — pricing too low or negative unit economics. *Antidote → §6.*
6. **Premature scaling** — expanding team, marketing spend, or feature scope before PMF is validated. Startup Genome research identifies this as one of the most common root causes of failure. *Antidote → advance by stage-appropriate exit criteria, not by ambition.*
7. **Poor product / ignoring users** — building in isolation without talking to the people who are supposed to use it. *Antidote → talk to users (§2), Mom Test discipline (§3).*
8. **Building too long before launching / perfectionism** — chasing polish instead of learning, delaying the first real test. *Antidote → early launch, MVP as a learning instrument, not a finished product (§1).*
9. **Scope creep / loss of focus** — trying to do everything, especially dangerous when AI tooling makes adding features cheap and tempting. *Antidote → write down explicit scope boundaries and the evidence bar required to add anything.*
10. **Founder burnout / giving up** — the final common pathway for most failure modes, regardless of root cause. *Antidote → ramen profitability (§2), sustainable pace, automating or delegating operational load.*
11. **Ignoring security and compliance until it's too late** — shipping to real users without a pre-launch security review. Code that runs is not the same as code that is safe, and this gap is especially easy to miss when a large share of the code was AI-generated. *Antidote → a pre-launch security and compliance checklist, treated as a gate, not an afterthought.*
12. **Chasing funding as validation** — treating a successful raise as proof the market wants the product. A raise validates investor belief, not customer demand. *Antidote → keep the PMF and unit-economics bar (§4, §6) as the real validation signal regardless of fundraising success.*

**Using this list during an audit**: each pattern above should be checked against direct evidence, not against the founder's stated intent to avoid it. "We know competitors matter, we just haven't mapped them yet" is pattern 4 in progress, not an exception to it. A pattern only counts as mitigated when the corresponding antidote section's operable criteria have actually been satisfied — a strategy slide that names the risk is not the same as evidence the risk has been addressed.

---

## Stage × Methodology Quick Reference

| Stage | Primary methodology to apply | Exit signal to look for |
|---|---|---|
| **Idea** | Mom Test discovery interviews (§3) + competitive/market assessment (§5) + why-now check (§5) | Clear, falsifiable evidence of problem-solution fit: real, specific, frequent, and severe pain, backed by past behavior, not opinion |
| **MVP** | Lean Build-Measure-Learn loop (§1) + MVP discipline (§1) + Sean Ellis 40% test + retention curve (§4) | Genuine PMF signal: retention flattening, organic pull, and paid+returning both holding — not a single vanity metric |
| **Launch** | Unit economics discipline — CAC, LTV, payback, burn multiple (§6) + removing founder-as-bottleneck (§2, §8) | A repeatable acquisition channel with acceptable payback, plus operations that don't require the founder's personal, unscalable involvement |
| **Scale** | Moat and defensibility, GTM function maturity, organizational scaling | Sustainable profitability, or a credible path to an outside financing/exit event, without relying on premature-scaling shortcuts (§8) |

**Judgment discipline that runs through every stage**:
- Validate before you build; use structured adversarial thinking (argue the strongest case against your own idea and your own numbers) rather than only the case for it.
- Judge advancement by stage-appropriate exit criteria and known failure modes, not by a feature checklist.
- Reject vanity metrics; trust only actionable, cohort-based metrics and real customer commitment.
- Treat honest engagement with disconfirming evidence as the system working correctly — a pivot is a designed outcome of the method, not a failure of it.
- Numbers presented without a stated source or calculation method (market size, retention, CAC) should be treated as unverified claims, not facts, until the underlying method is shown — a number with no visible arithmetic behind it is a guess wearing a number's clothing.
- A stage assessment is a snapshot, not a permanent verdict: re-check the exit criteria for the current stage on a regular cadence, since a business can regress (losing PMF signal, unit economics deteriorating) as easily as it can progress.
- When two sections of this reference point to conflicting conclusions about the same claim (for example, a strong Sean Ellis score in §4 alongside a negative LTV:CAC in §6), report the conflict explicitly rather than resolving it silently in the more favorable direction — a business can have real product love and unsustainable unit economics at the same time, and both facts belong in the verdict.
