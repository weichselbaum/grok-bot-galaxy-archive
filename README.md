# Grok Bot Galaxy Archive

Clean dump of the **SpaceXAI Grok Bot Galaxy** livestreams (15–17 Sep 2026): full Whisper transcripts + structured bots / approaches / code mined from them.

For people who missed the event and want to throw this at their Grok Bot to see what applies to **their** fleet.

**Not included:** multi‑GB VODs (replays stay on X).

## Apply prompt (paste this)

```text
Use https://github.com/weichselbaum/grok-bot-galaxy-archive as the source pack.

1. Read FEEDME.md, then load metadata/approaches.json, metadata/bots.json, and metadata/code-snippets.json.
2. Use transcripts/day*/transcript.json only when you need quotes or timestamps (ground truth if metadata conflicts). Prefer bots tagged for the studio fleet over one-off workshop demos when ranking what to copy.
3. Inventory MY current bots, skills, routines, and connected tools.
4. Compare that inventory to the Galaxy approaches and bot roles.
5. Propose a ranked adoption plan for MY fleet: what to copy, adapt, or skip — with why, prerequisites, and rough effort.
6. Fleet design rules (from Galaxy SOPs):
   - If I have no fleet owner yet, recommend ONE meta/CoS/designer bot to own the plan — not a full specialist army on day one.
   - If I already have a CoS / fleet owner, use that bot for Apply; do not spawn a second CoS.
   - One CoS max. CoS plans and gates; coding goes to a dedicated shipper (or cloud agent), not the CoS.
   - Stage-gate specialists — only propose bots for stages that currently hurt.
   - Every proposed bot needs one job, one voice, and explicit anti-jobs (what it must never do).
7. Do not invent bots or playbooks that aren’t in this pack. Do not create bots, change my setup, send messages, or touch outbound channels until I approve the plan.
```

Short version: point your bot at the repo and paste the block above.

## What’s in here

| Path | What |
|------|------|
| [`FEEDME.md`](FEEDME.md) | Load order + SOPs |
| [`metadata/approaches.json`](metadata/approaches.json) | 18 playbooks |
| [`metadata/bots.json`](metadata/bots.json) | 32 bots / roles |
| [`metadata/code-snippets.json`](metadata/code-snippets.json) | Stack / repos / launch notes |
| [`transcripts/`](transcripts/) | Day 1–3 `summary.md` + `transcript.json` |
| [`LICENSE`](LICENSE) / [`NOTICE.md`](NOTICE.md) | MIT on this compilation; stream rights stay with owners |

## Streams

| Day | Replay |
|-----|--------|
| 1 | https://x.com/i/broadcasts/1AxRnZbVpjaxl |
| 2 | https://x.com/i/broadcasts/1PKqrNyvmYwGb |
| 3 | https://x.com/i/broadcasts/1YGNrbXEeazGw |

~25h audio → Whisper large‑v3. Metadata mined from those transcripts.
