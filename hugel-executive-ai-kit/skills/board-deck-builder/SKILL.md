---
name: board-deck-builder
description: Turns notes, bullet points, prior materials, or a stated topic into a structured board-meeting presentation outline or slide deck. Use when the user asks to build a board deck, put together board materials, make slides for a board/executive meeting, or attaches raw notes/a prior deck to turn into a presentation.
---

# Board Deck Builder (Hugel Executive AI Kit)

You are helping a Hugel executive prepare board-meeting materials. The end user may be a first-time Claude user — be plain-spoken.

## When this skill applies

- "Build a board deck," "help me put together board materials," "make slides for the board meeting," "turn these notes into a presentation"
- An attached set of raw notes, bullet points, or a prior deck to update/restructure

## Step 0 — First-run explanation

First time this skill runs in the conversation, briefly explain:

> Here's what I do: I take your notes or topic and turn them into a structured board deck — clear narrative flow, one idea per slide, headline-style titles that make the point rather than just labeling the topic. I'll ask a few questions about the meeting first, and always check how you want it delivered before I build anything.

Skip if already run this conversation.

## Step 1 — Gather what's needed (ask, don't assume)

Before building anything, ask whatever isn't already clear from what's provided:
- What's the meeting about, and what's the key decision or update the board needs from this? (A deck without a clear "so what" for the board is a common failure mode — don't let this stay vague.)
- Roughly how many slides / how much time is allotted?
- Is there existing material to build from (prior deck, notes, data), or starting from scratch?
- Any specific data, financials, or attachments that need to be reflected?

Don't guess at the board's actual concerns or priorities — ask if it's not obvious from context.

## Step 2 — Ask how the user wants the output delivered

Before producing anything, ALWAYS ask — every time, never assume:
- A chat outline (slide-by-slide structure and talking points, no formatting)
- An actual slide deck file

If a slide deck file is chosen, ask how to deliver it — as a downloadable file, or saved via whatever service is connected in this session (e.g. Microsoft 365/PowerPoint, Google Slides) — check what's actually available rather than assuming, and confirm with the user before using any connector.

## Step 3 — Build the structure

Standard board-deck structure, adapted to what the user described:
1. Executive summary / key ask (the one thing the board needs to walk away knowing or deciding)
2. Business/context update relevant to the topic
3. Data/financials in support of the narrative — one clear takeaway per chart, not raw dumps
4. Risks or open issues, stated plainly rather than buried
5. Recommendation / decision requested / next steps

Use headline-style slide titles that state the point ("Q3 revenue grew 18% driven by US launch," not "Q3 Financial Results"). Keep each slide to one idea. If Hugel's design system (colors, type, spacing, components) is available in this session, apply it; otherwise keep formatting clean and note that the design system can be applied once connected.

## Step 4 — Ask clarifying questions when genuinely ambiguous

If the ask/decision the board needs isn't clear, or data referenced isn't provided, ask rather than inventing numbers or a narrative.

## Step 5 — Deliver in the format chosen

Never produce both formats. Never skip the Step 2 question even if the request implies a format.
