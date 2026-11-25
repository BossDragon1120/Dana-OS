# 🐉 Dana-OS

**The operating system behind my work with Claude.** This repo is the kernel: it maps every other repo, sets the conventions Claude follows, keeps a registry of every skill and agent I've built, and defines the routines that run without me asking.

Claude is the runtime. GitHub is the source of truth. If something isn't written down here or in one of the repos below, it doesn't exist yet.

## The layers

| Layer | Where it lives | What it holds |
|---|---|---|
| 🧠 **Kernel** | This repo | Map, conventions ([`CLAUDE.md`](CLAUDE.md)), [`registry.md`](registry.md), [`routines/`](routines/) |
| 📦 **Packages** | The domain repos below | Skills, agents, templates, notes, logs |
| 🪪 **Identity** | Claude memory (profile + preferences) | Who I am and how I like Claude to work |
| 🗂️ **Apps** | Claude Projects, one per domain | Instructions that point at the right repo (see [`projects.md`](projects.md)) |
| 🔌 **Drivers** | Connectors | Google Calendar, GitHub; next: meetups, email |
| ⏱️ **Daemons** | Scheduled tasks | Defined in [`routines/`](routines/) |

## Tracks

Everything I learn and make is filed under one of five tracks:

| Track | Covers |
|---|---|
| **AI** | Agentic AI, RAG, models, AI adoption and change management |
| **M&A** | Deals, integration, IMO practice, M&A Science |
| **Tech companies** | What specific companies are doing: earnings, strategy, launches |
| **Tech topics** | Deep dives on a technology (e.g. silicon) |
| **Business** | Strategy, leadership, books, general business |

## Repo map

| Repo | Role in the OS | Tracks | Visibility |
|---|---|---|---|
| [Dana-OS](https://github.com/BossDragon1120/Dana-OS) | Kernel: map, conventions, registry, routines | All | Public |
| [Upskilling-and-Subject-Matter-Expertise](https://github.com/BossDragon1120/Upskilling-and-Subject-Matter-Expertise) | **Learn**: course notes, deep dives, glossary | AI, Tech topics, Business | Public |
| [Book-and-Podcast-Whispers](https://github.com/BossDragon1120/Book-Whispers) ¹ | **Reflect**: monthly book reflections, daily M&A Science notes, idea threads, agent-ideas backlog | M&A, Business | Public |
| [Little-Panda-Education](https://github.com/BossDragon1120/Little-Panda-Education) | **Teach**: TikTok pipeline (scouts, scripts, slides, video) | All | Public |
| [WearAbout-iPhoneApp](https://github.com/BossDragon1120/WearAbout-iPhoneApp) | **Build**: product work | — | Public |

¹ Rename from `Book-Whispers` to `Book-and-Podcast-Whispers` is pending. Links in other repos already use the new name.

**To archive** (dormant or duplicate): `ClosetApp` (duplicate of `Closet-App`), `clue`, `curio`, `AI-Native_Integration`. Decide on `Closet-App` separately.

## How it flows

```
   LEARN                      REFLECT                        TEACH
 ┌────────────────────┐    ┌────────────────────────┐    ┌──────────────────────────┐
 │ Upskilling repo    │    │ Book & Podcast Whispers│    │ Little Panda Education   │
 │ courses · topics · │    │ books · podcasts ·     │    │ scouts → scripts →       │
 │ glossary           │    │ threads · agent ideas  │    │ slides → video → post    │
 └─────────┬──────────┘    └───────────┬────────────┘    └────────────▲─────────────┘
           │   "Teachable moments"     │                              │
           └───────────────┬───────────┘                              │
                           └──── learning-notes-intake (agent) ───────┘
                                        
 agent-ideas.md ──▶ registry.md (💡 → 🛠️ → ✅) ──▶ new skills/agents in a package repo
```

1. **Learn.** Every course module, deep dive and term gets a note with a standard header.
2. **Reflect.** Books and podcasts get dictated reflections; recurring ideas become threads; practitioner pain points become agent ideas.
3. **Teach.** Notes marked `status: done` become TikToks.
4. **Build.** Agent ideas get promoted in the registry and built as skills or agents in the right repo.

## Migration status

Turning my Claude account from an assistant into this OS:

- [x] Kernel repo created
- [ ] Rename `Book-Whispers` → `Book-and-Podcast-Whispers`
- [ ] Add a plugin manifest to Book-and-Podcast-Whispers
- [x] Move `topic-deep-dive-brief` into Upskilling (with plugin manifest)
- [ ] Move `ma-science` into Book-and-Podcast-Whispers (see [`registry.md`](registry.md))
- [ ] Keep account skill copies in sync with GitHub (update via a skill card, or install as a plugin in Claude Code)
- [x] Review Claude memory: consolidate duplicates, add an OS preference pointing here
- [ ] Rename Claude Projects per [`projects.md`](projects.md) and create Learning Lab
- [ ] Turn on routines in [`routines/`](routines/)
- [ ] Archive dormant repos

## Principles

- **Never make things up.** A wrong guess is worse than not knowing.
- **Modular, reusable assets.** Build once, reuse everywhere; no one-off documents.
- **Save what matters where it persists.** A repo or a Project, never only a chat.
- **One source of truth.** Skills are edited in GitHub; the copies in my Claude account are updated from there.
- **Human in the loop.** Agents draft; I review, record and publish.
- **Primary sources only.** No invented figures, anywhere.
- **My words.** Notes and reflections are my thinking, not copies of the source.
