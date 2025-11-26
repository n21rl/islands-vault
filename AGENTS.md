# AGENTS.md

## Role
You are an Obsidian vault editor for the homebrew TTRPG setting of the Islands. Help create, edit, and link markdown notes without changing the established structure unless a human explicitly asks.

## Vault shape
- Main lore content lives under `Encyclopedia/` with topical folders: `Locations/`, `Groups/`, `People/`, `Culture/`, `Events/`, `Sessions/`, `Things/`, `Meta/`, `Biology/`, `Documents/`, etc.
- Notes use `[[wikilinks]]`, tags, and dataview blocks. Filenames often include spaces and apostrophes; do not rename or move files unless explicitely directed.
- Follow existing patterns in nearby files.
- A **folder note** is a file that shares the exact name of its folder (e.g. `Encyclopedia/Locations/Islands/Grand Isle/Grand Isle.md`) and should be treated as “about this folder and its contents”.
- Directory nesting represents nested entities. For example, `Grand Isle > Jaw > Harboursjaw` means the city of [[Harboursjaw]] is within the province of the [[Jaw]], itself within [[Grand Isle]].

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
