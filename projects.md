# Claude Projects

Each Project is an "app" on the OS: one per domain, with instructions that point Claude at the right repo and conventions. Keep Project instructions short. The detail lives in the repos.

**What goes where:** reusable skills, templates and formats go in a repo. A Project holds the context and work in progress for its domain: decisions, drafts and status. Private Projects aren't listed here.

## Layout

| Project | Was | Tracks | Repos it uses | Holds |
|---|---|---|---|---|
| **Little Panda Studio** | _(unnamed)_ | All | Little Panda Education | Series decisions, video drafts: Deal Decoded, AI Vocab, Course Explainers |
| **Learning Lab** | _(new)_ | AI, Tech topics, Business | Upskilling, Book & Podcast Whispers | Courses, deep dives (e.g. silicon), books, M&A Science |
| **WearAbout** | Fit check App | — | WearAbout-iPhoneApp | Product decisions, beta testing, App Store |
| **The Agentic IMO** | The Agentic IMO | M&A | _TBD_ | Agentic IMO site, integration philosophy, IMO agent pack |

## To do in Claude
- [ ] Name the unnamed Project **Little Panda Studio**
- [ ] Rename **Fit check App** to **WearAbout**
- [ ] Create **Learning Lab**
- [ ] Paste the instruction template below into each one
- [ ] Decide where the IMO agent pack lives

## Instruction template

```
This Project is the [NAME] app in Dana-OS (github.com/BossDragon1120/Dana-OS).
Tracks: [TRACKS]. Repos: [REPOS].

Before starting:
1. Follow Dana-OS/CLAUDE.md for principles, where things go, naming and note headers.
2. Check Dana-OS/registry.md for an existing skill or agent before building one.
3. Follow the target repo's README and templates.

Don't publish or post anything without my review.
```
