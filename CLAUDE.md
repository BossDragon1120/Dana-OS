# CLAUDE.md: how to work inside Dana-OS

Read this before doing anything for me in a Claude session that touches my repos, skills, learning or content.

## Operating principles
- **Never make things up.** A wrong guess is worse than not knowing. If you aren't sure, say so.
- **Build modular, reusable assets, not one-off documents.** If something will be needed again, make it a skill, template or note in the right repo.
- **Save what matters where it persists.** Anything worth keeping goes into a repo or a Project. Don't leave it only in a chat.
- **Human in the loop.** Agents draft; I review, record and publish.

## Start here
1. **Check [`registry.md`](registry.md) first.** If a skill or agent already does the job, use it. Don't rebuild it.
2. **Find the right repo** with the map in [`README.md`](README.md). Each kind of work has one home.
3. **Follow that repo's own README and templates.** Its conventions win over anything general.

## Where things go

| If it's… | It goes in… | Path |
|---|---|---|
| Course module notes | Upskilling | `courses/<course>/NN-<module>.md` |
| A self-directed deep dive | Upskilling | `topics/<ai\|tech\|business>/<slug>.md` |
| A term to define | Upskilling | `glossary/<term>.md` |
| A book reflection | Book & Podcast Whispers | `books/YYYY-MM-<book-slug>/` |
| A podcast episode note | Book & Podcast Whispers | `podcasts/<show>/YYYY-MM-DD-<episode>.md` |
| An idea for an agent | Book & Podcast Whispers | a row in `agent-ideas.md` |
| A TikTok skill or agent | Little Panda Education | `skills/<name>/` or `agents/<name>.md` |
| A new skill or agent that fits nowhere | Dana-OS | `skills/` or `agents/`, then add it to the registry |
| A recurring task | Dana-OS | `routines/<name>.md` |

## Naming
- Files and folders: `kebab-case`. Dated files start with `YYYY-MM-DD` (or `YYYY-MM` for books).
- Skills: `<series-or-domain>-<job>` (e.g. `deal-decoded-script`, `podcast-whisper`).
- Agents: named for the role (e.g. `deal-decoded-scout`, `learning-notes-intake`).
- M&A and integration skills and agents keep standard M&A terms in their name or description (status update, RAID log, exec brief, dependency mapper, stakeholder comms), even if they also get a character name.
- Repos: `Title-Case-With-Hyphens`.

## Note headers
Every note in Upskilling and Book & Podcast Whispers starts with:

```yaml
type: course-module | topic | term | reflection | episode
subject: ai | tech | business | m&a
status: draft | done
video: none | idea | scripted | posted
```

Each repo's `templates/` folder has the full header; use it as written.

Agents rely on `status` and `video`. Never change a note's content to make it fit a video; only update the `video` field.

## Skills and agents
- **Source of truth is GitHub.** Edit the repo, never an uploaded copy in the Claude account.
- Start from the templates in `Little-Panda-Education/templates/`.
- Every skill and agent needs `name` and `description` frontmatter; run the repo's `scripts/validate.py` before committing.
- When you build, rename or retire one, **update [`registry.md`](registry.md) in the same change.**

## Routines
- Each routine in [`routines/`](routines/) is the plain-language definition of a scheduled task. The scheduled task's prompt should match it.
- Change the routine file first, then the scheduled task.

## Guardrails
- Don't publish, post or message anyone without my review.
- Primary sources only; never invent or estimate a figure.
- Raw dictations stay raw. Only the reflection gets polished.
- Most of these repos are **public**. Keep anything private, about my employer's internal work, or about other people out of them.
- Commit messages: short imperative summary, then what changed and why.
