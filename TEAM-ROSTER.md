# AI Clone Team — Roster Planning

One page to see the whole team: who's built, what each one actually does, and who's still available to build. Read this before deciding what gets built next — update it any time the roster changes.

## Confirmed team (as of 2026-09-02)

Jess's own numbered list, roles as she described them. This is now the team, replacing the old default Carrie → Linda build order.

| # | Name | Role | Status |
|---|---|---|---|
| 1 | **Meg** | Marketing strategist / CMO-in-a-box | Built & trained — `agents/meg-ai.md` |
| 2 | **Nia** | Newsletter & email — absorbs `ncf-email-builder` | Identity confirmed — `agents/nia-newsletter.md` (interview pending) |
| 3 | **Gloria** | Chief of staff — pipeline/GHL sync, business numbers, morning check-in + evening wrap-up | **Built & trained** — live, 2 daily cloud routines — `agents/gloria-assistant.md` |
| 4 | **Mafe** (Maria Fernanda) | Meta ads specialist — Digital HELOC campaigns, FL/NJ/CO/PA | **Built & trained** — `agents/mafe-meta-ads.md` |
| 5 | **Carlos** | NCF's social media manager (IG/FB/LinkedIn) + ad/Reels script development with Jess, hands finished scripts to Mafe | **Built & trained** — `agents/carlos-core-content.md` |
| 6 | **Linda** | Landing page builder, fully GHL-integrated | Stub — `agents/linda-landing-page-builder.md` |
| 7 | **Wanda** | The Workflow Queen — GHL workflows & drip campaigns | Stub — `agents/wanda-workflow-queen.md` |
| 8 | **Gia** | The GHL Queen — CRM management & optimization | Stub — `agents/gia-ghl-queen.md` |
| 9 | **Carrie** | Content-to-conversion — reviews/rewrites sales & landing page copy | Confirmed back on the team 9/2/26 — `agents/carrie-content-to-conversion.md` |

Naming resolved 9/2/26: #9 was briefly dropped, then confirmed back as Carrie.

**#3 consolidated 9/2/26:** originally built as two separate agents — Bridgette (morning) and Grecia (evening, briefly named "Grace") — then merged into one, **Gloria**, at Jess's request: she wanted one consistent voice across the whole day, not a handoff between two strangers. Team is 9 named roles in this numbered list; 11 total counting Ricky and Carla below.

## Captured but not yet build-queued

From Jess's cork-board brain dump (9/2/26) — real, named, reasonably scoped, but not yet slotted into build priority order the way #1–9 above are. Full context in `CORK-BOARD.md`.

| Name | Role | Status |
|---|---|---|
| **Ricky** | The Refi Agent — tracks client equity/loan position across the board, flags refinance timing, kicks off HELOC drip campaigns with Wanda | Concept captured — `agents/ricky-refi-agent.md` |
| **Carla** | Client happiness + artistic design — client retention/experience ideas, plus beautiful lead-magnet guides (e.g. "Moving to Denver") | Concept captured — `agents/carla-client-happiness.md` |
| **Veronica** | Video editor — Reels/Meta ad video for NCF now, Jess's personal account and YouTube shorts/long-form later | Named & scoped 9/4/26, toolkit installed and confirmed working (Node/FFmpeg/Remotion render tested end-to-end) — `agents/veronica-video-editor.md` |

