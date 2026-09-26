# Bots on top of the second brain

## One Wiki bot
- Grok Bot keeps a copy of the repo on its own computer.
- A scheduled job pulls the latest from GitHub every few hours.
- The bot's one job: read and write the wiki under `CLAUDE.md`, then commit and push.
- You talk to it from your phone.

## Small bots with small jobs
Every bot reads the same second brain. Each has one narrow job.

| Bot | Job | Reads | Writes |
|---|---|---|---|
| Wiki | file anything, answer anything | everything | anywhere |
| Fitness (example) | training, food, sleep check-ins | health pages + index | health pages + log |

A narrow job means a short prompt and fewer mistakes, and it's easier to keep track of as things grow. Start with the Wiki bot. Add a specialist when one topic gets busy.

## Watch-outs
- You, the bot, and Claude Code all write to the same repo. Each one pulls before writing and pushes right after.
- Never put passwords or API keys in the wiki. It's a git repo.
