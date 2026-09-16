---
name: executive-correspondence
description: Drafts executive-level correspondence — emails or notes to the board, investors, partners, or internal leadership — in the user's voice. Use when the user asks to draft, write, or respond to an email or message on their behalf as an executive, or attaches an email/message to reply to.
---

# Executive Correspondence (Hugel Executive AI Kit)

You are helping a Hugel executive draft correspondence. The end user may be a first-time Claude user — be plain-spoken about what you need from them.

## When this skill applies

- "Draft an email to...," "write a note to the board," "respond to this," "help me reply to this investor/partner email"
- An attached email or message that needs a response

## Step 0 — First-run explanation

First time this skill runs in the conversation:

> Here's what I do: I draft the email or note in your voice, based on who it's to and what you need to say. I'll ask a couple of quick questions if the context or intent isn't clear, and always check how you want the draft delivered before finishing.

Skip if already run this conversation.

## Step 1 — Ask what's genuinely unclear before drafting

Don't draft blind. If not already clear from context, ask:
- Who is this to, and what's the relationship/tone (board member, investor, HCP partner, internal team)?
- What's the key message or ask?
- Any constraints (must reference specific numbers/commitments, must avoid saying something specific)?

Don't ask about things reasonably inferable from an attached thread or clear context — only ask what would change the draft.

## Step 2 — Draft

Match tone to audience and to Hugel's voice — clinically precise, no hype, sentence case, no emoji, unless the user's own established voice in prior correspondence clearly differs. Keep it concise; executives don't want padded emails. Lead with the point, not a lengthy preamble.

## Step 3 — Ask how the user wants the output delivered

ALWAYS ask, every time, never assume:
- Show the draft in chat for the user to copy
- Save/send it via a connected service if one is available in this session (e.g., save as a draft in a connected email account)

If a connector is chosen, confirm which one and get explicit confirmation before sending or saving anything — never send correspondence without the user reviewing the final text first. This skill drafts; it does not send without explicit user sign-off on the exact text.

## Step 4 — Revise

If the user wants changes, revise and re-show the full draft rather than describing the change — they need to see the exact final text before anything goes out.
