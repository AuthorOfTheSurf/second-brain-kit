# Second Brain

> [!summary] A knowledge base in plain files that an AI writes and keeps up to date. Every answer gets filed, so the next question starts from everything you already know.

## One brain, any agent
- The knowledge is markdown files in a GitHub repo.
- The rules are in `AGENTS.md`. Any agent that follows them can read and write the brain: Claude Code, Grok Bot, or the next one.
- Agents sync through GitHub, so what one saves, the others see.

Change agents or note apps and nothing breaks, because the files stay.

## The loop
- You ask a question or work on something. Sometimes you hand over a source (an article or transcript) for `raw/`.
- The agent reads the sections map in `index.md`, searches for the relevant pages, and answers.
- It updates or creates pages, adds them to `index.md`, and writes a `log.md` entry.
- You review, then it commits and pushes.

## Why plain files
- You own them. Any AI, any editor, any year can read markdown.
- GitHub keeps every version, so nothing is lost and every change can be undone.
- Links between pages are where the value compounds: a new case links to old concepts, and patterns show up.

## Open threads
- Ask a first question about something you're working on.
- Add a first advisor to [[wiki/concepts/the-mastermind|the mastermind]].

## Links
- [[wiki/concepts/the-mastermind|The Mastermind]]
