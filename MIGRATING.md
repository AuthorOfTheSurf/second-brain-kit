# Moving an existing Obsidian vault into a second brain

> [!summary] Keep your notes and your links. Add the kit's rules, put the vault on GitHub, and let the agent build the index. Rewrite nothing on day one.

## Before you start
- **Back up the vault.** Zip the whole folder and put the zip somewhere outside it.
- In Obsidian, turn on **Settings → Files and links → Automatically update internal links**. Then moving a note in Obsidian rewrites every link to it.

## 1. Add the kit to the vault
Copy these into the vault's top folder: `CLAUDE.md`, `index.md`, `log.md`, `raw/`, `.gitignore`, `.obsidian/app.json` (merge its settings into yours if the file exists), plus `GUIDE.md` and `BOTS.md` if you want them nearby.

## 2. Move your notes into `wiki/`
- Make a `wiki/` folder in Obsidian.
- Drag your existing top-level folders into it **inside Obsidian's file explorer**, not in Finder or Explorer. Obsidian keeps the links working; a file manager breaks them.
- Keep your own folder names. They become your sections.
- Attachments (images, PDFs) can stay where they are. Obsidian finds them by name.

## 3. Put it on GitHub
- In GitHub Desktop: **File → Add local repository**, pick the vault folder, then **Publish repository**. Keep it **private**.
- Check the `.gitignore` is in place first, so Obsidian's workspace and cache files stay out.
- GitHub rejects single files over 100 MB. Move huge videos out of the vault first.

## 4. Let the agent build the index
Open the vault in Claude Code or give the repo to your bot, then ask:

> "Read every page in `wiki/`. Build `index.md`: a sections map with one line per folder, then one line per page. Don't edit any page yet. List anything that looks like a source (clippings, articles, transcripts) that should move to `raw/`, and wait for my OK."

This is one big `ingest` session, and it's the only one that reads everything.

## 5. Conform pages as you touch them
- Don't rewrite the whole vault to the new page format. Your notes are in your voice; mass rewrites lose that and are hard to review.
- When a question touches an old page, the agent adds a summary line and a Links section then.
- Old pages work fine as they are. The index is what makes them findable.

## Obsidian Sync: keep it or drop it?
Obsidian Sync and GitHub both sync the same files. Running both on every device can create conflicts, so give each one a lane:

| Setup | How it works | Good for |
|---|---|---|
| **Keep Sync for the phone** | Your computer's vault is the GitHub copy. The Obsidian Git community plugin pulls, commits and pushes on a timer there. Sync carries changes to your phone. | You read and write in Obsidian on your phone. |
| **Drop Sync** | GitHub is the only sync. On the phone, you talk to your bot instead of opening Obsidian. | You mostly use the bot on the go. Simpler and cheaper. |

With **Keep Sync**, changes from the bot reach your phone only after your computer pulls them, so your computer has to be on. Only the computer runs git. Don't set up git on the phone too.

## Links
- `README.md` — setup from scratch
- `GUIDE.md` — getting the most out of it
