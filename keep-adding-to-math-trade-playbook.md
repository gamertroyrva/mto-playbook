# Math Trade Organizer Playbook — Operating Guide
*Restart document for building the Playbook phase by phase across multiple Claude Chat sessions.*
*Drag this file in at the start of any new session to resume without re-deriving the method.*

---

## What This Guide Is For

The Math Trade Organizer Playbook is a structured reference document for running a local no-ship math trade from A to Z — written for an audience that ranges from experienced OLWLG participants who've never organized, to someone who's been toying with the idea, to Troy himself as a repeatable reference.

The Playbook is being built one phase at a time, in conversation with Claude Chat, then rendered as HTML. This guide tells a fresh Claude session everything it needs to know to pick up where the last session left off.

---

## Terminology

Three levels, used precisely:

- **Phase** — the largest grouping (Phase 1 through Phase 6 of the Playbook).
- **Task** — the row-level unit within a phase (e.g., "Venue Lock-In," "GeekList Creation & Launch").
- **Steps** — the discrete actionable items inside a Task's Steps column numbered list.

---

## The Artifact Being Built

Each phase of the Playbook is rendered as a self-contained HTML table with the following columns:

| Column | Description |
|--------|-------------|
| **Task** | Short task name. Bold, colored for scannability. |
| **Task Description** | 1-3 sentences. What this task is and why it matters at a high level. |
| **Task Steps** | Numbered list. The actual how-to, step by step. Enough detail that someone doing it for the first time could follow along. |
| **Why Do This** | Prose paragraphs (or a short bulleted list where appropriate). The reasoning, lessons learned, and context behind the task. Reined in — not exhaustive. The goal is useful, not comprehensive. |

**Phase** is rendered as a section header above the table, not a column inside it.

### HTML Rendering Conventions
- Phase header: dark accent bar (rust/brown) with white text, spanning the full table width
- Task column: accent color text, bold
- Why Do This column: slightly off-white background to visually distinguish it from the Steps column
- Steps: `<ol>` numbered list inside the cell
- Why bulleted lists (when used): `<ul>` inside the cell, one item per line
- No "Why" label inside the Why cell — the column header already says it
- Scope note at the bottom of each phase (italicized, left-bordered callout) acknowledging that this is the "Troy edition" and that a leaner version without Discord dependencies would exist for a general audience
- Mobile-responsive: columns stack on narrow screens with data-label attributes

---

## The Method: How Each Phase Gets Built

Every phase follows the same process:

### Step 1 — Bone Structure Review
Confirm the sub-tasks for the phase from the bone structure below. Ask Troy if anything is missing or needs splitting before investing in elaboration.

### Step 2 — Narrative Elaboration (Conversation)
Talk through the phase task by task. Troy describes what actually happens — the mechanics, the tools, the timing, the lessons learned, the judgment calls. Claude reflects back, asks clarifying questions, and surfaces hidden tasks. This is the raw material pass. Don't rush it.

### Step 3 — Table Draft (Markdown first)
Once the phase is fully talked through, draft it as a markdown table or narrative first to validate the content — then convert to HTML. Don't jump to HTML before the content is right.

### Step 4 — Tidbit Collection and Revision
Present the HTML (or markdown draft). Troy reads it once (or twice) and collects feedback as "tidbits" — one at a time, in whatever order they surface. **Claude queues each tidbit as it's given — restating it back in a running list — and does NOT regenerate anything until Troy explicitly says to.** Apply all tidbits in one regeneration pass.

### Step 5 — Why Do This Refinement
After the main table is stable, go through the Why Do This column one task at a time. Troy decides what to keep, what to trim, and what to release entirely. The goal: Why content that's balanced in height with the Steps content, lean enough to read, rich enough to matter. Anything culled doesn't need a home elsewhere — if it's in Troy's head, that's enough.

### Step 6 — Sign Off and Save
Troy downloads the HTML file. It lives in the vault alongside the other phase files. The next session picks up with the next phase.

---

## Voice and Audience Notes

- Written for an OLWLG-experienced reader who may never have organized — not a beginner, but not an insider either.
- The "Troy edition" framing acknowledges that Troy's approach includes a significant discretionary layer (year-round Discord community, personal outreach habits, three-identity participant tracking) that most math trades don't have. The Playbook documents this layer fully. A leaner version for a general audience is a future extraction exercise, not a parallel document.
- Troy's personal entertainment value in any task (e.g., enjoying browsing new GeekList additions) does not belong in the Why column. The Why is for the reader, not Troy's internal experience.
- Avoid meta-commentary about the Playbook itself inside the Why column.
- De-personalize any lessons learned that reference specific participants negatively.

