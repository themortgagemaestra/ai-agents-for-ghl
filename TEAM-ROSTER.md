# AI Clone Team — Roster Planning

One page to see the whole team: who's built, what each one actually does, and who's still available to build. Read this before deciding what gets built next — update it any time the roster changes.

## Confirmed team (as of 2026-09-02)

Jess's own numbered list, roles as she described them. This is now the team, replacing the old default Carrie → Linda build order.

| # | Name | Role | Status |
|---|---|---|---|
| 1 | **Meg** | Marketing strategist / CMO-in-a-box | Built & trained — `agents/meg-ai.md` |
| 2 | **Nia** | Newsletter & email — absorbs `ncf-email-builder` | Identity confirmed — `agents/nia-newsletter.md` (interview pending) |
| 3 | **Bridgette** | Morning brief | Scope confirmed, build greenlit — `agents/bridgette-morning-brief.md` |
| 4 | **Mafe** (Maria Fernanda) | Meta ads specialist | Flagged urgent by Jess — build ASAP — `agents/mafe-meta-ads.md` |
| 5 | **Callie** | Core content — mortgage & real estate content, personality-first | Stub — `agents/callie-core-content.md` |
| 6 | **Linda** | Landing page builder, fully GHL-integrated | Stub — `agents/linda-landing-page-builder.md` |
| 7 | **Wanda** | The Workflow Queen — GHL workflows & drip campaigns | Stub — `agents/wanda-workflow-queen.md` |
| 8 | **Gia** | The GHL Queen — CRM management & optimization | Stub — `agents/gia-ghl-queen.md` |
| 9 | **Carrie** | Content-to-conversion — reviews/rewrites sales & landing page copy | Confirmed back on the team 9/2/26 — `agents/carrie-content-to-conversion.md` |
| 10 | **Grecia** | Evening/daily wrap-up brief, Bridgette's counterpart | Stub — `agents/grecia-evening-wrapup.md` |

Naming resolved 9/2/26: #9 was briefly dropped, then confirmed back as Carrie. #10 (originally proposed as "Grace") is now **Grecia** — Jess wants some names in the roster to be Spanish.

---

## Role detail (what's confirmed so far, beyond the one-liner)

**Bridgette — Morning Brief.** Modeled loosely on a real demo from Amber McCue's AI Clone Team training (a "chief of staff" morning brief), then stripped hard of the decorative filler in that version (energy/astrology cards, vague "ratio check" paragraphs, hedged padding) per Jess's direction: plain, direct, eighth-grade-simple language, no bullshit. Every morning, Bridgette gives Jess:
1. **One Big Thing today** — a single headline task, bolded, one line on why.
2. **On deck** — a short runner-up list for after the Big Thing is done.
3. A reminder to write her 6 gratitudes — in her physical journal, not captured digitally.
4. A one-line social media content spark (not a full draft — that's Callie's/Nia's job).
5. A market or loan-product update.
6. Whatever got pushed over from the night before by Grecia, read from the shared log (`agents/daily-brief-log.md`).

Explicitly out of scope for now: email/GHL inbox triage — real value, but needs the GHL/email integration this project hasn't built yet. Later phase, not v1.

**Grecia — Evening/Daily Wrap-Up Brief.** Mirrors a ritual Jess already does by hand: writing 6 wins/successes before shutting down for the day. Grecia's job:
1. Help Jess pinpoint at least 6 things she accomplished that day. *(Open question: physical-journal-only like gratitude, or captured in the shared log? Not yet confirmed.)*
2. Note what didn't get done.
3. Decide what becomes tomorrow's Big Thing, and write it to the shared log for Bridgette.
Tone: part personal assistant, part coach — celebrates wins, keeps Jess moving toward her goals, grounded in gratitude. Not just a status report.

**The shared log.** Bridgette and Grecia write into one running file, `agents/daily-brief-log.md` (same newest-entry-at-top pattern as `EXECUTION-LEDGER.md`) — that's how they hand off to each other without needing any live integration.

**Mafe — Meta Ads.** Full lifecycle expert: budgets, A/B testing, ad copy, every component of a Meta ad, and funneling those leads into GoHighLevel start to finish. Jess called this one out as the most urgent to build.

**Callie — Core Content.** Mortgage and real estate content ideas with real personality — explicitly not generic, not AI-sounding. Reference points Jess named: Caroline Sells Colorado and The Mortgage Nerd on Instagram (real-talk, non-"mortgagey" mortgage content). Also needs to generate content that isn't about mortgages at all — general/lifestyle/interest content that shows Jess as a multi-faceted person, not just a lender.

**Linda — Landing Pages.** Full GHL landing pages, not just copy — fully integrated with Jess's social media, email, and texting, not standalone pages.

**Wanda — The Workflow Queen.** GHL workflow and drip-campaign expert. Builds engaging workflows integrating SMS, email, and social; converts cold → warm → hot leads into closed loans; specifically responsible for routing Meta-sourced leads (from Mafe's ads) into the right workflows and keeping them organized.

**Gia — The GHL Queen.** CRM best-practices expert — keeps GHL clean, neat, optimized. Takes notes from the Monday pipeline meeting (Jess, her mom, and Bobby) and turns them into updates across opportunities, contacts, and workflows in GHL. Answers Jess's GHL questions and gives usage guidance.

---

## Reference & infrastructure (not agents — feed the agents above)

Confirmed 9/2/26 — these stay as rulebook/fact-sheet skills every agent checks before producing anything, not standalone teammates:

| Name | What it holds | Feeds |
|---|---|---|
| `jessica-personal-brand` | Personal brand identity, voice, and contact-info rules | Every public-facing agent |
| `ncf-digital-heloc` | Digital HELOC product specs & process facts | Any agent writing about the HELOC product |
| Clone File (Jess's Claude memory) | Brand voice, business facts, goals shared across the whole team | Every agent |

---

## Full candidate roster (Amber McCue's 27 roles — anyone not yet claimed)

For reference, in case a future need matches one of these more precisely than a custom name. From `docs/training-doc-template.md`.

### Content
Callie claimed · Linda claimed · Riley (Repurposing), Glenda (Guest Research), Wynn (Podcast Scripts), Polly (Podcast Producer), Crystal (Carousels), Quinn (Curriculum Designer) — unclaimed

### Growth
Meg claimed · Carrie claimed · Izzy (Marketing Insights), Suzie (Social Media), Lena (LinkedIn), Manny (ManyChat), Lakeisha (Launch Emails) — unclaimed
*(Mafe, Wanda, Gia are custom roles Jess created — not from Amber's list.)*

### Ops
Nia claimed (mapped from "Nia — Newsletter") · Bridgette claimed (mapped from "Bridgette — Morning Brief") · Cassie (Customer Service), Dorothy (Delegation), Rachel (Process Requests), CEO Time (Weekly Planning), Sloane (SOP Creation), Hope (Interview Questions), Willa (Daily Wellness) — unclaimed
*(Grecia is a custom role Jess created — not from Amber's list.)*

### Strategy
Marlow (Modern CFO), Allie (Market & Competitive), Betty (Business Plan Builder) — unclaimed

---

## Build order

1. Roster planning — done, this doc.
2. **Bridgette** — confirmed 9/2/26 as the next build. Real business-context interview (`docs/training-doc-template.md`) starts now, same depth as Meg got.
3. **Mafe** — flagged as most urgent by Jess. Next after Bridgette.
4. Everyone else (Carrie, Callie, Linda, Wanda, Gia, Grecia, Nia's full interview) — order still open.
