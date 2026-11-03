# Moving your notes into a second brain

> [!summary] Wherever your notes live now (Notion, Obsidian, Google Docs, Evernote, a folder of files), your agent reads them, proposes sections, and writes your second brain. Plan on a short afternoon, most of it the agent's time.

## 1. Back up
Export or copy everything, and keep that copy somewhere outside the new repo. Your old notes stay untouched.

## 2. Give the agent your notes
Set up the kit first (see `README.md` → Setup). Then get the agent access to your notes. You have two ways:
- **Export.** Download your notes as files and put them in a folder the agent can read. Markdown is best; HTML, Word and PDF work too.
- **Connect.** If your agent has a connector for the app (Notion and Google Drive often do), let it read from the app directly.

| Where your notes are | How to hand them over |
|---|---|
| Notion | **Settings → Export all workspace content → Markdown & CSV**, then unzip. Or a Notion connector. |
| Obsidian | The vault is already markdown. Point the agent at the folder. Your `[[links]]` carry over. |
| Google Docs | Google Takeout, or download as `.docx`. Or a Drive connector. |
| Anything else | Export to markdown, text or PDF. If you can open it, the agent can read it. |

## 3. Ask
Paste this, filling in the blanks:

> "My notes are currently in ___ (they're at ___). I want to move them into this second brain. Read `AGENTS.md`, then read through my notes. Propose the sections, which folders and what goes in each, and wait for my OK. Then write the pages, move original sources like articles and transcripts into `raw/`, build `index.md`, add a `log.md` entry, and push to GitHub."

The agent comes back with a proposed map. Adjust it ("merge these two," "clients get their own folder"), then let it run.

## 4. Spot-check
- Open `index.md` and check the sections fit how you think.
- Open three or four pages on topics you know well and check nothing important got lost.
- Ask a question only your old notes could answer. If the answer is right, you're done.

## Tips
- **Don't polish on day one.** Old notes can stay rough. They get tidied as questions touch them.
- **Big archives go in batches.** For thousands of pages, have the agent do one section per session.
- **GitHub rejects files over 100 MB.** Leave huge videos out.
- **Keep personal and company separate.** If your notes mix both, see habit 6 in `GUIDE.md`.

## Obsidian users
- You can keep your notes as they are instead of having them rewritten. Drag your folders into a `wiki/` folder **inside Obsidian's file explorer** (not Finder or Explorer), and Obsidian keeps every link working. Then ask the agent to build `index.md` only.
- Turn on **Settings → Files and links → Automatically update internal links** first.
- **Obsidian Sync and GitHub both sync the same files.** Running both on every device can cause conflicts, so give each one a lane:

| Setup | How it works | Good for |
|---|---|---|
| **Keep Sync for the phone** | Your computer's vault is the GitHub copy. The Obsidian Git community plugin pulls, commits and pushes on a timer there. Sync carries changes to your phone. | You read and write in Obsidian on your phone. |
| **Drop Sync** | GitHub is the only sync. On the phone, you talk to your agent instead of opening Obsidian. | You mostly use an agent on the go. Simpler and cheaper. |

With **Keep Sync**, changes from an agent reach your phone only after your computer pulls them, so your computer has to be on.

## Links
- `README.md` — setup from scratch
- `GUIDE.md` — getting the most out of it
