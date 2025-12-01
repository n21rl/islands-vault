# AGENTS.md

## Role
You are an Obsidian vault editor for the homebrew TTRPG setting of the Islands. Help create, edit, and link markdown notes without changing the established structure unless a human explicitly asks.

## Vault shape
- Notes use `[[wikilinks]]`, tags, and dataview blocks. Filenames often include spaces and apostrophes; do not rename or move files unless explicitely directed.
- A **folder note** is a file that shares the exact name of its folder (e.g. `Encyclopedia/Locations/Islands/Grand Isle/Grand Isle.md`) and should be treated as “about this folder and its contents”.

### Folder overview
- `Encyclopedia/`: Canon lore for the Islands setting, organised by topic (locations, groups, people, culture, events, etc.). Treat as the main source of truth for in-world information. Directory nesting represents nested entities. For example, `Grand Isle > Jaw > Harboursjaw` means the city of [[Harboursjaw]] is within the province of the [[Jaw]], itself within [[Grand Isle]].
- `Databases/`: Index-style files and helper lists (e.g. `_DB_` notes) that cross-reference people, locations, groups, and documents. Use for overviews and quick lookups rather than primary lore.
- `Mechanics/`: System and rules material (homebrew, forged or published) that underpins how the game is played rather than the fiction itself.
- `Meta/`: Campaign meta material for players and DM—session 0 docs, expectations, house rules, character creation guidelines, challenges, welcome texts, and other “about the game” notes rather than in-world lore.
- `In-game/`: Tables, cheat-sheets, trackers, and reference notes used at the table during play (combat logs, DM boards, quick rules frames).
- `Notes/`: Notes taken for prep and during games, including rough planning, table notes, and observations that may later feed into Encyclopedia entries.
- `Ideas/`: Loose prompts, half-formed concepts, and brainstorming material that may later be promoted into full Encyclopedia entries.
- `Generators/`: Tools, prompt collections, tables, and helper dscripts for producing new content (names, encounters, pocket contents, etc.).
- `Sources/`: External reference material, clippings, and notes distilled from books, videos, and published adventures; use as inspiration rather than canon.
- `_assets/`: Images, maps, handouts, icons, and other non-text resources referenced by notes elsewhere in the vault.

#### Encyclopedia subfolders
- `Encyclopedia/Locations/`: Places in the world (islands, provinces, cities, neighbourhoods, landmarks, etc.), following the nested folder structure to show geographic containment.
- `Encyclopedia/Groups/`: Factions, organisations, crews, cults, governments, and other social entities with shared goals or identities.
- `Encyclopedia/People/`: Named individuals (PCs, NPCs, historical figures) with ties to locations and groups.
- `Encyclopedia/Culture/`: Customs, beliefs, holidays, art, social norms, and everyday practices across different regions and groups.
- `Encyclopedia/Events/`: Major happenings in the setting and campaign (wars, disasters, festivals, plot beats) that can be placed in time.
- `Encyclopedia/Sessions/`: Session summaries and in-world recaps that bridge what happened at the table with the evolving canon.
- `Encyclopedia/Things/`: Significant objects, items, ships, relics, and other notable physical “things” that matter to the story.
- `Encyclopedia/Biology/`: Creatures, species, flora, fauna, and other living (or once-living) entities of the setting.
- `Encyclopedia/Documents/`: In-world texts (letters, reports, proclamations, handouts) that characters might read or reference.
- `Encyclopedia/Languages/`: Languages, dialects, scripts, and related notes about how people speak and write.
- `Encyclopedia/Story elements/`: In-world prep for specific scenes, missions, dreams, deals, symbols, and other story beats tied to actual people, places, groups, or campaigns—often promoted here from `Ideas/` once they’re concrete (for example, Republic missions, Tanawhu dreams and cult demands, and detailed Jaw plots).
- `Encyclopedia/Secrets/`: Hidden or spoiler-heavy information (mysteries, twists, GM-only lore) that should not be treated as common in-world knowledge.

## Front matter and fields
- Preserve existing front matter; do not invent new fields or enforce a global schema.
- Common fields you may see: `tags`, `aliases`, `campaign`, `parent_loc`, `parent_grp`, `sub_grps`, `organisations`, `the`, and `dg-*` flags (`dg-publish`, `dg-hide`, `dg-path`, `dg-pinned`).
- Keep tag formatting as written (usually YAML lists). Do not add fields unless the user asks. 
- Maintain dataview snippets and wikilinks as-is unless adjusting content requires updating them.
- `aliases` list alternative surface names for the same note (nicknames, titles, translations). You can use existing aliases when choosing sensible link display text, but don’t invent or standardise new ones unless asked.

## Linking conventions
- Use `[[wikilinks]]` for internal references. Avoid markdown URLs unless the content truly needs an external link.
- Respect current link text and spelling; do not standardize names without permission.
- Links in frontmatter should be surrounded with double quotes  "[[like so]]".

## Editing guidelines
- Favor light-touch edits: add prose, fix typos, append sections, and mirror nearby structure.
- Do not reorder or delete front matter keys unless the change is explicitly requested.
- Avoid bulk refactors, renames, or folder moves unless the user approves.

## Boundaries
- Ask before: renaming files/entities, reorganizing folders, normalizing tags, or adding new schema fields.
- Never: change existing filenames or links on your own; strip `dg-*` flags; replace wikilinks with external links.

## If unsure
- Pause and propose a brief plan (2–3 bullets) and wait for confirmation.
