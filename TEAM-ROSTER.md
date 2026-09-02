# AI Clone Team — Roster Planning

One page to see the whole team: who's built, who's a real agent vs. background reference, and who's still available to build. Read this before deciding what gets built next — update it any time the roster changes.

## Answering the open question: is the newsletter skill an agent? Is the brand kit?

Short version: **the newsletter builder should probably get a name — the brand kit shouldn't.**

The distinction that matters: does it *produce output on request* (an agent/teammate), or does it *feed facts and rules to other agents* (reference material, part of the Clone File)?

- **`ncf-email-builder`** writes bilingual weekly emails and monthly newsletters — that's a deliverable, the same shape of work as Carrie or Linda's. It reads like a real teammate that just never got a name. Amber McCue's own 27-role roster (already in `docs/training-doc-template.md`) has a role that's exactly this: **Nia — Newsletter** (Ops department). Proposed: rename/reframe this skill as **Nia**.
- **`morning`** (the daily brief) is the same situation — it produces a standing deliverable, just not yet customized to NCF. Amber's roster has **Bridgette — Morning Brief** (Ops). Proposed: **Bridgette**, once it's NCF-customized.
- **`jessica-personal-brand`** doesn't produce anything on its own — it's the ruleset every other agent checks before writing anything public-facing (how your name/title appear, when "The Mortgage Maestra" applies, contact block, etc.). That's infrastructure, like a style guide, not a teammate. No name needed.
- **`ncf-digital-heloc`** is the same shape — a facts reference (rates, LTV, credit pull mechanics) every agent pulls from. No name needed.

This is a judgment call, not a fixed rule — say the word if you'd rather name the reference skills too, or *not* name Nia/Bridgette and leave them as plain utility skills.

---

## Active team (agents — produce work, have a persona)

| Name | Role | Department | Status | Lives at |
|---|---|---|---|---|
| **Meg** (Meg AI) | Marketing strategist / CMO-in-a-box | Growth | ✅ Fully trained | `agents/meg-ai.md` |
| **Nia** *(proposed name)* | Newsletter & email writer — bilingual weekly emails, monthly newsletters | Ops | ⚠️ Built, but as an untrained/unnamed skill (`ncf-email-builder`) — no business-context interview yet | Claude Skill `ncf-email-builder` |
| **Bridgette** *(proposed name)* | Morning brief / daily dashboard | Ops | ⚠️ Built, generic — not yet NCF-customized | Claude Skill `morning` |
| **Carrie** | Content-to-conversion — reviews/rewrites sales & landing page copy | Growth | 🔲 Stub only, not built | `agents/carrie-content-to-conversion.md` |
| **Linda** | Landing page builder — full pages, not just copy | Content | 🔲 Stub only, not built | `agents/linda-landing-page-builder.md` |

## Reference & infrastructure (not agents — feed the agents above)

| Name | What it holds | Feeds |
|---|---|---|
| `jessica-personal-brand` | Personal brand identity, voice, and contact-info rules | Every public-facing agent |
| `ncf-digital-heloc` | Digital HELOC product specs & process facts | Any agent writing about the HELOC product |
| Clone File (Jess's Claude memory) | Brand voice, business facts, goals shared across the whole team | Every agent |

---

## Full candidate roster (Amber McCue's 27 roles, for picking what's next)

Everything below is from Amber's original roster (`docs/training-doc-template.md`), sorted by her own department groupings. Use this as the pick-list instead of defaulting to Carrie → Linda — pick whichever ones actually matter for NCF right now.

### Content
| Role | Status |
|---|---|
| Callie — Core Content | Largely covered already by Nia/`ncf-email-builder` |
| Riley — Repurposing | Not built |
| **Linda — Landing Pages** | Stub exists |
| Glenda — Guest Research | Not built |
| Wynn — Podcast Scripts | Not built |
| Polly — Podcast Producer | Not built |
| Crystal — Carousels | Not built |
| Quinn — Curriculum Designer | Not built |

### Growth
| Role | Status |
|---|---|
| **Meg — CMO** | ✅ Built and trained |
| Izzy — Marketing Insights | Not built |
| Suzie — Social Media | Not built |
| Lena — LinkedIn | Not built |
| Manny — ManyChat | Not built |
| **Carrie — Content-to-Conversion** | Stub exists |
| Lakeisha — Launch Emails | Not built |

### Ops
| Role | Status |
|---|---|
| Cassie — Customer Service | Not built |
| Dorothy — Delegation | Not built |
| Rachel — Process Requests | Not built |
| CEO Time — Weekly Planning | Not built |
| **Nia — Newsletter** | Built, unnamed (`ncf-email-builder`) — proposed match above |
| Sloane — SOP Creation | Not built |
| Hope — Interview Questions | Not built |
| **Bridgette — Morning Brief** | Built, generic (`morning`) — proposed match above |
| Willa — Daily Wellness | Not built |

### Strategy
| Role | Status |
|---|---|
| Marlow — Modern CFO | Not built |
| Allie — Market & Competitive | Not built |
| Betty — Business Plan Builder | Not built |

---

## Decisions needed from Jess

1. **Confirm or reject the Nia / Bridgette naming.** If confirmed, next step is giving each the same real business-context interview Meg got (per `docs/training-doc-template.md`), not just a rename.
2. **Pick what gets built next**, instead of the old default order (Carrie, then Linda). Anything from the candidate roster above is fair game — say which ones you actually want on the team.
