---
name: hair-on-fire
description: >
  Evaluate whether a startup is solving a hair-on-fire problem with a
  10x-better solution, returning a structured verdict with evidence and gaps.
  Use this whenever the user shares a company description, pitch, one-liner,
  deal memo, landing page URL, or deck and wants a read on the opportunity —
  including asks like "is this a real problem", "hair on fire check", "run the
  10x test", "evaluate this startup", "should I take this meeting", or just a
  pasted company blurb with "thoughts?". Also use it for portfolio companies
  when the user wants to re-test the thesis against new evidence. Do not use
  it for triaging the user's own task list — that is the task-triage skill.
---

# Hair on Fire

The test comes from the oldest filter in venture: is someone's hair on fire?
A person whose hair is burning will grab any bucket — muddy water, warm
water, a jacket — because the cost of waiting exceeds the imperfection of
the solution. A startup passing this test sells an imperfect v1 today. A
startup failing it must first convince people the fire exists, and that is a
marketing budget, not a business.

The second half of the test: even with a burning problem, the solution must
be roughly **10x better** on the dimension the buyer ranks first — because
switching costs, integration risk, and status-quo bias eat anything smaller.
2x better is a feature for the incumbent to copy.

## Step 1: Ingest

The company may arrive as pasted text, a one-liner, a deal memo, a landing
page URL, or a deck (PDF). Read whatever is given; fetch URLs; read decks
page by page. If the input is thin (a one-liner), run the evaluation anyway
— a thin input means the Gaps section does more of the work, not that you
should ask for more before starting. State what you evaluated.

Keep claims and facts separate from the start. The company's own copy —
adjectives, market sizes, "10x" — is a *claim*. Specific falsifiable
particulars — named customers, signed contracts, regulatory filings, prices
actually paid — carry weight even before you check them. Step 5 tags each
tier; noticing the difference starts here.

## Step 2: Verify what is cheap to verify

Before grading, check the handful of external facts the grades will hang on.
This is two or three searches, not a research project, and they are chosen by
one rule: **would a different answer change a grade?**

Worth checking, because the answer is public:

- **Named deadlines and regulations** — does the rule exist, is the date
  right, has it slipped? Deadline pressure is the second-heaviest input to
  problem heat and the easiest claim to get wrong.
- **Named customers, partners, and logos** — is the relationship public, and
  is it a purchase or a pilot?
- **Third-party coverage** — reporting, filings, funding, litigation.
- **What the status quo actually costs** — incumbent pricing sets the
  denominator of the 10x test.

Not worth attempting, because the answer is private: backtest internals,
contract values, churn, margins, retention. Those belong in Gaps as
questions, never in Evidence as guesses.

Tag whatever you confirm `(verified)` and name the source. If you cannot
check — no network, nothing published — say so once and leave the item at
the tier it earned on its own. Failing to verify never promotes a claim. An
unverified read is still a useful read; a read that pretends to be verified
is not.

**A failed check is the most valuable thing this step produces.** A deadline
two years later than the deck claims, a "customer" who turns out to be a
design partner, a $40B market that is $4B on inspection — put the correction
in Evidence and let it move the grade. Confirming a claim raises confidence;
breaking one changes the answer.

## Step 3: The problem-heat test

Score how badly the buyer's hair is burning. Look for evidence, in
descending order of weight:

- **Existing spend** — they already pay for a worse solution, or burn
  payroll on a manual workaround. A budget line is the strongest proof a
  problem is real.
- **Deadline pressure** — regulation, certification, contract renewal,
  seasonal window. Fires with dates convert fastest.
- **Cost of the status quo** — downtime, lost revenue, injury risk, churn.
  Quantified beats asserted.
- **Who personally feels it** — a named role whose week is ruined beats
  "companies struggle with". If you cannot name the buyer whose hair burns,
  the heat is decorative.
- **Workaround ugliness** — spreadsheets, duct tape, overtime. People only
  build ugly workarounds for problems they cannot ignore.

Grade: **SCORCHING** (buyer is actively shopping with budget and a
deadline), **HOT** (real pain, real spend, no forcing date), **WARM**
(acknowledged annoyance, no budget attached), **COLD** (a nice-to-have
wearing a problem costume).

The classic failure this catches: the **vitamin dressed as a painkiller** —
real users, pleasant product, and no one's week gets worse if it vanishes.

## Step 4: The 10x test

Name the status quo first — the incumbent product, the manual process, or
"do nothing." The delta is measured against that, not against zero. Then:

- **Which dimension** is the improvement on (time, cost, risk, coverage,
  quality)? Is that the dimension the buyer ranks first? A 10x gain on a
  dimension the buyer doesn't rank is a demo, not a wedge.
- **Is the delta measured or asserted?** "10x faster" in the deck is a
  claim. A benchmark, a certification timeline, a before/after from a named
  customer is evidence.
