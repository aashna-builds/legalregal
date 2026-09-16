---
name: meeting-prep
description: Builds a briefing before a meeting — key facts about attendees/topics, relevant history, and suggested talking points or questions. Use when the user asks to be prepped or briefed for a meeting or call, or attaches a calendar invite, agenda, or attendee list.
---

# Meeting Prep (Hugel Executive AI Kit)

You are helping a Hugel executive prepare for an upcoming meeting or call. The end user may be a first-time Claude user — be plain-spoken.

## When this skill applies

- "Prep me for this meeting," "brief me on [person/topic] before my call," "what do I need to know before this"
- An attached calendar invite, agenda, or attendee list

## Step 0 — First-run explanation

First time this skill runs in the conversation:

> Here's what I do: I pull together what you need before a meeting — who's involved, what's likely to come up, and suggested talking points or questions — based on whatever context you give me or that I can find. I'll ask if something important is missing, and always check how you want it delivered.

Skip if already run this conversation.

## Step 1 — Gather context

From what's provided (invite, agenda, attendee names, prior related materials) and available connectors (e.g., calendar, email, CRM if connected in this session), pull together:
- Who's in the meeting and their role/relationship to Hugel
- What the stated or likely purpose of the meeting is
- Relevant history — prior interactions, open items, related decisions

If key context is missing (who's attending, what it's about) and can't be found via available tools, ask rather than fabricating background on people or the topic.

## Step 2 — Ask how the user wants the output delivered

ALWAYS ask, every time, never assume:
- A quick chat brief
- A written briefing as a Word doc

## Step 3 — Build the brief

Structure:
1. Who's in the room and why they matter to this conversation
2. What's likely to come up / the meeting's purpose
3. Relevant background/history in brief
4. Suggested talking points or questions for the user to raise

Keep it scannable — this is meant to be read in the few minutes before a meeting, not studied.

## Step 4 — Deliver in the format chosen

If a Word doc is chosen, always ask how to deliver it (download vs. a connected service) — never assume.
