# Routine: daily-podcast

**Schedule:** daily, morning (Pacific)
**Track:** M&A
**Status:** 💡 proposed

One M&A Science episode a day keeps the M&A track sharp and feeds the agent-ideas backlog.

## Inputs
- `listening-log.md` in Book & Podcast Whispers (what I've already heard)
- The M&A Science episode list on mascience.com

## Outputs
- One message: today's suggested episode, link, a two-line "why this one", and a reminder to dictate a 2-minute reflection afterwards for the `podcast-whisper` skill

## Prompt
```
Read listening-log.md in github.com/BossDragon1120/Book-and-Podcast-Whispers. Pick one
M&A Science episode I haven't logged, favoring integration, IMO and AI-in-M&A topics.
Send me one short message: episode title, link, two lines on why it's worth my time,
and a reminder to dictate a 2-minute reflection afterwards so podcast-whisper can file it.
```

## Guardrails
Don't write to the repo. This routine only suggests; filing happens when I dictate.
