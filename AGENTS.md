# Mason Family Prison Break - Agent Notes

## Project Structure

This is a tabletop RPG campaign workspace. Content is organised by campaign.

- `Campaign 2/` — the active campaign
  - `campaign log.md` — session-by-session record of events
  - `Missions/` — mission briefs (M01 through M08+), mixing backstory, plot hooks, and possible player approaches
  - `NPCs/` — character files and portrait images (`.png`, `.jpeg`), stored flat in the same folder
  - `PCs/` — player character files
  - `Places/` — location descriptions; `tower/` subfolder has many rooms
  - `Organisations/` — faction descriptions
  - `monsters/` — creature stat blocks and notes
  - `spells/` — custom spell descriptions

## Conventions

- NPC files are short markdown: name as the title, a brief description, then whatever detail is relevant (personality, stats, relationships). There is no rigid template — some are one line, some are detailed.
- Monster/NPC stat blocks follow a compact format: `STR DEX CON INT WIS CHA   HP  AC  SPD` on one line, then actions listed below. See `monsters/elephant spirit.md` or the stats section in `NPCs/Dirge.md` for examples.
- Character portrait images go directly in `NPCs/` alongside the `.md` files, not in a subfolder.
- Mission files are numbered sequentially (M01, M02, etc.) and use act-based or section-based structure with possible player approaches and complications.
- The campaign log uses date headers (`## 25th`) and plain prose underneath.

## Gotchas

- The workspace path contains spaces. Shell commands must quote all paths.
- When copying or writing files to this project, avoid name collisions with existing files — check first.
- Spelling in the campaign files is informal and intentional. Don't correct the DM's spelling in existing content.
