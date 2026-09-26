# Second Brain

> [!summary] A knowledge base in plain files that an AI writes and keeps up to date. Every answer gets filed, so the next question starts from everything you already know.

## Three layers
| Layer | Job | Here |
|---|---|---|
| UI | seeing and talking | Obsidian, a phone chat with a bot |
| API (business logic) | the rules for reading and writing | the AI agent, following `CLAUDE.md` |
| Database | storage and history | markdown files in a GitHub repo |

Swapping one layer doesn't break the others. Change bots, change note apps: the files stay.

## The loop
- You add a source to `raw/`, or ask a question.
- The agent reads the sections map in `index.md`, searches for the relevant pages, and answers.
- It updates or creates pages, adds them to `index.md`, and writes a `log.md` entry.
- You review, then it commits and pushes.

## Why files, not an app
- You own them. Any AI, any editor, any year can read markdown.
- GitHub keeps every version, so nothing is lost and every change can be undone.
- Links between pages are where the value compounds: a new case links to old concepts, and patterns show up.

## Links
- [[wiki/concepts/the-mastermind|The Mastermind]]
