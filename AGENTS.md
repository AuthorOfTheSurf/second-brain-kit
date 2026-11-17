# Second Brain — house rules

You maintain this knowledge base. I bring sources and questions; you do the writing, filing and linking. Read this file every session.

## Layout
```
index.md   ← a sections map at the top, then one line per page. Read the map FIRST.
log.md     ← append-only history, newest at the bottom
raw/       ← my original sources (articles, transcripts, notes). NEVER edit these.
wiki/      ← pages you write and keep up to date, grouped in folders by topic
```
The sections map at the top of `index.md` lists each section: its folder(s), what goes there, and any rules for it. Before answering, read the map, then search `index.md` and `wiki/` for the topic. Read the whole index only while it's short. When a topic outgrows the existing folders, make a new folder and add it to the map.

## Pages
- Start with `# Title` and a one-line summary: `> [!summary] ...`
- Short sections. Tables for comparisons. Concrete examples over theory.
- Link generously with `[[page-name]]` or `[[folder/page-name|Title]]`; Obsidian resolves both. A link to a page that doesn't exist yet is fine — it marks something worth writing.
- End with a **Links** section.
- One idea per page. Don't copy a fact into two pages — link to it. If two vocabularies name the same idea, map them in a table on one page.
- Pages with ongoing work (projects, and hub pages many others link to) keep an **Open threads** list. When one closes, mark it ✅ and link the page that closed it.
- Real people: only what I've told you. Mark gaps "to confirm". Never invent facts.

## After every answer (not just when I add a source)
A good answer gets saved:
1. Create or update the pages it touches.
2. If something new contradicts an old page, flag it on the page — don't silently overwrite.
3. Add new pages to `index.md` under the right section: one line, one sentence on what the page is. The detail goes in the page's summary.
4. Add a `log.md` entry (format below).
5. Close any open threads this answered.
6. List every file you changed, one per line, as repo-relative paths.
7. Ask before committing in a live chat. A scheduled bot job, or a session where I've pre-approved commits, commits and pushes on its own.

## Log format
```
## [YYYY-MM-DD] <ingest|query|lint> | <Short Title>
- what I asked, the answer in brief, pages created/updated, open threads
```
`lint` is a tidy-up pass: broken links, orphan pages, contradictions, stale open threads. Use today's real date. Check recent entries with `grep "^## \[" log.md | tail -5`.

## Git
- When I say "save", commit and push. Written but not committed isn't saved; committed but not pushed isn't saved. If the push fails, say it isn't saved yet.
- If the repo has a remote, pull before you start editing; a bot or another device may have pushed.
- One commit per log entry. The title is the log line without the date (e.g. `query | Morning routine`). Push after committing. If a push fails or there's no remote yet, say so and carry on.
- Fold my feedback in *before* committing, so each commit is a reviewed unit.
- Never put passwords, API keys or tokens in the wiki. It's a git repo.

## Style
- Write for a smart reader who's new to the topic. Use the real term, not a dumbed-down stand-in. If the reader may not know it, explain it once in a short clause. Don't explain words they already use.
- Every sentence carries information. No warm-up, no recap, no "it's not X, it's Y", no telling the reader how to read what follows.
- Short sentences. Plain words when they're just as precise. Spell out acronyms the first time.
- Say when evidence is weak. Honest over tidy.
- Connect ideas across pages; note tensions and gaps.
- Steps and lists go in bullets, not arrow chains in prose.
- Never a bare number: write "step 4 (the review)", not "step 4".
- Short is fine. A short page is finished, not thin. Extend a page only when you can name the specific thing it's missing.
