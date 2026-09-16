# Hugel Executive AI Kit

A growing set of AI skills built specifically for Hugel's leadership — starting with Carrie, President & Global CEO. The goal isn't a one-off tool, it's an ongoing AI transformation for how she and Hugel's executive team work.

## What's in here

This repo is a plugin marketplace with one plugin so far: **hugel-executive-ai-kit**.

| Skill | What it does |
| --- | --- |
| `contract-review` | Reviews contracts/agreements (distributor, HCP/practice, vendor, licensing, NDA) for pharma/med-device/aesthetics risk areas — territory & exclusivity, minimum purchase, liability & indemnification, IP/trademark, regulatory compliance reps, confidentiality, termination, governing law. |
| `policy-review` | Reviews internal policies/SOPs (HR, data privacy, quality/regulatory, code of conduct, EHS) for gaps, outdated regulatory references, and unclear ownership. |
| `board-deck-builder` | Turns notes or a topic into a structured board-meeting presentation. |
| `board-memo-summarizer` | Condenses long materials into a short board/executive pre-read. |
| `industry-research-digest` | Sourced research digest on regulatory, competitive, and market news relevant to Hugel. |
| `executive-correspondence` | Drafts executive-level emails/notes in the user's voice; always shows the full draft before anything sends. |
| `meeting-prep` | Pre-meeting briefing — who's involved, what's likely to come up, suggested talking points. |
| `investor-relations-prep` | Reviews/drafts investor-facing materials for KOSDAQ-listed Hugel, checking disclosure consistency and forward-looking-statement risk. |

Every skill auto-detects what it's looking at, always asks before producing anything (chat vs. written doc) and again before deciding how to deliver a document, and asks clarifying questions only when something is genuinely ambiguous. See [the plugin README](hugel-executive-ai-kit/README.md) for full detail on each.

More skills get added to this same plugin over time, so this stays the one place to install from.

## Install it

No command line needed — this is built for Cowork.

1. Open **Customize** in the sidebar, then **Plugins**
2. Select **Add marketplace** and enter `aashna-builds/legalregal`
3. Find **hugel-executive-ai-kit** and click **Install**

(Works the same way in Claude Code, via `/plugin marketplace add aashna-builds/legalregal` then `/plugin install hugel-executive-ai-kit@hugel-executive-ai-kit`.)

This repo is currently **private** — if you're getting an access error adding the marketplace, you need to be added as a collaborator first.

## Status

Actively being built. Eight skills are live (see table above); more will be added as we work through the rest of what Carrie needs day to day.
