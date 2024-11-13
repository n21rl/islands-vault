---

database-plugin: basic

---

```yaml:dbfolder
name: Adventurers
description: 
columns:
  status:
    input: select
    accessorKey: status
    label: status
    key: status
    id: status
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "alive", value: "alive", color: "hsl(220, 95%, 90%)"}
      - { label: "away", value: "away", color: "hsl(96, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  level:
    input: number
    accessorKey: level
    label: level
    key: level
    id: level
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  class:
    input: tags
    accessorKey: class
    label: class
    key: class
    id: class
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 155
    options:
      - { label: "Artificer", value: "Artificer", color: "hsl(193, 95%, 90%)"}
      - { label: "Fighter", value: "Fighter", color: "hsl(24, 95%, 90%)"}
      - { label: "Warlock", value: "Warlock", color: "hsl(217, 95%, 90%)"}
      - { label: "Wizard", value: "Wizard", color: "hsl(188, 95%, 90%)"}
      - { label: "Bard", value: "Bard", color: "hsl(320, 95%, 90%)"}
      - { label: "Cleric", value: "Cleric", color: "hsl(230, 95%, 90%)"}
      - { label: "Rogue", value: "Rogue", color: "hsl(248, 95%, 90%)"}
      - { label: "Ranger", value: "Ranger", color: "hsl(94, 95%, 90%)"}
      - { label: "Fighter/Warlock", value: "Fighter/Warlock", color: "hsl(0,96%,90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  tags:
    input: tags
    accessorKey: tags
    label: tags
    key: tags
    id: tags
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 100
    options:
      - { label: "pc", value: "pc", color: "hsl(265, 95%, 90%)"}
      - { label: "document", value: "document", color: "hsl(87, 95%, 90%)"}
      - { label: "person", value: "person", color: "hsl(122, 95%, 90%)"}
      - { label: "compendium/src/5e/dmg", value: "compendium/src/5e/dmg", color: "hsl(67, 95%, 90%)"}
      - { label: "class/artificer", value: "class/artificer", color: "hsl(147, 95%, 90%)"}
      - { label: "compendium/src/5e/tce", value: "compendium/src/5e/tce", color: "hsl(71, 95%, 90%)"}
      - { label: "compendium/src/5e/xge", value: "compendium/src/5e/xge", color: "hsl(82, 95%, 90%)"}
      - { label: "subclass/barbarian/ancestral-guardian", value: "subclass/barbarian/ancestral-guardian", color: "hsl(293, 95%, 90%)"}
      - { label: "compendium/src/5e/scag", value: "compendium/src/5e/scag", color: "hsl(115, 95%, 90%)"}
      - { label: "subclass/barbarian/battlerager", value: "subclass/barbarian/battlerager", color: "hsl(51, 95%, 90%)"}
      - { label: "subclass/barbarian/beast", value: "subclass/barbarian/beast", color: "hsl(10, 95%, 90%)"}
      - { label: "compendium/src/5e/phb", value: "compendium/src/5e/phb", color: "hsl(104, 95%, 90%)"}
      - { label: "subclass/barbarian/berserker", value: "subclass/barbarian/berserker", color: "hsl(340, 95%, 90%)"}
      - { label: "subclass/barbarian/storm-herald", value: "subclass/barbarian/storm-herald", color: "hsl(48, 95%, 90%)"}
      - { label: "subclass/barbarian/totem-warrior", value: "subclass/barbarian/totem-warrior", color: "hsl(89, 95%, 90%)"}
      - { label: "subclass/barbarian/zealot", value: "subclass/barbarian/zealot", color: "hsl(273, 95%, 90%)"}
      - { label: "subclass/barbarian/wild-magic", value: "subclass/barbarian/wild-magic", color: "hsl(119, 95%, 90%)"}
      - { label: "class/barbarian", value: "class/barbarian", color: "hsl(303, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  race:
    input: select
    accessorKey: race
    key: race
    id: race
    label: race
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Dwarf", value: "Dwarf", color: "hsl(100, 95%, 90%)"}
      - { label: "Human", value: "Human", color: "hsl(248, 95%, 90%)"}
      - { label: "Kenku", value: "Kenku", color: "hsl(257, 95%, 90%)"}
      - { label: "Half-Elf", value: "Half-Elf", color: "hsl(96, 95%, 90%)"}
      - { label: "Gnome", value: "Gnome", color: "hsl(76, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  pronouns:
    input: select
    accessorKey: pronouns
    key: pronouns
    id: pronouns
    label: pronouns
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "he/him", value: "he/him", color: "hsl(212,93%,88%)"}
      - { label: "she/her", value: "she/her", color: "hsl(310,96%,90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  age:
    input: number
    accessorKey: age
    key: age
    id: age
    label: age
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  dg-publish:
    input: text
    accessorKey: dg-publish
    key: dg-publish
    id: dg-publish
    label: dg-publish
    position: 13
    skipPersist: false
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  hp:
    input: number
    accessorKey: hp
    key: hp
    id: HP
    label: hp
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  modifier:
    input: number
    accessorKey: modifier
    key: modifier
    id: initiative
    label: modifier
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  ac:
    input: number
    accessorKey: ac
    key: ac
    id: AC
    label: ac
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  pp:
    input: number
    accessorKey: pp
    key: pp
    id: p_perception
    label: pp
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  organisations:
    input: text
    accessorKey: organisations
    key: organisations
    id: organisations
    label: organisations
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 152
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
config:
  remove_field_when_delete_column: true
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: query
  source_form_result: "FROM \"Encyclopedia/People/Adventurers\""
  source_destination_path: Encyclopedia/People/Adventurers
  row_templates_folder: /
  current_row_template: _tools/templates/PC.md
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```