**Reopened and reversed, 9/4/26:** the 9/3 resolution below (video folded into Carlos) got overridden — Jonathan shared the actual toolkit he uses ([`jzferrell26/auto-video-agent`](https://github.com/jzferrell26/auto-video-agent)), and Jess decided, explicitly, that video editing is its own separate agent after all — **"Carlos is going to be doing separate stuff. The AI editing agent... is going to be something separate."** Named Veronica. **`agents/carlos-core-content.md` still has the old 9/3 language and needs a correction pass** so the two files stop contradicting each other — not done yet.

~~**Resolved 9/3/26:** this was Carlos's real interview all along — social-media script writing, content calendar, and video/visual production are now all explicitly his scope (see `agents/carlos-core-content.md`). The separate future video-editing role idea is resolved into Carlos, not spun off on its own.~~ *(superseded 9/4/26, see above — left here rather than deleted so the history of the decision is visible, not just the reversal.)*

---

## Role detail (what's confirmed so far, beyond the one-liner)

**Gloria — fully trained 9/2/26, see `agents/gloria-assistant.md` for the complete doc** (this section used to duplicate it — now just points there so the two can't drift out of sync). Short version: her core job is bridging the team's real pipeline-tracking system — a running Google Doc, not GHL directly — into GoHighLevel (and eventually Arrive), since manual GHL data entry wasn't working for the team. Plus the AM/PM daily touchpoints, general to-do tracking, and a monthly stats brief once GHL/Arrive access exists. Live as two daily cloud routines (`Gloria - Morning Check-in`, `Gloria - Evening Wrap-up`, 8:30am / 5:00pm Mountain), now with Google Drive access enabled (Slack stays off — Jess doesn't use it).

**Mafe — Meta Ads.** Full lifecycle expert: budgets, A/B testing, ad copy, every component of a Meta ad, and funneling those leads into GoHighLevel start to finish. Jess called this one out as the most urgent to build.

**Carlos — fully trained 9/3/26, see `agents/carlos-core-content.md` for the complete doc.** Short version: NCF's actual social media manager — Instagram, Facebook, and LinkedIn, 3-4 posts/week, finished output (caption + hashtags + real visual/video direction), not just ideas. Four content pillars: first-time homebuyers, Digital HELOC spotlights, client wins (starting from the unused Google-review backlog), and fully-Spanish community-facing posts. Default NCF team voice; becomes a Mortgage Maestra "collaboration" post only when Jess is on camera or content is hyper-local. Voice references: Caroline Sells Colorado, Connor D. Cole (creative risk-taking), The Mortgage Nerd (helpful, not her cheesy branding).

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
Linda claimed · Riley (Repurposing), Glenda (Guest Research), Wynn (Podcast Scripts), Polly (Podcast Producer), Crystal (Carousels), Quinn (Curriculum Designer) — unclaimed
*(Carlos was renamed from Amber's "Callie" on 9/3/26 — Jess wanted a "boy name," these are her agents, not Amber's clones. Carlos no longer maps to any single Amber role; treat him as a custom name like Mafe/Wanda/Gia.)*

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

**Standing process, confirmed 9/2/26: one at a time, fully finished before moving on — no more gaps.**

1. Roster planning — done, this doc.
2. ~~Gloria~~ — **done, fully trained 9/2/26.** Reprioritized to #1 (over Mafe) on Jess's call — "Gloria could run the business if I wasn't there." Same depth as Meg.
3. ~~Mafe~~ — **done, fully trained 9/2/26.** Flagged urgent by Jess from the start.
4. **Next session starts here (refined late 9/2/26). Priority for 9/3, in order:**
   1. **GHL ↔ pipeline-doc sync with Gloria — "more important than anything else."** Checked the night before: not connected — no GoHighLevel connector exists in this environment yet (confirmed via registry search, 9/2/26). Real blocker, not a settings toggle. Jess wants to show Gloria the actual running Google Doc and make real progress toward the two staying synchronous.
   2. **Meta ads prep with Carlos + Mafe** — write/finalize scripts, record any additional video needed (one good one already exists), get everything organized and ready to launch the next round of Digital HELOC ads.
   3. Testing Meg is still worth doing, just no longer positioned as the literal first task.
5. ~~Carlos~~ — **done, fully trained 9/3/26.** NCF's social media manager across IG/FB/LinkedIn — see `agents/carlos-core-content.md`.
6. **Then continue building.** Order still open: Carrie, Linda, Wanda, Gia, Nia's full interview — Jess's call.
7. **Georgia/Texas licensing research — scheduled for Friday, September 4, 2026.** Explicitly not part of 9/3.