---

## The Full Bone Structure (Six Phases, Two Levels)

*Note: the lettered sub-tasks below are starting hypotheses, not commitments. Phase 1's bone structure (organized by audience: returners, newbies, etc.) was discarded entirely during elaboration in favor of a different organizing principle (venue, schedule, announcement, open-ended outreach). Don't be precious about the existing letters — Step 1 (Bone Structure Review) may reshape a phase from scratch, and that's expected, not a failure.*

### Phase 1 — Awareness & Recruiting ✅ COMPLETE
Completed tasks (in order as rendered in the HTML):
1. Venue Lock-In
2. Build the Trade Schedule
3. Facebook Announcement Post
4. Sing from the Mountain Tops

*Note: the original lettered bone structure (Returner outreach / Newbie recruiting / Community buzz / Building the participant pool) was discarded entirely. The actual organizing principle that emerged: a hard prerequisite (venue), a planning task (schedule) that feeds the rest, one recipe-card action (Facebook post), and one open-ended improvisational task (Sing from the Mountain Tops). A cross-cutting thread — tracking who recruits newbies, for a Phase 6 swap-day superlative — was identified but intentionally not resolved here; it doesn't fit cleanly into any single phase and will surface again (referenced again around Phase 4).*

### Phase 2 — Offer Up Games ✅ COMPLETE
Completed tasks (in order as rendered in the HTML):
1. GeekList Creation & Launch
2. Discord Channel Setup
3. Advertising & Awareness
4. Monitoring GeekList Additions
5. Tracking & Encouraging Participation

*Note: The bone structure originally listed 4 sub-tasks for this phase. Through elaboration, the actual task list grew to 5 — Discord Channel Setup was split out from GeekList Creation & Launch, and Advertising & Awareness, Monitoring, and Encouraging Participation were refined and resequenced. Expect similar evolution in other phases.*

### Phase 3 — Wants Phase
a. Monitoring submission progress
b. Practice runs at submission percentage intervals
c. Genie pipeline execution on each practice run
d. Anomaly review
e. Targeted outreach to nudge submission rates
f. Watching loops form / reading the trade

### Phase 4 — Final Run Phase
a. Submission deadline management
b. Final algorithm execution
c. Genie pipeline execution
d. Anomaly review and results validation
e. Results packaging / preparation for announcement

### Phase 5 — Announce Results Phase
a. Publishing results
b. Communicating to participants
c. Handling questions and edge cases

### Phase 6 — Swap Phase *(The Glorious Payoff, the Whole Point, the Day the Nitrogen Gets Harvested)*
a. Pre-swap logistics and reminders
b. Day-of facilitation
c. Handling no-shows and exceptions
d. Post-swap wrap-up and community celebration

---

## What "Complete" Looks Like for Each Phase

- HTML file downloaded and saved to vault
- All tidbits applied and a final revision rendered
- Why Do This column trimmed and balanced
- Scope note present at the bottom
- No open feedback items

---

## Reference: Phase 2 HTML File

The completed Phase 2 HTML file (`playbook-table-offer-up-games.html`) serves as the style and content reference for all subsequent phases. When in doubt about formatting, column balance, or level of detail — look at Phase 2.

---

## Key Decisions Already Made (Don't Re-Derive These)

- **Audience:** OLWLG-experienced reader, organizer experience not assumed
- **Scope:** Local no-ship trades only. No attempt to cover shipping trades or note divergences.
- **Format:** HTML table per phase, self-contained files, eventually potentially assembled into one multi-phase page
- **Column definitions:** Task / Task Description / Task Steps / Why Do This (see above)
- **Phase as section header:** not a column
- **Why Do This:** prose paragraphs, bulleted list only where content naturally calls for it, no "Why" label inside the cell
- **Trimming philosophy:** anything culled from the Why column doesn't need to live anywhere else. Trust Troy's memory.
- **Troy edition acknowledgment:** scope note at the bottom of every phase. As of Phase 1, scope notes should go beyond acknowledging discretionary layers (e.g., Discord) and explicitly call out which tasks form a "minimal viable" version of the phase vs. which are discretionary effort layered on top. See Phase 1's scope note as the new reference.
- **Phase 2 vs. Phase 1 as references:** Phase 2 remains the formatting/rendering reference. Phase 1 is the reference for scope note depth and for how much a phase's bone structure can legitimately change during elaboration.
- **Leaner general-audience version:** future extraction exercise, not a parallel build

---

*Created: June 14, 2026*
*Last updated: June 14, 2026 (Phase 1 complete; terminology, bone structure flexibility, tidbit queuing, and scope note depth additions)*
