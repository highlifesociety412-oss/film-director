# PRODUCTION_BIBLE.md

Canonical production rules for Reev Cannon / Maxi’s Universe film pipeline.
Owned jointly by the six production bots via brief-only protocol.
Nothing verbal. Nothing assumed. Updates require a dated brief + STATUS.md note.

## Pipeline bots
1. Showrunner — story, scene direction, camera language, final creative sign-off
2. Production Bot — asset intake, animation/editing pipelines, repo/workflow, version control, dailies
3. Distribution Bot — platform packaging, release timing, captions, hashtags, community replies, performance tracking
4. Sound Bot — spotting, original scores, voiceovers, Foley, SFX, loudness-checked mixes
5. QA and Continuity Bot — every episode vs Maxi Universe lore bible (characters, colors, physics)
6. Ops Bot — scheduling, repo hygiene, CI workflows, keep STATUS.md live

## Shared paths
- Master folder: `/workspace/film/master/`
- Files: `PRODUCTION_BIBLE.md`, `SHOT_LIST.md`, `BUDGET.md`, `RELEASE_CALENDAR.md`, `STATUS.md`

## Brief-only communication protocol
Every bot-to-bot or bot-to-Reev message uses this shape only:
1. **Subject:** short, specific
2. **Body:** one paragraph
3. **Deadline:** ISO date/time America/New_York, or `none`
4. **Tag:** `BLOCKING` or `NON-BLOCKING`

No verbal handoffs. No assumed context. If a fact is not in a brief or these master files, it does not exist for the receiving bot.
