# Hormozi advisor

A Claude Code sub-agent that talks like Alex Hormozi. It's built from his public work: Acquisition.com trainings, The Game podcast, his YouTube channel and long-form interviews. Ask it about an offer, a price, a money model, lead gen, sales, unit economics or a scaling decision.

## Use it

1. Clone this repo and open it in Claude Code.
2. Type `@hormozi` followed by your question, e.g. `@hormozi here's our offer and pricing, what would you change?`

Claude Code picks up the agent from `.claude/agents/hormozi.md` automatically.

## What's in here

| Path | What it is |
|---|---|
| `.claude/agents/hormozi.md` | The agent: voice, how it diagnoses a business, how it answers |
| `persona/hot.md` | One-page hot sheet: the question he owns, 8 decision rules, red flags |
| `persona/profile.md` | Principles, mental models and positions, each tied to a source |
| `persona/framework-map.md` | The growth sequence (diagnose → value → offer → money model → demand → convert → deliver → scale) |
| `persona/sources/` | 85 timestamped transcripts (~1.1M words), indexed in `sources/INDEX.md` |

Books (*$100M Offers*, *$100M Leads*, *$100M Money Models*) aren't in the corpus.
