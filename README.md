# Second Brain starter kit

A knowledge base an AI writes and maintains for you, in plain text files you own. You bring sources and questions; the AI files, links and answers.

## The three layers
| Layer | What it does | Here |
|---|---|---|
| UI | how you see it and talk to it | Obsidian to browse; a chat with your bot or Claude to talk |
| API (business logic) | the rules for reading and writing it | an AI agent following `CLAUDE.md` |
| Database | where the knowledge lives | a folder of markdown files, versioned on GitHub |

Obsidian is only the UI. The value is in the files and the rules.

## What it costs
- **Start: Grok Bot, $30/mo** (SuperGrok). An always-on AI with its own computer. It can set this kit up for you, and you talk to it from your phone.
- **Next: Claude Max, $100/mo.** Adds Claude Code, the stronger agent for big ingests, reorganizing, and long sessions.
- GitHub (private repo) and Obsidian are free.

## Setup
1. Make a free GitHub account.
2. Give this kit to Grok Bot. Ask it to create a private GitHub repo from it, keep a copy on its computer, and put today's date in the first `log.md` entry.
3. Install Obsidian and open the repo folder in it to browse your pages.
4. Later, with Claude Max: install the Claude desktop app, open the Code tab, and point it at the same folder.

## First session
- Drop an article, transcript or notes into `raw/` and say "ingest this."
- Or just ask a question. The answer gets filed.
- Then open `index.md` in Obsidian and follow the links.

## What's in the box
```
CLAUDE.md   ← the rules the AI follows (edit them as you go)
index.md    ← catalog of every page, by section
log.md      ← history of every session
raw/        ← your sources, never edited
wiki/       ← the pages the AI writes
BOTS.md     ← small bots with small jobs
```
Two starter pages are already filed: `wiki/concepts/second-brain.md` (how this works) and `wiki/concepts/the-mastermind.md` (a way to use it you might not think of).

## Modules
A module is a set of ready-made pages dropped into `wiki/` so your second brain starts off knowing a field: fitness, sales, self-coaching. Ask for one when you want a topic to start strong.
