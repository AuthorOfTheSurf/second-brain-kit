# Second Brain starter kit

**Own your brain. Run it with any AI.**

Your second brain is a folder of plain text files that your AI agents read and write. Every question you ask and every project you work on leaves something behind. Next week, whatever AI you use already knows your business, your people and your processes.

**New here? Read [`GUIDE.md`](GUIDE.md)** for the six habits that get the most out of it.

## Why entrepreneurs use it
- **Stop re-explaining your business.** Every agent reads the same brain, so a new chat starts out knowing your offers, clients and goals.
- **Never get locked in.** AI tools change every month. Your brain is markdown files you own, so you can try the new tool this week and it's smart on day one. You can also run several at once.
- **Knowledge compounds on its own.** You don't file anything. The agent saves what you learn as you work, and the next answer starts from everything before it.
- **Get your SOPs out of your head.** SOPs (standard operating procedures), skills and processes live in the brain, where any agent or new hire can run them.
- **Onboard in a day, not weeks.** A new VA (virtual assistant) or hire gets the company brain, and their agents start out knowing how you work.

## What it looks like
- **You just work.** Ask your agent about pricing, a client or a Spanish lesson. It answers, then saves what matters into the right page. You never say "save this."
- **You point it at something.** At a bookstore, three books catch your eye: "Research these three, save summaries to my second brain, and teach me the best idea from each."
- **Your team runs on it.** Your sales process, hiring checklist and client notes are written down once. A new assistant's agent reads them and gets to work.

## Works with any agent
Use the one you like. They all share one brain:
- **Claude Code** for big jobs: long sessions, reorganizing, moving notes in.
- **Grok Bot** for an always-on agent you talk to from your phone.
- **Any other frontier agent** (Codex, an AI browser, whatever comes next) that can read and write files in a GitHub repo.

When one agent saves something, it pushes to GitHub, and every other agent pulls the latest. Want to browse your brain like a notebook? Open the folder in [Obsidian](https://obsidian.md). It's optional, because the agents do the work.

## Tools
- **An AI agent** that can work with files. Pick one from the list above.
- **GitHub** (free). A private repo stores your brain, keeps every version, and syncs every agent and device.
- **Optional:** Obsidian, to read and click through your pages.

## Setup
1. Make a free [GitHub](https://github.com) account. On this repo's page, click **Use this template** and create a **private** repo.
2. Connect your agent:
   - **Claude Code:** in the Claude desktop app's Code tab, say: "Clone my repo `<your repo URL>` and open it." If it asks you to sign in to GitHub, follow its steps. It reads the rules in `CLAUDE.md` on its own.
   - **Grok Bot:** give it your repo's URL. Ask it to connect to GitHub with write access, clone the repo, read `CLAUDE.md` and follow it in every session, and pull the latest every few hours.
   - **Any other agent:** same as Grok Bot.
3. Seed it with a 15-minute interview. Say:
   > "Interview me so my second brain knows me. Ask about my business, my current projects, my goals for this year, and the people I work with. Ask one question at a time. Then file what you learned and push."
4. Check it worked. Open your repo on GitHub. You should see new pages in `wiki/` and a first entry in `log.md`.
5. From now on, just work. Ask your agent anything you're working on, and the brain grows with every answer.

**Already have notes in Notion, Obsidian or Google Docs?** Your agent can move them in for you in an afternoon. See [`MIGRATING.md`](MIGRATING.md).

## What's in the box
```
CLAUDE.md     ← the rules every agent follows (edit them as you go)
index.md      ← the map of your brain
log.md        ← history of every session
raw/          ← original sources, never edited
wiki/         ← the pages your agents write
GUIDE.md      ← six habits for getting the most out of it
MIGRATING.md  ← bring in notes from anywhere
BOTS.md       ← small bots with small jobs
```
Two starter pages are already filed: `wiki/concepts/second-brain.md` (how it works) and `wiki/concepts/the-mastermind.md` (a way to use it you might not think of).

## Modules
A module is a set of ready-made pages dropped into `wiki/` so your brain starts off knowing a field, such as fitness, sales or self-coaching. None ship with the kit yet. Ask your agent to build one when you want a topic to start strong.

MIT licensed: copy it, change it, hand it on.