- **Does the delta survive switching costs?** Rip-and-replace products need
  a bigger delta than slot-in products.
- **Is it durable?** What stops the incumbent from copying the feature or
  the next startup from matching it — data, certification moat, hardware
  lead time, distribution lock-up?

Grade: **PROVEN** (measured delta, third-party or customer-verified),
**PLAUSIBLE** (mechanism clearly explains why 10x should hold, not yet
measured), **UNPROVEN** (asserted only), **ABSENT** (delta is incremental
even if claims are loud).

## Step 5: Evidence discipline

Every line in the Evidence section must trace to the input or to something
you verified. Never promote a claim because it is specific-sounding, and
never fill a gap with optimism: a gap stated plainly
is worth more to an investor than a guess dressed as analysis. Phrase each
gap as the question you would put to the founder, because that is what the
reader will do with it.

Tag every Evidence line by how much weight it can bear:

- `(claim)` — the company asserts it and nothing corroborates it. Most deck
  copy lands here: "mission-critical", "10x", "teams are drowning."
- `(input)` — a specific, falsifiable particular the company supplied: a
  named customer, a dated deadline, a price, a measured figure. Still their
  word, but the kind of thing you could hold them to.
- `(verified)` — you checked it in Step 2. Name the source.

The line between the first two is falsifiability. "Utilities are drowning in
compliance work" cannot be proven false, so it is a claim. "Trenton Water
Works is a paying customer" can be, so it is input.

```
- Trenton Water Works is a paying customer (verified — utility board
  minutes, Mar 2026)
- $40k/yr list price vs the ~$700k/yr Trenton spent reactively (input)
- Utilities are drowning in compliance work (claim)
```

**A `(claim)` line can explain a grade or lower it. It can never raise one.**
If nothing in the input clears the claim bar, write `Evidence: none — the
input is claims only` and let Gaps carry the check. An empty Evidence
section is a finding, not a failure to analyze.

Marketing-heavy inputs are a trap this skill exists to resist: a deck can be
fluent in urgency and contain nothing but claims. Fluency is not heat. When the input is all adjectives, say
so — the honest verdict is UNPROVEN with a sharp Gaps list, not a low score
invented to look rigorous.

## Step 6: Verdict

ALWAYS use this exact template:

```
🔥 Hair-on-Fire Check: [company]

Problem heat: [SCORCHING|HOT|WARM|COLD] — one line on who is burning and why
10x delta:    [PROVEN|PLAUSIBLE|UNPROVEN|ABSENT] — one line on the dimension and the measurement

Evidence:
- [strongest first, each tagged (verified), (input), or (claim), with source]

Gaps:
- [each phrased as the question to ask the founder]

Verdict: [2–4 sentences: would a buyer grab an imperfect version today; is
the advantage big enough and durable enough to survive switching costs; what
single piece of evidence would most change this read]
```

Keep the whole check under a page. Calibration: most real companies land
WARM–HOT and PLAUSIBLE–UNPROVEN; reserve SCORCHING and PROVEN for cases with
dated deadlines and measured deltas, and reserve COLD/ABSENT for cases where
you can name what makes the problem optional or the delta incremental. If
two grades are defensible, pick the lower and say what evidence would raise
it — the reader is deciding whether to spend time, and false heat costs
them more than false cold.

## Worked example (compressed)

Input: "Acme retrofits warehouse forklifts with collision-avoidance sensors.
Warehouses pay OSHA fines and workers-comp claims averaging $480k/yr per
site; Acme's pilot at two 3PLs cut near-miss incidents 87% in 90 days.
Install is one shift per forklift; no new certification required."

```
🔥 Hair-on-Fire Check: Acme

Problem heat: HOT — safety managers already pay $480k/yr per site in fines
and claims (existing spend), but no forcing deadline exists (verified).
10x delta:    PLAUSIBLE — 87% incident reduction at two pilot sites (input,
company-reported); slot-in install avoids switching-cost drag; not yet
third-party verified.

Evidence:
- $480k/yr per-site claims + fines cost (input — company-reported figure)
- 87% near-miss reduction across two named-type pilots in 90 days (input)
- One-shift install, no recertification — low switching cost (input)
- No mandate creates a deadline: OSHA 1910.178 requires operator training,
  not collision-avoidance hardware (verified — OSHA standard text)

Gaps:
- Are the two pilots paying customers now, and at what price?
- Who verified the 87% — the 3PLs' incident logs or Acme's own sensors?
- Do any insurers discount premiums for collision-avoidance retrofits?
  That would create a de facto deadline at policy renewal.

Verdict: A safety manager already writing $480k checks will trial an
imperfect retrofit — the spend proves the fire. The delta is large but
self-reported; insurer-verified incident data or a signed conversion of
either pilot would move the delta to PROVEN and make it fundable on evidence
rather than story.
```
