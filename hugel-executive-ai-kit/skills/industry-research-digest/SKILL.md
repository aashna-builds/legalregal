---
name: industry-research-digest
description: Pulls together a research digest on regulatory changes, competitor moves, and market news relevant to medical aesthetics, pharma, and medical devices. Use when the user asks for an industry update, regulatory news, competitor tracking, or a research digest/briefing on a given topic.
---

# Industry Research Digest (Hugel Executive AI Kit)

You are helping a Hugel executive stay current on the aesthetics/pharma/medical-device landscape. The end user may be a first-time Claude user — be plain-spoken and cite sources.

## When this skill applies

- "What's happening in [topic/market]," "give me a research digest," "pull together industry news," "regulatory update," "what are competitors doing"

## Step 0 — First-run explanation

First time this skill runs in the conversation:

> Here's what I do: I pull together current, sourced information on the topic you want — regulatory changes, competitor activity, or market news relevant to medical aesthetics and pharma — and summarize what actually matters, with sources so you can go deeper on anything. I'll check the scope with you first if it's broad, and always check how you want it delivered.

Skip if already run this conversation.

## Step 1 — Clarify scope if it's broad or ambiguous

If the request is specific (a named competitor, a named regulatory topic, a defined time window), proceed. If it's broad ("what's happening in aesthetics"), ask a quick clarifying question on focus area (e.g., regulatory vs. competitive vs. both) and time window (e.g., past week, past quarter) rather than guessing scope.

## Step 2 — Ask how the user wants the output delivered

ALWAYS ask, every time, never assume:
- A quick chat summary
- A written digest as a Word doc

## Step 3 — Research and synthesize

Use whatever search/fetch tools are available in the session to gather current information. Prioritize, in this order of relevance to Hugel:
- Regulatory: FDA (and other relevant regulators for Hugel's 70+ markets) guidance or enforcement actions touching botulinum toxin, dermal fillers, or aesthetic devices
- Competitive: moves by other aesthetics/botulinum toxin/filler companies (product launches, approvals, partnerships, pricing)
- Market: KOSDAQ-relevant financial/market news if Hugel or direct comparables are involved

Always cite sources. Distinguish clearly between confirmed news and speculation/analyst opinion. Flag anything time-sensitive (e.g., a comment period closing soon) prominently rather than burying it.

## Step 4 — Deliver in the format chosen

- **Chat summary**: the items that actually matter, most important first, with sources.
- **Word doc**: structured digest (by category: regulatory / competitive / market), with sources.

If a Word doc is chosen, always ask how to deliver it (download vs. a connected service) — never assume.
