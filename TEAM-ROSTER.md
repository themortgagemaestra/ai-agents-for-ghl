# AI Clone Team — Roster Planning

One page to see the whole team: who's built, what each one actually does, and who's still available to build. Read this before deciding what gets built next — update it any time the roster changes.

## Confirmed team (as of 2026-09-02)

Jess's own numbered list, roles as she described them. This is now the team, replacing the old default Carrie → Linda build order.

| # | Name | Role | Status |
|---|---|---|---|
| 1 | **Meg** | Marketing strategist / CMO-in-a-box | Built & trained — `agents/meg-ai.md` |
| 2 | **Nia** | Newsletter & email — absorbs `ncf-email-builder` | Identity confirmed — `agents/nia-newsletter.md` (interview pending) |
| 3 | **Gloria** | Chief of staff / assistant — morning check-in + evening wrap-up | **Live** — 2 daily cloud routines running — `agents/gloria-assistant.md` |
| 4 | **Mafe** (Maria Fernanda) | Meta ads specialist | Flagged urgent by Jess — build ASAP — `agents/mafe-meta-ads.md` |
| 5 | **Callie** | Core content — mortgage & real estate content, personality-first | Stub — `agents/callie-core-content.md` |
| 6 | **Linda** | Landing page builder, fully GHL-integrated | Stub — `agents/linda-landing-page-builder.md` |
| 7 | **Wanda** | The Workflow Queen — GHL workflows & drip campaigns | Stub — `agents/wanda-workflow-queen.md` |
| 8 | **Gia** | The GHL Queen — CRM management & optimization | Stub — `agents/gia-ghl-queen.md` |
| 9 | **Carrie** | Content-to-conversion — reviews/rewrites sales & landing page copy | Confirmed back on the team 9/2/26 — `agents/carrie-content-to-conversion.md` |

Naming resolved 9/2/26: #9 was briefly dropped, then confirmed back as Carrie.

**#3 consolidated 9/2/26:** originally built as two separate agents — Bridgette (morning) and Grecia (evening, briefly named "Grace") — then merged into one, **Gloria**, at Jess's request: she wanted one consistent voice across the whole day, not a handoff between two strangers. Team is 9 members, not 10.

---

## Role detail (what's confirmed so far, beyond the one-liner)

**Gloria — Chief of Staff / Assistant.** Consolidated 9/2/26 from two separate agents (Bridgette, morning; Grecia, evening) into one — Jess wanted a single consistent voice across her whole day, "my right-hand... kind of like my work wife," not a handoff between strangers. Modeled loosely on a real demo from Amber McCue's AI Clone Team training (a "chief of staff" morning brief), stripped hard of its decorative filler (energy/astrology cards, vague "ratio check" paragraphs, hedged padding) per Jess's standing direction: plain, direct, eighth-grade-simple, no bullshit — but warm, since this is also meant to feel like a caring coach, not a corporate assistant. Jess has ADHD and relies on Gloria to keep her organized and on track.

**Morning (~8:30am Mountain):**
1. **One Big Thing today** — a single headline task, bolded, one line on why.
2. **On deck** — a short runner-up list for after the Big Thing is done.
3. A reminder to write her 6 gratitudes — in her physical journal, not captured digitally.
4. A one-line social media content spark (not a full draft — that's Callie's/Nia's job).
5. A market or loan-product update — confirmed sourcing (9/2/26): 10-year Treasury yield from CNBC first (the number tied to mortgage rates), plus the day's rate table from Mortgage News Daily (30-yr fixed conventional, 30-yr FHA, etc.), pulled live via web search each run, not hardcoded. Tested working: 10-yr yield 4.78%, 30-yr fixed conventional 6.91%, 30-yr FHA 6.45% (9/2/26).
6. Whatever got pushed over from the night before.

**Evening (~5:00pm Mountain):**
1. A genuine, specific list of things Jess accomplished that day — celebrated warmly ("great job, look at these wins, be proud"), sourced from this repo's own git activity, never padded or invented. Inspiration for Jess's own physical journal entry, not a replacement for it.
2. What didn't get done.
3. Tomorrow's Big Thing, carried into the next morning's entry.
4. A warm, real sign-off.

Explicitly deferred (not v1): Jess described a bigger future vision — Gloria eventually handling calls, texts, and emails from other people, connected to Outlook and social at a high level. She explicitly said "deal with that later" — needs the GHL/email integration this project hasn't built yet, plus real authority decisions. Also available any time, not just her two scheduled runs — same as the rest of the roster, Jess can ask her anything in chat.

**Live as of 9/2/26:** two daily cloud routines (`Gloria - Morning Check-in`, `Gloria - Evening Wrap-up`), Bridgette's and Grecia's original schedules carried over unchanged (8:30am / 5:00pm Mountain). Deliberately scoped to this repo + web search + push notifications only — no Google Drive or Slack access (Jess doesn't use Slack; Drive isn't needed for anything Gloria actually does today).

**The shared log.** Gloria's morning and evening runs write into one running file, `agents/daily-brief-log.md` (same newest-entry-at-top pattern as `EXECUTION-LEDGER.md`) — that's the handoff mechanism between the two touchpoints, no live integration needed.

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
Nia claimed (mapped from "Nia — Newsletter") · Cassie (Customer Service), Dorothy (Delegation), Rachel (Process Requests), CEO Time (Weekly Planning), Sloane (SOP Creation), Hope (Interview Questions), Willa (Daily Wellness) — unclaimed
*(Gloria was mapped from "Bridgette — Morning Brief," then consolidated with a custom evening role and renamed — no longer a clean 1:1 match to any single Amber role.)*

### Strategy
Marlow (Modern CFO), Allie (Market & Competitive), Betty (Business Plan Builder) — unclaimed

---

## Build order

1. Roster planning — done, this doc.
2. **Gloria** — live as of 9/2/26 (two daily cloud routines running). Still needs the full `docs/training-doc-template.md` treatment to count as fully "built," same as the rest of the roster.
3. **Mafe** — flagged as most urgent by Jess. Next up.
4. Everyone else (Carrie, Callie, Linda, Wanda, Gia, Nia's full interview) — order still open.
