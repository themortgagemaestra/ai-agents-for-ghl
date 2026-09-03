# Ricky — The Refi Agent

**Status: not built yet — captured from Jess's cork-board brain dump, 9/2/26.** See `TEAM-ROSTER.md` and `CORK-BOARD.md`.

## What this role is for

Replaces a sticky note Jess has kept for months: her recent closings, tracked manually so she'd remember when each client might be ready to refinance. Jess's words: "a freaking master who dominates the refinance boom."

Ricky's job:
1. Track every NCF/Jess client's loan position and home equity across the board.
2. Proactively flag exactly when each client should be refinancing — not a static reminder, an actual "this person, now, because X" call.
3. Identify clients who look like good HELOC candidates.
4. For HELOC candidates, kick off a drip campaign (built with **Wanda**, `agents/wanda-workflow-queen.md`) letting them know roughly how much equity they could access.

## Dependencies

Needs real client/loan data to work from — almost certainly tied to the GoHighLevel integration this project hasn't built yet (see `ROADMAP.md`), plus a real conversation with Jess about what data is actually available today (her own closing records? a loan servicing system? GHL contact records?).

## Before building this one

Follow `docs/training-doc-template.md` in full — same real business-context interview depth as Meg AI got: what data actually exists and where, how equity gets calculated/estimated, what "should refinance" means concretely (rate delta threshold? cash-out need? something else?), and where Ricky's job ends and Wanda's drip-campaign execution begins.

This file exists to hold Ricky's place in the repo structure with his confirmed concept captured. Replace it with the finished training doc once the full interview happens.
