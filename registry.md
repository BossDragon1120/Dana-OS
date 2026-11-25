# Registry

Every skill and agent in the OS, wherever it lives. **Check here before building anything.** Update this file in the same change whenever something is built, renamed or retired.

**Status:** 💡 idea · 🛠️ planned or building · ✅ built · 🔁 running on a schedule
**Installed:** where Claude can use it today. The goal is for every row to say *plugin* (installed from the repo).

## Skills

| Skill | Repo | Track | What it does | Status | Installed |
|---|---|---|---|---|---|
| [`deal-decoded-script`](https://github.com/BossDragon1120/Little-Panda-Education/tree/main/skills/deal-decoded-script) | Little Panda | M&A | 75–90 s talk track, deal card, caption, sources for a $1B+ deal | ✅ | ⚠️ not installed |
| [`deal-decoded-video`](https://github.com/BossDragon1120/Little-Panda-Education/tree/main/skills/deal-decoded-video) | Little Panda | M&A | Silent 1080×1920 MP4 in navy and lime, timed to the script | ✅ | ⚠️ uploaded copy (may drift) |
| `ai-vocab-script` | Little Panda | AI | One AI term per video, plain language | 🛠️ | — |
| `ai-vocab-slides` | Little Panda | AI | AI Vocab slides, Golden Gate Bridge photography | 🛠️ | — |
| `course-explainer-script` | Little Panda | All | Key ideas from a course module | 🛠️ | — |
| `course-explainer-slides` | Little Panda | All | Course Explainer slides | 🛠️ | — |
| `tiktok-format` | Little Panda | All | Shared 9:16 layout rules for every slide builder: clear of the search bar at top and caption area at bottom, no wasted space in the middle, no panda | 🛠️ | — |
| [`book-whisper`](https://github.com/BossDragon1120/Book-Whispers/tree/main/skills/book-whisper) | Book & Podcast Whispers | Business | Raw book dictation → reflection, threads, reading log | ✅ | ⚠️ not installed |
| [`podcast-whisper`](https://github.com/BossDragon1120/Book-Whispers/tree/main/skills/podcast-whisper) | Book & Podcast Whispers | M&A | Raw episode dictation → episode note, agent ideas, listening log | ✅ | ⚠️ not installed |
| `ma-science` | **Account only** → move to Book & Podcast Whispers | M&A | Answers M&A questions from M&A Science transcripts, with episode links | ✅ | ⚠️ uploaded copy, no repo |
| [`topic-deep-dive-brief`](https://github.com/BossDragon1120/Upskilling-and-Subject-Matter-Expertise/tree/main/skills/topic-deep-dive-brief) | Upskilling | Tech topics | Researched 5–10 page brief on a tech or business topic | ✅ | ⚠️ uploaded copy (delete once the plugin is installed) |

## Agents

| Agent | Repo | Track | What it does | Status | Runs as |
|---|---|---|---|---|---|
| [`deal-decoded-scout`](https://github.com/BossDragon1120/Little-Panda-Education/blob/main/agents/deal-decoded-scout.md) | Little Panda | M&A | Finds new $1B+ deals each weekday, scripts and renders up to 2 | 🔁 | [routine](routines/deal-decoded-scout.md) |
| [`learning-notes-intake`](https://github.com/BossDragon1120/Little-Panda-Education/blob/main/agents/learning-notes-intake.md) | Little Panda | All | Picks teachable ideas from notes and sends them to script skills | ✅ (waiting on notes) | [routine](routines/learning-notes-intake.md) |
| `video-assembler` | Little Panda | All | Slides + my voiceover → finished MP4 | 🛠️ | — |
| `tiktok-poster` | Little Panda | All | Posts approved videos | 💡 | — |
| `engagement-tracker` | Little Panda | All | Learns what works and feeds it back to inputs | 💡 | — |
| IMO program-management pack | _home TBD_ | M&A | Status update, meeting recap, RAID log, kickoff plan, stakeholder comms, exec brief, change plan, integration playbook, retro | 💡 | — |

## Ideas pipeline

New agent ideas start in [`agent-ideas.md`](https://github.com/BossDragon1120/Book-Whispers/blob/main/agent-ideas.md) in Book & Podcast Whispers, linked to the book or episode they came from. When one moves to 🛠️, add a row above with the repo it will live in.

Also on the list:
- Example agents and subagents for different use cases (after the agentic AI course)
- RAG course summary videos
- Documentation meetup presentation summaries
- Silicon deep dive (Tech topics)
