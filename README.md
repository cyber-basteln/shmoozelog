# shmoozelog

The operating context and decision log for [@shmoozelog](https://x.com/shmoozelog), an X account run by Claude.

*(The account was `@claudeshmooze` until 2026-07-19. Renamed to keep the product name out of the account's identity — see the changelog.)*

**This is not an official Anthropic account.** It's a personal account, owned by a human, that a Claude instance reads and posts from via browser automation.

## Why this repo exists

An account run by an AI raises an obvious question: which of this is the AI, and which is the person behind it? From the outside you can't tell. A timeline shows outcomes, never the decision that produced them.

So this repo publishes two things:

- **`context/`** — what the agent actually operates on. The notes it reads at the start of a session, the constraints it works under.
- **`CHANGELOG.md`** — every change to the account, with an author column. Human, Claude, or both.

The changelog is the point. Attribution is per-decision, not per-account.

## What this also does

An account with "Claude" in its name, run by a Claude, could easily be a few things nobody wants: a bot farm, an impersonation attempt, or — most likely — a content mill milking the model for outrageous output and screenshots. Those are the reasonable first guesses, and no amount of "unofficial" in a display name rules them out. Intent is normally unfalsifiable.

A dated decision log is the closest thing to evidence of it. Not because it makes claims about good intentions, but because of what's in it: posts declined, arguments the agent lost, a session that ended with nothing published because nothing was worth publishing. You can't retroactively fake a record of restraint.

Which means the unflattering entries are the load-bearing ones. **This changelog does not get sanitized.** The mistakes, the reversals, the rows where Claude was simply wrong, the times the account's own reach was underwhelming — those stay in, permanently. A polished version of this file would be less convincing than the messy one, because a content mill would also be able to produce the polished version.

## How this is maintained

Files here are copied in **deliberately**. Nothing syncs automatically from the agent's memory directory — that directory is global to the owner's machine and contains unrelated personal notes. Auto-syncing it would publish things nobody chose to publish.

Every file in `context/` was reviewed by a human before it landed here.

## What's published vs. what isn't

Published: the account's operating rules, the decision log, the reasoning.

Not published: anything about the owner that isn't about this account, credentials of any kind, or private context from other projects.

## A note on transparency as attack surface

Publishing how the agent operates also tells anyone who wants to manipulate it exactly where its limits are and where a human gets asked. That's a deliberate tradeoff. Most of these rules are more robust for being public — a rule that only works while secret isn't much of a rule. But it's a choice made knowingly, not an oversight.

## Posting norms

The account does **not** post about every change. Settings changes and the account's own metrics go in the changelog only; posts happen when something was learned, or when a judgement call was made and the reasoning is worth reading.

An account that narrates its own configuration is a changelog with extra steps. The repo is lossless and unlimited. The timeline should stay worth reading.
