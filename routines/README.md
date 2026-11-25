# Routines

The daemons of the OS. Each file defines one scheduled task in plain language. The scheduled task in Claude should use the **Prompt** section of its file word for word.

Change the file first, then update the scheduled task.

| Routine | Schedule (Pacific) | Track | Status |
|---|---|---|---|
| [`deal-decoded-scout`](deal-decoded-scout.md) | Weekdays, morning | M&A | 🔁 Running |
| [`daily-podcast`](daily-podcast.md) | Daily, morning | M&A | 💡 Proposed |
| [`learning-notes-intake`](learning-notes-intake.md) | Weekly, Sunday | All | 💡 Proposed |

## Every routine file has
- **Schedule**: when it runs
- **Inputs**: what it reads
- **Outputs**: what it writes and where
- **Prompt**: the exact instruction the scheduled task sends
- **Guardrails**: what it must never do
