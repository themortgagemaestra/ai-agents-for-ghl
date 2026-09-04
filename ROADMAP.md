# AI Clone Team — Roadmap (North Capital Funding / Jessica Lindsay)

## Why this exists

Jess attended Amber McCue's "AI Clone Team" workshop (Sept 1, 2026), which teaches training persistent AI "team members" (a defined role + brand voice + expected output) instead of one-off prompting — a Clone File (voice/brand reference) plus specialist roles, trained once and reused. McCue's paid program is $999 (or 2×$550) for 27 pre-built roles. Jess chose to build the equivalent herself, for free, as Claude Skills, since Claude is McCue's own recommended platform anyway and no GHL connector is currently available to build directly inside GoHighLevel.

Core constraint that governs every team member built here: Jess has a strong personal discomfort with AI replacing human, authentic work. Every skill in this roster is designed to protect her time and voice, not replace them — outputs are strategy, drafts, and structure that she (or a trained writer-skill that bakes in her brand voice) still touches, never fully-automated client-facing material.

Training standard: each team member should be thoroughly trained before it's considered done — matching Amber McCue's own benchmark (hours of training per role, ~15 pages for a role like the competitive-brief specialist), not a quick job description. Don't mark a role "built" until it has real business context, not just a generic mandate.

## Team roster

See `TEAM-ROSTER.md` — the current source of truth for the full team: every name, role, and build status. This section used to duplicate that list; now it just points there so the two can't drift out of sync.

Quick summary as of 9/4/26: 12 team members confirmed (Meg, Nia, Gloria, Mafe, Carlos, Linda, Wanda, Gia, Carrie, Ricky, Carla, Veronica). The 9/3 call to fold video into Carlos's scope was reopened and reversed on 9/4 — Jess wants video editing as its own dedicated role after all, now that a real toolkit exists to run it. Named Veronica; her toolkit (Node/FFmpeg/Remotion) is installed and confirmed rendering. **Meg, Gloria, Mafe, and Carlos are fully built and trained.** Gloria's core job is bridging the team's pipeline Google Doc into GoHighLevel (no native connector yet — Zapier is the live path being pursued as of 9/3/26). Mafe runs Meta ads for the Digital HELOC product across NCF's four licensed states (FL/NJ/CO/PA), working from creative Jess and Carlos supply, with Jess reviewing campaigns before launch. Carlos is NCF's social media manager across Instagram, Facebook, and LinkedIn, producing finished posts (not just ideas), with Jess reviewing every post before it goes live. Standing process: one agent built completely before moving to the next.

## Platform decision

Claude Skills, backed by a shared memory "Clone File" (Jess's profile, brand, and business-area facts) that every team member reads before acting — not inside GoHighLevel directly (no GHL connector available as of Sept 2026). If a GHL connector becomes available later, this logic can be adapted into GHL workflows/agents at that point.

## Organization scheme

- **Claude Skills** = the live, working agents — account-wide, auto-trigger by description, no need for one Claude Project per agent.
- **This GitHub repo** = the source of truth once Claude Code is set up: one file per agent, the training-doc template, and the execution ledger.
- **Google Drive "AI Agents" folder** = the original human-readable master/backup copy — kept as a mirror during the transition.
- **Jess's Claude memory** = the shared Clone File every agent reads from (brand voice, business facts, goals) — not duplicated per agent.

## Status log

See `EXECUTION-LEDGER.md` for the running, dated log of what's been done and what's next.
