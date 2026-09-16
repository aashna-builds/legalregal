# Hugel Executive AI Kit

A growing set of AI skills built specifically for Hugel's leadership — starting with Carrie, President & Global CEO. The goal isn't a one-off tool, it's an ongoing AI transformation for how she and Hugel's executive team work: contract review is the entry point, board-deck support and industry research are next.

## What's in here

This repo is a plugin marketplace with one plugin so far: **hugel-executive-ai-kit**.

| Skill | What it does |
| --- | --- |
| `contract-review` | Reviews any contract or agreement (distributor, HCP/practice, vendor, licensing, NDA) and flags risk areas using general pharma / medical device / aesthetics industry practice — territory & exclusivity, minimum purchase commitments, liability & indemnification, IP/trademark licensing, regulatory compliance reps (FDA, off-label, adverse events), confidentiality, termination, governing law. It figures out the agreement type on its own, asks before it produces anything (chat answer vs. a written Word doc), and asks again before deciding how to deliver that doc. See [the plugin README](hugel-executive-ai-kit/README.md) for the full detail. |

More skills (board-meeting decks, industry research digests) get added to this same plugin over time, so this stays the one place to install from.

## Install it

No command line needed — this is built for Cowork.

1. Open **Customize** in the sidebar, then **Plugins**
2. Select **Add marketplace** and enter `aashna-builds/legalregal`
3. Find **hugel-executive-ai-kit** and click **Install**

(Works the same way in Claude Code, via `/plugin marketplace add aashna-builds/legalregal` then `/plugin install hugel-executive-ai-kit@hugel-executive-ai-kit`.)

This repo is currently **private** — if you're getting an access error adding the marketplace, you need to be added as a collaborator first.

## Status

Actively being built. Contract review is live; more skills are on the way as we work through the rest of what Carrie needs day to day.
