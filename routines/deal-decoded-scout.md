# Routine: deal-decoded-scout

**Schedule:** weekdays, morning (Pacific)
**Track:** M&A
**Status:** 🔁 running
**Runs:** the [`deal-decoded-scout`](https://github.com/BossDragon1120/Little-Panda-Education/blob/main/agents/deal-decoded-scout.md) agent

## Inputs
- M&A announcements since the previous weekday (8-Ks, press releases)
- Existing Deal Decoded scripts, so it skips deals already covered

## Outputs
- Up to 2 scripts: `ma-<buyer>-<target>-talk-track.md`
- A silent MP4 for each: `deal-decoded-<buyer>-<target>.mp4`
- One summary message to me

## Prompt
```
Run the deal-decoded-scout agent from github.com/BossDragon1120/Little-Panda-Education
(agents/deal-decoded-scout.md). Follow it exactly, using the deal-decoded-script and
deal-decoded-video skills from the same repo. Send me one summary message when done.
```

## Guardrails
Primary sources only. Never post or publish. Message only me.
