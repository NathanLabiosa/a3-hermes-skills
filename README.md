# a3-hermes-skills

Public skill tap for the CSCI 599 Assignment 3 Hermes agent.

## Skills
| Skill | What it does |
|---|---|
| `deadline-tracker` | Ranks deadlines from calendar + email + notes by urgency with days remaining and a next action. Read-only. |

## Install (any Hermes install)
```bash
hermes skills tap add NathanLabiosa/a3-hermes-skills
hermes skills search deadline --source github
hermes skills install NathanLabiosa/a3-hermes-skills/skills/deadline-tracker
```
No credentials, no absolute paths. Content is synthetic-data safe.
