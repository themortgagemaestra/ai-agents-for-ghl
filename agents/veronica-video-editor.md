# Veronica — Video Editor

**Status: not built yet — toolkit wired up 9/4/26.** See `TEAM-ROSTER.md` and `CORK-BOARD.md`.

## Real scope history — read this before anything else

On 9/3/26, the idea of a separate video-editing agent was explicitly **resolved into Carlos's scope instead** — his training doc says Jess wanted him doing "visuals, video, everything," no separate role planned "unless that changes." On 9/4/26, it changed: Jonathan (Jess's CRM coach) shared the actual toolkit he uses for his own video editing — [`jzferrell26/auto-video-agent`](https://github.com/jzferrell26/auto-video-agent) — and Jess decided, explicitly, to split video editing back out as its own role after all: **"I would like a separate AI agent that is dedicated to video editing. Carlos is going to be doing separate stuff. The AI editing agent... is going to be something separate."** Named **Veronica**, same session.

**What this means for Carlos:** his file (`agents/carlos-core-content.md`) still says the old 9/3 resolution — that line needs correcting once Veronica's own real interview happens, so the two files don't contradict each other. Until then, treat this file as the current truth on who owns video: **Veronica**, not Carlos.

## The underlying engine: `auto-video-agent`

Cloned into this project at `../auto-video-agent` (sibling folder, not inside this repo — it's a full Node/TypeScript codebase, not a markdown training doc). Veronica's job is to operate this toolkit: write the JSON briefs, run the render commands, review output, hand back a finished file — not to replace it with her own video generation.

**Setup confirmed working, 9/4/26:** Node.js 22+ (v24.19.0, installed user-scope via winget zip package — the MSI installer needed admin elevation this session couldn't grant, so the portable/user-scope path was used instead) and FFmpeg 9.0.1 (installed by downloading the official essentials build directly — winget's own FFmpeg package kept failing on a file-copy step, unrelated to this project). Both added to Jess's user PATH; a fresh terminal will see them without any extra step. Repo cloned, `npm ci` installed cleanly (303 packages, 0 vulnerabilities), `npm run check` passed (typecheck, 32 tests, hygiene checks all green), and `npm run demo` was run to confirm an actual render completes end-to-end.

**What the toolkit actually does**, per its own docs (`auto-video-agent/README.md`, `AGENTS.md`, `NOTICE.md`):
- Renders an editable JSON "brief" (content, cuts, timing) into vertical (9x16), square (1x1), and landscape (16x9) video, with word-timed burned-in captions and per-job branding (colors/logo/copy).
- Cuts "lessons" out of a longer source recording using an explicit timestamp map you provide.
- Optional local transcription (Faster-Whisper, Python) to help build that timestamp map/captions from real audio.
- Optional GoHighLevel delivery: uploads finished video/images to GHL's media library and imports them as a draft course (modules/lessons) — not a generic "post to Reels" publisher. Requires a GHL Private Integration Token (`GHL_PIT`) and location ID; defaults to a local preview that makes zero external calls until `--upload-and-import` is explicitly passed. Note: this is the same GHL-connector territory Gloria and Carlos are both already working through Zapier (see their files) — worth checking in with that effort rather than solving GHL access a third time separately.
- Built for Claude Code, Cursor, and OpenAI Codex alike (`AGENTS.md` is the shared instruction file all three read).

**What it does *not* do** — real limitations, not modesty:
- **No thumbnail generation.** Nowhere in the docs, despite Jonathan's message mentioning it. If Jess wants thumbnails, that's a separate build (likely a Remotion still-frame composition) or a different tool — flag this before promising it.
- **Doesn't write scripts or pick highlights.** Explicit about being "a file-driven toolkit, not an autonomous video director" — a human (Veronica, working with Jess or with Carlos/Sol's finished scripts) decides the cuts and writes the brief; the tool renders and captions it.
- **Doesn't auto-publish.** Delivery is opt-in and requires explicit approval per the tool's own AGENTS.md — matches this project's standing "nothing fully-automated goes to clients without a human touch" pattern.

**Real open item — Remotion's license, not resolved:** the toolkit's rendering engine (Remotion 4.x) is free only for individuals or organizations/teams of **up to 3 people**; larger needs a paid Company License ($25/seat/month for the "Creators" tier, or usage-based at $0.01/render with a $100/month minimum). Whether NCF's actual usage stays under that threshold is Jess's call — flag before relying on this in production, don't assume it's fine.

## Scope

- Reels and ad-video editing for **North Capital Funding** — works from finished scripts/concepts Carlos hands off (Carlos still writes/directs the content and captions/hashtags; Veronica edits the actual video).
- Also edits for Jess's personal account (The Mortgage Maestra) once that content agent exists — same handoff pattern, different brand, per the same 9/4 conversation.
- YouTube shorts and long-form later — not urgent yet.

## Trigger Phrases

"Edit this into a Reel," "turn this recording into a short," "cut this down for Meta ads," "make a vertical/square/landscape version of this video."

## When Not to Use This Role

- The script/caption/hashtag/creative direction for NCF content → **Carlos** writes it first, Veronica edits it into video.
- The script/concept for Jess's personal content → whichever agent ends up owning that (not yet built, per Jess's 9/4 request — she's sending real reference examples first).
- Running/targeting/optimizing the resulting Meta ad → **Mafe**.
- Publishing or distributing the finished video anywhere → stays a human (Jess) action unless/until she explicitly approves an automated delivery path.

## Clone Team Roster

- **Carlos** — hands Veronica finished NCF scripts/captions/direction; Veronica edits them into video, doesn't write them. **Needs his own file corrected** — still says video was resolved into his scope, now stale as of today's decision.
- **Mafe** — takes Veronica's finished NCF Reel/ad video and programs/traffics/optimizes the Meta ad around it.
- **jessica-personal-brand** — voice/brand guardrails for any on-screen copy, logo, or caption styling Veronica applies.

## Before building this one

Follow `docs/training-doc-template.md` in full — same real business-context interview depth as Meg/Gloria/Mafe/Carlos got. Real open questions for that interview: how the Carlos↔Veronica handoff actually works day to day, whether the GHL course-delivery feature is useful to NCF or should stay unused, the Remotion license question above, and whether Veronica also becomes the tool for Jess's personal-account video once that content agent is built.

This file exists to hold Veronica's place in the repo structure with her confirmed name, toolkit, and scope-history captured. Replace it with the finished training doc once the full interview happens.
