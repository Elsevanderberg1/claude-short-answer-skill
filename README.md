# /short - Claude Code Skill

A Claude Code skill that switches output to summary-only mode - cutting reasoning, walkthroughs, and filler so you get just conclusions and results, saving tokens and keeping your context window clean.

## Install

```bash
claude install-skill https://github.com/Elsevanderberg1/claude-short-answer-skill
```

## Usage

Type `/short` in any Claude Code conversation to switch to summary-only output.

Type `/short off` or say "back to normal" to revert to default output style.

## What it does

- Skips reasoning and build-up, delivers only the conclusion
- No preamble, no "Let me explain..." openers
- If you need the "why" on something, just ask and it expands
- Does not affect code quality, safety checks, or clarifying questions
