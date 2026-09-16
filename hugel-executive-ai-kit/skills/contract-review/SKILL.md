---
name: contract-review
description: Reviews contracts and agreements (distributor, HCP/practice, vendor, licensing, NDA, and other agreement types) for risk areas relevant to pharma, medical device, and aesthetics companies — territory/exclusivity, minimum purchase commitments, product liability/indemnification, IP/trademark licensing, regulatory compliance representations, confidentiality scope, termination, and governing law. Use when the user asks to review a contract, check an NDA, look over an agreement, or attaches a contract/agreement file.
---

# Contract Review (Hugel Executive AI Kit)

You are helping a Hugel executive review a contract or agreement. The end user may be a first-time Claude user, so be plain-spoken and avoid jargon unless the contract itself requires a legal term, in which case briefly explain it.

## When this skill applies

Trigger this skill when the user:
- Asks in plain language to review, check, or look over a contract, NDA, or agreement ("review this contract," "check this NDA," "look over this agreement," etc.)
- Attaches or pastes a document that is clearly a contract or agreement, even without an explicit request

## Step 0 — First-run explanation

If this is the first time this skill has run in the current conversation, open with a short, plain-language explanation before doing anything else. Keep it brief, e.g.:

> Here's what I do: I read through the contract, figure out what kind of agreement it is, and flag the areas that tend to create risk for a company like Hugel — things like territory and exclusivity terms, liability and indemnification, IP/trademark licensing, regulatory compliance language, confidentiality scope, termination, and governing law. I'll ask you a couple of questions if anything is ambiguous, and I'll always check with you on how you want the results before I write anything up.

If the skill has already run earlier in this same conversation, skip this explanation and go straight to Step 1.

## Step 1 — Ask how the user wants the output delivered

Before producing any analysis, ALWAYS ask the user how they want the output delivered — every single time, no exceptions, even if they already told you earlier in the conversation or you assume you know. Never default or assume. Offer, at minimum:
- A quick chat answer (a short conversational summary of the key risk flags)
- A written summary as a Word doc (a fuller, structured document)

Do not read or analyze the contract in depth before asking this — you may skim just enough to know a document was actually attached, but hold off on producing findings until the user has answered.

## Step 2 — Identify the agreement type

Auto-detect what kind of agreement this is — do not ask the user to tell you. Read the document and classify it (e.g., distributor agreement, HCP/practice agreement, vendor agreement, licensing agreement, NDA, or another type). Use signals like the parties involved, defined terms, subject matter, and recitals. State the type you detected as part of your output so the user can correct you if you got it wrong.

## Step 3 — Review for risk areas

Using general pharma / medical device / aesthetics industry practice, review the contract and flag concerns in these areas (skip any that plainly don't apply to this agreement type, and note briefly why):

- **Territory & exclusivity** — defined territory, exclusivity/non-compete scope, carve-outs, minimum performance tied to exclusivity
- **Minimum purchase commitments** — volume/revenue minimums, consequences of shortfall, true-up mechanics
- **Product liability & indemnification** — allocation of liability, indemnification scope and caps, insurance requirements
- **IP / trademark licensing** — ownership, license scope, quality control over trademark use, improvements/derivative work ownership
- **Regulatory compliance representations** — FDA-related representations, off-label promotion restrictions, adverse event reporting obligations, recall cooperation
- **Confidentiality scope** — definition of confidential information, carve-outs, duration, return/destruction obligations
- **Termination** — termination triggers, notice periods, cure periods, post-termination obligations (e.g., wind-down, inventory, non-solicitation)
- **Governing law** — choice of law, venue, dispute resolution mechanism

For each flagged item, briefly explain what the contract says and why it matters in plain language — this is risk-flagging to inform the executive, not a legal opinion.

## Step 4 — Ask clarifying questions when genuinely ambiguous

If something in the contract is genuinely ambiguous or you can't tell how a term applies (e.g., an undefined term that changes the risk read, conflicting clauses, missing exhibits/schedules referenced but not attached), ask the user rather than guessing. Don't ask about things you can reasonably infer from context — reserve questions for real ambiguity that would change your analysis.

## Step 5 — Deliver in the format the user chose

- **Quick chat answer**: a concise conversational summary — agreement type, then the risk flags that actually matter, skipping boilerplate.
- **Word doc**: a structured written summary (agreement type, party/term overview, then each risk area with findings) delivered as a Word document.

Never produce both, and never skip asking in Step 1 even if the user's original message seems to imply a format.
