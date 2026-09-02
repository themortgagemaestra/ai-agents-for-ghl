# AI Clone Team — Roadmap (North Capital Funding / Jessica Lindsay)

## Why this exists

Jess attended Amber McCue's "AI Clone Team" workshop (Sept 1, 2026), which teaches training persistent AI "team members" (a defined role + brand voice + expected output) instead of one-off prompting — a Clone File (voice/brand reference) plus specialist roles, trained once and reused. McCue's paid program is $999 (or 2×$550) for 27 pre-built roles. Jess chose to build the equivalent herself, for free, as Claude Skills, since Claude is McCue's own recommended platform anyway and no GHL connector is currently available to build directly inside GoHighLevel.

Core constraint that governs every team member built here: Jess has a strong personal discomfort with AI replacing human, authentic work. Every skill in this roster is designed to protect her time and voice, not replace them — outputs are strategy, drafts, and structure that she (or a trained writer-skill that bakes in her brand voice) still touches, never fully-automated client-facing material.

Training standard: each team member should be thoroughly trained before it's considered done — matching Amber McCue's own benchmark (hours of training per role, ~15 pages for a role like the competitive-brief specialist), not a quick job description. Don't mark a role "built" until it has real business context, not just a generic mandate.

## Team roster

**Built, pre-existing:**
- `ncf-email-builder` — bilingual weekly emails & monthly newsletters
- `jessica-personal-brand` — personal voice/positioning guardrails (part of the "Clone File")
- `ncf-digital-heloc` — product knowledge reference
- `morning` — daily brief/dashboard (not yet NCF-customized)

**Built and fully trained:**
- **Meg AI** (`agents/meg-ai.md`) — marketing strategist / CMO-in-a-box. Trained on Jess's real competitive landscape, current-state audit, confirmed goals, time budget, and decision authority. Prioritizes, audits, builds plans; routes actual writing to the right existing skill rather than writing it herself. Quiz's #1 recommended starting point.

**Not built yet, in priority order:**
- **Carrie** — content-to-conversion: reviews/rewrites sales & landing page copy specifically for conversion (quiz's 2nd priority). Needs the same depth of onboarding as Meg AI.
- **Linda** — landing page builder: full landing/sales pages, not just copy.
- Callie (core content creator) is quiz's 3rd priority but is largely already covered by `ncf-email-builder`.

## Platform decision

Claude Skills, backed by a shared memory "Clone File" (Jess's profile, brand, and business-area facts) that every team member reads before acting — not inside GoHighLevel directly (no GHL connector available as of Sept 2026). If a GHL connector becomes available later, this logic can be adapted into GHL workflows/agents at that point.

## Organization scheme

- **Claude Skills** = the live, working agents — account-wide, auto-trigger by description, no need for one Claude Project per agent.
- **This GitHub repo** = the source of truth once Claude Code is set up: one file per agent, the training-doc template, and the execution ledger.
- **Google Drive "AI Agents" folder** = the original human-readable master/backup copy — kept as a mirror during the transition.
- **Jess's Claude memory** = the shared Clone File every agent reads from (brand voice, business facts, goals) — not duplicated per agent.

## Status log

See `EXECUTION-LEDGER.md` for the running, dated log of what's been done and what's next.
