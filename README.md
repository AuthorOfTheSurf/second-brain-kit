# Second Brain starter kit

A knowledge base an AI writes and maintains for you, in plain text files you own. You bring sources and questions; the AI files, links and answers.

## The three layers
| Layer | What it does | Here |
|---|---|---|
| UI (user interface) | how you see it and talk to it | Obsidian to browse; a chat with your bot or Claude to talk |
| API (business logic) | the rules for reading and writing it | an AI agent following `CLAUDE.md` |
| Database | where the knowledge lives | a folder of markdown files, versioned on GitHub |

Obsidian is only the UI. The value is in the files and the rules.

**New here? Read [`GUIDE.md`](GUIDE.md)** for the six habits that get the most out of it.

## What it costs
Prices as of September 2026.

- **Start: Grok Bot, $30/mo** (SuperGrok). An always-on AI with its own computer. It can set this kit up for you, and you talk to it from your phone.
- **Next: Claude Max, $100/mo.** Adds Claude Code, the stronger agent for big ingests, reorganizing, and long sessions.
- GitHub (private repo) and Obsidian are free.

MIT licensed: copy it, change it, hand it on.

## Setup
Already have an Obsidian vault? Follow [`MIGRATING.md`](MIGRATING.md) instead.

1. Make a free GitHub account.
2. On this repo's page, click **Use this template** and create a **private** repo in your account.
3. Give Grok Bot your new repo's URL. Ask it to connect to GitHub with write access, clone the repo onto its computer, add a first `log.md` entry with today's date, and set up a job that pulls the latest every few hours.
4. On your computer, install GitHub Desktop and clone the same repo. Open that folder in Obsidian to browse your pages.
5. Later, with Claude Max: in the Claude desktop app's Code tab, open the folder on your computer. Your copy and the bot's copy stay in sync through GitHub.

Links between pages work in Obsidian. On GitHub they show as plain text.

## First session
- Drop an article, transcript or notes into `raw/` and say "ingest this."
- Or just ask a question. The answer gets filed.
- Then open `index.md` in Obsidian and follow the links.

## What's in the box
```
CLAUDE.md     ← the rules the AI follows (edit them as you go)
index.md      ← sections map, then one line per page
log.md        ← history of every session
raw/          ← your sources, never edited
wiki/         ← the pages the AI writes
GUIDE.md      ← how to get the most out of it
MIGRATING.md  ← bring in an existing Obsidian vault
BOTS.md       ← small bots with small jobs
```
Two starter pages are already filed: `wiki/concepts/second-brain.md` (how this works) and `wiki/concepts/the-mastermind.md` (a way to use it you might not think of).

## Modules
A module is a set of ready-made pages dropped into `wiki/` so your second brain starts off knowing a field: fitness, sales, self-coaching. None ship with the kit yet. Ask the agent to build one when you want a topic to start strong.
