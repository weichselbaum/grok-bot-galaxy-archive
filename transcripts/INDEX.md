# Transcript index — Grok Bot Galaxy Livestream

Full Whisper (`faster-whisper` large-v3) transcripts for the three official `@bot` X Broadcasts.
Durations from transcript JSON `meta.audio_duration_s`. Times below are **stream-relative** (00:00 = broadcast start), not wall-clock PT.

| Day | Date | Title | Duration | Words (approx) | Files |
|-----|------|-------|----------|----------------|-------|
| 1 | 2026-09-15 | Day 1: Grok Bot Galaxy Livestream | ~8.75 h (31513 s) | ~93.5k | `day1/transcript.{txt,srt,json}` |
| 2 | 2026-09-16 | Grok Bot builds a Game Studio LIVE | ~8.39 h (30199 s) | ~88.3k | `day2/transcript.{txt,srt,json}` |
| 3 | 2026-09-17 | Building a company in 3 days - launching today! | ~7.97 h (28702 s) | ~84.9k | `day3/transcript.{txt,srt,json}` |

**Prefer** `transcript.json` (segment timestamps) for citation; use `transcript.txt` for bulk search; `transcript.srt` for players.

Condensed narratives (optional): `dayN/summary.md`. Structured extracts: `../metadata/{bots,code-snippets,approaches}.json`.

---

## Day 1 — Ideate & stand up “Ship by Thursday” (pop-up OS)

**Broadcast:** https://x.com/i/broadcasts/1AxRnZbVpjaxl  
**Build spine hosts:** Matt Palmer (@mattyp), Lauren Tan (@poteto), Roshan Sadanani (@roshan_s)

### Session blocks (approx stream time; align with x.ai/galaxy PT schedule)

| Stream-ish window | Session | Speakers / notes |
|-------------------|---------|------------------|
| 00:00–~00:35 | Open + company zero | Blank GitHub org **Ship by Thursday**, Slack as control plane, P-Stack pitch |
| ~00:35–~01:30 | **Grok Bot 101** | Roman Ugarte — Data Dan / Slide Sonia / Email Ethan; teach-a-task; auto-review; memory on S3 |
| ~01:30–~03:00 | Build: idea mining + Eggbot/Steve | X MCP research; install **Dr. Eggbot**; rename default → **Steve**; **Grokpot** prototyper; pop-up OS thesis |
| ~02:50 | Incident | Steve opens ~**2000-line PR** → rule **ship to main, no PRs** |
| ~03:00–~04:00 | Guest / validation | Distribution advice; sell-to-three framing |
| ~04:00–~05:30? | **Engineering** | Lingxi Li — agent factories, PR review Slack automations, verification skills |
| Mid–late | Ops bots | **Tater**, **Hashbrown**, Knowledge Base Manager, Pixel/design talk, Vercel + shipbythurs.day |
| ~05:00–~06:30 | **Product Managers** | Kevin Niparko — Cora, Emily, Ashley, PM Pete, Pixel, Ray |
| ~07:20–~08:30 | **Founders** | Shub Gaur + guest Jenny — CloseBot, ProdBot, StockBot, YapBot; Master Chief anecdote |

### Themes
- Humans + bots as employees; Slack/Notion/GitHub blank slate  
- Marketplace templates vs custom specialists  
- Pop-up restaurant OS lander (HTML) before day-2 pivot  
- P-Stack / potato culture seeds  

---

## Day 2 — Pivot to game studio (codename Cupcake)

**Broadcast:** https://x.com/i/broadcasts/1PKqrNyvmYwGb  

### Session blocks

| Stream-ish window | Session | Speakers / notes |
|-------------------|---------|------------------|
| 00:00–~00:35 | Pivot announcement | “Agents told us to pivot” → **game studio**; arena / bot battler ideas |
| ~00:35–~01:30 | **Sales Engineering** | Amrita Venkatraman — Sherlock, Serena, Mimi |
| Morning–afternoon | Build | Poteto mode demos; **CupcakeEng**; ImageGen; swarm prototypes; Comment Sicko lore; food-named bots (Tater Mash, Hashbrown, Bake) |
| Mid | **Sales** | SpaceXAI Sales Team patterns |
| Mid–late | **SDRs** | Simon Lackowski |
| Late | **Customer Support** | David Gan — Stripe refund SOP demo (Carter vs Damon) |
| Late build | Infra | Clerk, Vercel Functions exploration, Slack Ping bot, Notion SoT mandate, Audio Engineer spun up |

### Themes
- Poteto mode = router skill; Full autopilot playbook introduced  
- Swarm of multi-model cloud agents for prototypes  
- Cupcake working title; art/audio experiments  
- Auth (Clerk) + serverless direction  

---

## Day 3 — Launch Thursday Arena + monetize

**Broadcast:** https://x.com/i/broadcasts/1YGNrbXEeazGw  

### Session blocks

| Stream-ish window | Session | Speakers / notes |
|-------------------|---------|------------------|
| 00:00–~00:30 | Overnight factory recap | Full autopilot → 100–170+ PRs; **Play** QA bot on green CI |
| ~00:30–~01:30 | **Marketing Ops** | Matthew Silberman, Teresa Hsu; Starbase bot-share challenge |
| ~01:25–~02:00 | **Launch** | Flip to prod; name drop **ThursdayArena.com** + @ThursdayArena; stack Go/Vercel/PlanetScale/Clerk |
| Afternoon | Feedback factory | Steve Slack triage; Crumble → Tater → Hashbrown; Elo/matchmaking bugs |
| Mid | **Post-Sales** | Blake Schuller |
| ~05:30 | **Stripe guest** | Dan Hill (Link) — one-time agent cards + spend approval |
| Mid–late | **Marketing** | Josh Kim — outbound, conversion |
| Late | Monetization | **Pay for Cloud** auction PR mashed live; auction buggy |
| Wrap | Metrics + outage | ~6k public matches, ~2k X logins goal, ~17k–30k page views; **bad SQL** from factory downs prod briefly |
| Close | Mash lore | Merges renamed **mash** via Eggbot potato Notion task |

### Themes
- Software factory as product: triage → fix → playtest → mash  
- Real users + real outages  
- Thinnest payments path (Link / ads auction)  
- Purpose framed as teaching Grok Bot use, not “just a game”  

---

## Cross-day continuity

| Thread | Day1 | Day2 | Day3 |
|--------|------|------|------|
| Company | Ship by Thursday / pop-up OS | Game studio / Cupcake | Thursday Arena live |
| CoS | Steve created | Steve + CupcakeEng | Steve runs feedback factory; renamed Stephen joke |
| Eng factory | Ship-to-main rule; Tater/Hashbrown | Potato / autopilot / swarm | Play QA; 100s of PRs; mash |
| Meta-bot | Dr. Eggbot installed | Creates CupcakeEng; Comment Sicko | Potato naming → mash language |
| Stack | GitHub, Slack, Notion, Vercel, Clerk talk | Clerk, Vercel Functions | Go + Vercel + PlanetScale + Clerk + Stripe Link |

