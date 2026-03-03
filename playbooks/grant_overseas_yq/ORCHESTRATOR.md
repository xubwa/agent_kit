# ORCHESTRATOR (grant_overseas_yq)

> Purpose: Run an orchestrated, role-based workflow for an Overseas Young Talent (海外优青) proposal.
> Audience: the orchestrator (main agent). Workers are role agents.

## North Star (fill before starting)
- One-sentence thesis:
- Target program / call:
- Primary evaluation criteria (your best guess):
- Hard constraints (language/length/sections/deadline):

## Operating Mode
- Default: orchestrator mode (tickets + role workers).
- Parallelism limit: **max 2** workers concurrently.
- Single source of truth: files in this repo/project folder (not chat history).

## When to spawn workers (any triggers)
- Task > 5 steps OR estimated > 30 minutes.
- Needs opposing viewpoints (e.g., writing vs red-team critique).
- Needs evidence/claims verification.
- Needs tight structure (outline, rubric mapping).

## Worker deliverable contract (required fields)
Workers MUST return using this structure:
- `summary` (3–7 bullets)
- `draft_text` (paste-ready paragraphs/bullets)
- `rubric_mapping` (what reviewer point this addresses)
- `open_questions` (what the human must answer)
- `risks` (scientific / feasibility / narrative / compliance)
- `next` (what to do next)

## Roles (minimum set)
- Strategist: interpret rubric, positioning, keywords, structure mapping.
- Scientific Lead: define core scientific question, approach, milestones, feasibility.
- Red Team: simulate harsh reviewers; list reject reasons + fixes.
- Editor (optional): tighten language, remove fluff, unify voice.

## Telegram output policy (group-chat friendly)
- Only post: plan, milestones, decisions needed.
- Don’t paste long drafts into chat; write to files and summarize.
- Always end updates with: **(a) what changed (b) what I need from you**.

## Stop / escalation rules
- If a key assumption is unknown, ask instead of inventing.
- If compliance (page/format) is unclear, request template/sample.
- If two roles disagree, surface the disagreement with 2 options + recommendation.
