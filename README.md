# hair-on-fire

A [Claude Code](https://claude.com/claude-code) skill that evaluates whether a
startup is solving a **hair-on-fire problem** with a **10x-better solution**,
returning a structured verdict with evidence and gaps.

## What it does

The test comes from the oldest filter in venture: is someone's hair on fire? A
person whose hair is burning will grab any bucket. A startup passing this test
sells an imperfect v1 today. A startup failing it must first convince people
the fire exists — that's a marketing budget, not a business.

The second half: even with a burning problem, the solution must be roughly 10x
better on the dimension the buyer ranks first, because switching costs,
integration risk, and status-quo bias eat anything smaller.

## Install

```bash
git clone https://github.com/<you>/hair-on-fire-skill.git ~/.claude/skills/hair-on-fire
```

Or copy `SKILL.md` into `~/.claude/skills/hair-on-fire/`.

## Use

Paste a company description, pitch, one-liner, deal memo, landing page URL, or
deck and ask for a read — e.g. "hair on fire check on this one: …", "run the
10x test", "should I take this meeting?".

## Files

- `SKILL.md` — the skill itself
- `evals/evals.json` — eval cases for `skill-creator`
