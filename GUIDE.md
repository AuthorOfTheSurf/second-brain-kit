# Getting the most out of your second brain

> [!summary] Six habits that turn a folder of notes into something that gets smarter every week and works for you on every device.

## 1. Own the storage
- Your knowledge lives in plain markdown files in a private GitHub repo. No app owns it.
- Any AI can read it, today or in ten years. Switch tools and the files come with you.
- GitHub keeps every version, so a bad edit is always one step from undone.

## 2. File every answer (compounding)
The rule that makes it grow: **a good answer gets saved.**
- Ask a question, get an answer, and the agent writes it into the wiki.
- The next question starts from everything already filed, not from zero.
- New pages link to old ones. After a few months, the links show patterns you didn't know you had: the same mistake across three deals, the same idea from three books.

The more you use it, the more each answer is worth.

## 3. Capture with the least effort
The bottleneck is getting things in. Make it easy:
- **Voice.** Talk through a meeting or idea on your phone, then give the transcript to your bot.
- **Paste.** Articles, emails, call notes: drop them in `raw/` and say "ingest this."
- **Just ask.** A question you'd ask any AI, ask here instead. The answer gets filed.

## 4. Use it everywhere
- **Phone:** talk to your bot (Grok Bot) from anywhere.
- **Laptop:** Obsidian to browse; Claude Code for big jobs.
- **Any other AI:** point it at the repo, or paste in the pages that matter. It gets your context in seconds instead of you re-explaining your business every chat.

That last one is the everyday payoff. Your context is written down once and ready for any task: a sales email, a pricing decision, a plan for the week.

## 5. Give bots small jobs
Start with one Wiki bot that files anything. As a topic gets busy, give it its own bot:
- A **fitness bot** that logs training and reads your health pages.
- A **sales bot** that preps you before calls from your people and projects pages.
- A **mastermind** session where advisors you've researched weigh in on a decision.

Every bot reads the same second brain. Each owns a small part of it. A narrow job means a short prompt and fewer mistakes. See `BOTS.md`.

## 6. Keep personal and company separate
Two repos, with agents moving information between them:

| | Personal second brain | Company knowledge base |
|---|---|---|
| Who | you | the team |
| Holds | your thinking, people, health, drafts | processes, clients, decisions, how-tos |
| Access | private to you | shared with the team |

- **Personal pulls from company.** Your agents can read the company repo for context, so your answers know the business.
- **Company gets filled from personal.** When something you figured out is ready for the team, have an agent write it into the company repo as a clean page. You choose what moves. Nothing personal moves on its own.

## Keep it healthy
- **Review before commit.** Read what the agent changed before it's saved. Five seconds now saves a wrong fact spreading later.
- **Monthly tidy-up.** Ask: "Lint the wiki: broken links, orphan pages, contradictions, stale open threads."
- **Edit the rules.** `CLAUDE.md` is yours. When the agent keeps doing something you don't like, add a rule.
- **No secrets.** Passwords and API keys never go in the wiki.
