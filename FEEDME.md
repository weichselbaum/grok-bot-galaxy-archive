# FEEDME

Load in this order:

1. **`metadata/approaches.json`** — how they ran the company (primary)
2. **`metadata/bots.json`** — named bots (prefer high confidence; prefer studio fleet over workshop demos when adopting)
3. **`metadata/code-snippets.json`** — stack / repos / launch notes
4. **`transcripts/INDEX.md`** — day map
5. **`transcripts/dayN/transcript.json`** — ground truth with timestamps

`summary.md` files are optional orientation only.

## Apply SOPs (anti–cargo-cult)

- **Inventory → match → ranked plan → stop for approval → create only what was approved.**
- **One CoS / fleet designer max.** Greenfield: propose that role first. Already have one: reuse it. Never two.
- **CoS ≠ coder.** Plan and gates stay with CoS; implementation to a shipper / cloud agent.
- **Stage-gate specialists.** Don’t spawn research / QA / marketing / eng workers until the current stage hurts without them.
- **One job · one voice · explicit anti-jobs** on every bot.
- **Source of truth outside chat** (Notion or equivalent). Chat is disposable.
- **Never send** email / Slack / posts as the user without an explicit named ask.
- **Verify before claiming done** (especially coding bots).
- If metadata and a transcript disagree, **trust the transcript**.

That’s the whole dump.
