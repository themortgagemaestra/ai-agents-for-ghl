# The Cork Board — Ideas Parking Lot

Jess has a real cork board in her office (three columns: **Ideas / In Progress / Complete**), set up back when she started working with Tiffany Rose, her one-to-many marketing coach. The sticky notes on it had gone stale — mostly from before she moved, back in her old apartment — so on 9/2/26 she took them all down to start fresh, but wanted everything on them captured first so nothing gets lost in the refresh.

This file is the digital version of that board. **Nothing here is being built right now** — this is the parking lot, not the active roster. When Jess is ready to tackle something on this list, it graduates: a new agent gets a real stub in `agents/` and a row in `TEAM-ROSTER.md`, or a to-do gets done and moves to "Complete" below.

**How to use this:** newest brain-dump session at the top. Keep items in whichever column they belong (Idea / In Progress / Complete). Never delete an item just because it's old — move it to Complete, or leave it in Ideas if it's still just an idea.

---

## Captured 2026-09-02 (the cork board refresh)

### Ideas → new agents

**Ricky — the Refi Agent.** Replaces a sticky note of Jess's recent closings, kept only to manually track when to reach back out about refinancing. Ricky's job: look across every NCF/Jess client, track their equity and loan position, and proactively flag exactly when each one should refinance. If a client looks like a HELOC candidate, Ricky kicks off a drip campaign (built with **Wanda**) telling them roughly how much equity they could access. Full spec captured in `agents/ricky-refi-agent.md`.

**Carla — Client Happiness + Artistic Design.** Started as two separate ideas Jess merged into one: (1) a "chief client happiness officer" — client retention, referrals, client-experience ideas (see the closings/client-love notes below); (2) an artistic, technically sharp design/content person who builds beautiful lead-magnet guides (the "Moving to Denver" idea below). Jess combined them into one role and named her Carla. Full spec captured in `agents/carla-client-happiness.md`.

**A dedicated video-editing agent — raised, resolved into Carlos, then reopened. Graduated 9/4/26 as its own role, Veronica.** Raised during Mafe's interview (9/2/26): "we need another AI agent to edit videos for Instagram Reels, for Meta ads, and then eventually for YouTube, both shorts and long form, and content in general." Resolved into Carlos's scope on 9/3/26 during his real interview. Reopened 9/4/26 when Jonathan actually shared the toolkit he uses ([`jzferrell26/auto-video-agent`](https://github.com/jzferrell26/auto-video-agent)) — Jess decided video editing should be its own dedicated agent after all, distinct from Carlos. See `agents/veronica-video-editor.md`.

**Carlos's scope — fully resolved 9/3/26.** Renamed from Callie the same day (Jess's own words: these are her AI agents, not her clones, and content roles don't have to default female — same scope, new name). Full real interview happened 9/3/26, not just the Mafe-interview scope note from the day before: Carlos is NCF's actual social media manager across Instagram, Facebook, and LinkedIn — see `agents/carlos-core-content.md` for the complete training doc.

### Ideas → Gloria's job

- **Reading list.** Books Jess wants to read: *Go High Level*, *12 Week Work Year*. Gloria should keep a running list and surface a suggestion when there's room for it — maybe not every day; a monthly cadence might fit better.
- **A monthly brief**, separate from the daily AM/PM ones — stats-focused: leads in, applications, sources, everything. Gloria pulls this by coordinating with **Mafe** (once built) and GoHighLevel (once connected) — depends on both, not buildable yet.
- **General to-do tracking** — not everything needs its own agent or its own cork board space. Confirmed to-dos for Gloria to hold onto:
  - Update the North Capital Funding bios and photos on the website.
  - New Jersey and Colorado continuing education (CE) — due dates/requirements.
  - **Georgia and Texas mortgage licensing** — real step-by-step instructions in plain language (her words: "eighth-grade-level," "don't just send me the NMLS website"), plus full cost breakdown for each state, plus a proactive flag if there's a state that would be easy for her given an existing connection there. **Scheduled for Friday, September 4, 2026** (moved off Thursday 9/3 — explicitly not a tomorrow task). Jess also raised the idea of a dedicated **compliance function** (part of Gloria, or its own future agent) that owns this kind of research permanently, rather than it being a one-off task — not scoped further yet, just noted here.

### Ideas → Linda's job

- **Link tree landing page**, built in GoHighLevel instead of paying for a Linktree subscription — something like "themortgagemaestra.com" with all her links. Confirmed as a real task for Linda once she's built.

### Ideas → merch / marketing (undeveloped — Jess's own words: "weird, random, nothing ideas yet")

One sticky note, mostly loose fragments, captured as-is rather than over-interpreted:
- North Capital Funding
- "Sasha the Mortgage" (unclear — name idea? content idea? not specified)
- Merch ideas generally
- "Unlock Your Bright Future" (tagline/campaign name?)
- Bookmarks (as a giveaway/merch item)
- Plannable seed packets — Jess specifically likes this one; it's a spring item, and she noted it's autumn now, so there's real lead time to plan and execute it well
- Resources for realtors (a lead-magnet/referral-partner idea, unspecified)

### Ideas → client experience (feeds Carla)

From the same "how I want to handle closings/clients" note:
- An address stamper with the client's new home address, given at closing on purchases.
- A closing gift paired with a Google review ask.
- Get notified whenever a past client's name shows up in "junk mail" (marketing mail from competitors) — treat it as a cue to reach out/ask for a referral.
- The bigger goal behind all of these: take better care of clients than anyone else does, and figure out what actually makes their experience better — this is Carla's real mandate, not just a task list.

### Ideas → lead magnets (feeds Carla + Linda + the future social/content role)

- **Moving to Denver / Denver Neighborhoods / Buying Your First Home in Denver** — beautiful, genuinely well-designed PDF guides (neighborhoods, suburbs, local info, relocation info), not generic AI-slop design. Used as lead magnets: people request them, it ties into GoHighLevel, promoted via whichever agent ends up owning social media.

### Content idea

- "5 Scripts for Overcoming Objections of ___" — e.g., objections to buying when rates are high, objections that a new build isn't always the better choice, etc. A content template/series idea for whoever ends up owning social scripts (see the open Carlos question above).

---

## In Progress

**Veronica — Video Editor.** Graduated 9/4/26: named by Jess, real stub captured in `agents/veronica-video-editor.md`, row added to `TEAM-ROSTER.md`. Toolkit ([`jzferrell26/auto-video-agent`](https://github.com/jzferrell26/auto-video-agent)) cloned, Node.js/FFmpeg installed, `npm ci` / `npm run check` / `npm run demo` all passed — the render pipeline is confirmed working end to end. Not yet run against real footage, and the real business-context interview hasn't happened. **Carlos's file still needs a correction pass** — it currently says video was resolved into his scope; that's superseded as of today.

**Jess's personal-brand content agent (working name attempts: "Sol," rejected).** Raised 9/4/26, same session as Veronica: a dedicated agent for Jess's own account (The Mortgage Maestra), separate from Carlos/NCF — music, the band, yoga, her 135-year-old house, Latina identity, dark humor, journaling, the arts. First content ideas offered (three concepts for a rainbow-morning-light video) were rejected as generic. **Paused, not abandoned** — Jess is sending real reference posts/accounts she actually likes, same calibration approach used for Carlos (Connor D. Cole, Caroline Sells Colorado). Not yet named, scoped, or stubbed — waiting on those references before building anything further.

## Complete

*(nothing here yet)*
