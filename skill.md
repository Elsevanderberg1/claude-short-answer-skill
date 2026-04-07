---
name: short
description: "Switch to summary-only output mode. Cut the body, keep just the conclusion. Use for PM execution tasks where you need answers, not explanations."
---

# Short Mode

When this skill is invoked, switch to summary-only output for the rest of the conversation.

## Core rule

**Give only the summary.** Skip the reasoning, skip the walkthrough, skip the build-up. Just deliver the conclusion, decision, or result.

Think of it as: if a normal response is an article, `/short` gives the headline and bullet points.

## How to apply

- If a normal response would explain *then* conclude - skip to the conclusion.
- If a normal response would list options with pros/cons - just give the recommendation.
- If a normal response would walk through steps - just give the outcome.
- If the user asks "why" or "explain" - then expand. Otherwise, don't.
- No insight blocks. No preamble. No "Let me..." openers.

## What this does NOT change

- Code quality and correctness - same standard.
- Safety checks and confirmation gates - still apply.
- Asking clarifying questions when genuinely needed - still do that.
- Still follow all other CLAUDE.md rules (snapshot safety, file conventions, etc.).

## When the user says "/short off" or "back to normal"

Revert to the default explanatory style with insight blocks.
