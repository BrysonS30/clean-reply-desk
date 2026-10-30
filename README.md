# Clean Reply Desk — Grok Bot Knowledge Base

This repository is the central reference library for Grok Bot work related to **Clean Reply Desk**.

It contains the business overview, problem, workflow, technology, safety rules, current status, pricing, and next steps, along with instructions for Grok Bots that use this information.

## How Grok Bots should use this repository

1. Read `GROK-BOT-INSTRUCTIONS.md` before working on Clean Reply Desk.
2. Read `BOT-ROLES.md` to understand the intended responsibilities of each bot.
3. Read the relevant business-reference documents below before making recommendations or drafting work.
4. Treat the business-reference documents as the source of truth. Do not invent missing facts.
5. Ask Bryson before changing repository documents, contacting prospects, sending messages, spending money, or changing a live system.

Do not assume Grok automatically reads this repository. Connect the repository in the Grok environment and explicitly instruct each bot to read the required files. Confirm that it has read them.

## Business reference files

| File | What it covers |
|---|---|
| `PRODUCT-OVERVIEW.md` | What Clean Reply Desk is, its founder, and its first market |
| `PROBLEM-IT-SOLVES.md` | The customer problem the product addresses |
| `HOW-IT-WORKS.md` | The quote request, drafting, approval, reply, follow-up, and reporting workflow |
| `TECH-STACK.md` | The tools and drafting approach |
| `SAFETY-AND-HONESTY-RULES.md` | Required safeguards and honest-business rules |
| `CURRENT-STATUS.md` | Current project status |
| `PRICING.md` | Pilot and ongoing pricing information |
| `NEXT-STEPS.md` | Current planned next steps |

## Grok Bot setup files

| File | What it covers |
|---|---|
| `GROK-BOT-INSTRUCTIONS.md` | Shared instructions for any Grok Bot working on this project |
| `BOT-ROLES.md` | Suggested responsibilities and boundaries for the bot team |

## Source-of-truth rules

- Preserve the facts in the business-reference files.
- If two documents appear to conflict, point out the conflict and ask Bryson which information is correct. Do not silently choose or rewrite facts.
- If information is missing or outdated, identify what needs confirmation.
- Clearly distinguish confirmed facts from assumptions, suggestions, and research.
- Do not claim that a feature, automation, customer result, or integration exists unless the repository or Bryson confirms it.

## Security and privacy

Do not store passwords, API keys, access tokens, private customer data, or other secrets in this repository. Keep sensitive client information out of repository files. The repository's visibility may be public; check its GitHub settings before adding anything confidential.

## Important operating boundary

These Markdown files communicate instructions and intended bot responsibilities. They do not, by themselves, grant or restrict technical permissions, connect Grok to GitHub, or guarantee that multiple bots can coordinate. Those capabilities must be configured and tested in the Grok environment.
