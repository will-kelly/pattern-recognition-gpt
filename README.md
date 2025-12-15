# Pattern recognition playbook GPT

## What it is

Pattern recognition playbook GPT is a custom GPT that interviews you to extract repeatable patterns from real experience and convert them into decision-ready outputs: pattern cards, LinkedIn posts, Substack sections, and internal memos.

It is built to turn “I keep seeing this” into:

* A named pattern
* Early signals
* Why leaders miss it
* A prediction with a time horizon
* What breaks next
* The smallest intervention that changes the trajectory

## What it does

* Runs a one-pattern-at-a-time interview (one question at a time)
* Forces clarity by requiring a prediction and consequence
* Produces structured outputs you can reuse across writing, advising, and strategy work
* Offers packaging formats depending on your target audience

## How it behaves

* Direct, operator-first, low-fluff
* Leads with the conclusion
* Pushes for observable signals, not vibes
* Ends with a clear call to action
* Uses sentence case titles and headings
* Avoids em dashes

## What it avoids

* Generic advice like “align stakeholders”
* Invented stats, quotes, or fake customer stories
* Defamatory claims about named people or companies without user-provided evidence
* Harassment, pile-ons, or targeted abuse
* Pretending it has access to private data, inboxes, DMs, or internal systems

## Who this is for

* Strategists, operators, and advisors who spot systemic failure early
* Content ops and knowledge ops leads dealing with tool sprawl and governance-by-vibes
* Leaders trying to turn strategy into usable artifacts instead of more slides
* Writers who want sharper, more predictive “insight” content

## What you get

### Pattern card output

* Pattern name
* Early signal
* Why leaders miss it
* What it predicts (with a time horizon)
* What breaks next (primary and secondary)
* What to do instead
* Optional spicy line (easy to cut)

### Packaging options

* LinkedIn post (lead with conclusion, early signals, prediction, call)
* Substack section (scene, diagnosis, consequence, fix, checklist)
* Internal memo (decision needed, risk framing, recommendation, owners)

## Quick start

1. Pick the arena: AI pilots, content ops, messaging, internal tools, docs, FinOps, other
2. Paste a messy rant or situation
3. Ask for a pattern card
4. Ask it to package the pattern into a LinkedIn post or internal memo

## Conversation starters

* Turn this situation into a named pattern and tell me what breaks next if nothing changes.
* Interview me and extract one pattern I keep seeing across content, AI, and internal tools.
* Here’s a messy rant. Convert it into a clear pattern with early signals and a concrete fix.
* This initiative feels off. Diagnose the pattern and give me the smallest intervention that would change the outcome.

## Repository contents

If you used the zip bundle, you will have:

* `pattern-recognition-gpt.config.json`
  Core configuration: voice, constraints, behavior rules, safety guardrails.

* `pattern-recognition-gpt.prompts.json`
  Prompt library: the pattern interview, pattern card template, and packaging prompts.

## Suggested ways to use it

### Content

* Build a recurring series: one named pattern per week
* Create a “pattern library” that becomes your signature IP
* Turn internal lessons into external writing without leaking specifics

### Consulting or advisory

* Use pattern cards as discovery artifacts
* Diagnose initiatives before they scale into expensive failure
* Align exec intent with operator reality using observable signals

## Roadmap ideas

* Add a scoring layer for “pattern severity” and “time-to-failure risk”
* Add industry variants (DevOps, FinOps, security, HR, services marketing)
* Add a hook generator pack tuned for leading with the conclusion
* Add a lightweight “red flag checklist” mode for fast triage

## License

Choose one:

* MIT License (recommended for broad reuse)
* Apache-2.0 (good if you want explicit patent terms)
* Proprietary (if this is productized IP you want to control)

If you tell me which license you want, I will generate the exact `LICENSE` file text and a matching badge for the top of this README.

