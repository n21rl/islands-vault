---

database-plugin: basic

---

```yaml:dbfolder
name: Organisations
description: new description
columns:
  column1:
    input: text
    key: column1
    accessorKey: column1
    label: Column 1
    position: 1
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
    position: 2
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
  tags:
    input: tags
    accessorKey: tags
    key: tags
    id: tags
    label: tags
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 1
    width: 164
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "moc", value: "moc", color: "hsl(352, 95%, 90%)"}
      - { label: "organisation", value: "organisation", color: "hsl(142, 95%, 90%)"}
      - { label: "#deity", value: "#deity", color: "hsl(203, 95%, 90%)"}
      - { label: "act", value: "act", color: "hsl(153, 95%, 90%)"}
      - { label: "Category/Group", value: "Category/Group", color: "hsl(46, 95%, 90%)"}
      - { label: "Category/Settlement", value: "Category/Settlement", color: "hsl(218, 95%, 90%)"}
      - { label: "class/artificer", value: "class/artificer", color: "hsl(165, 95%, 90%)"}
      - { label: "compendium/src/5e/tce", value: "compendium/src/5e/tce", color: "hsl(37, 95%, 90%)"}
      - { label: "class/barbarian", value: "class/barbarian", color: "hsl(279, 95%, 90%)"}
      - { label: "compendium/src/5e/phb", value: "compendium/src/5e/phb", color: "hsl(152, 95%, 90%)"}
      - { label: "class/bard", value: "class/bard", color: "hsl(253, 95%, 90%)"}
      - { label: "class/cleric", value: "class/cleric", color: "hsl(331, 95%, 90%)"}
      - { label: "class/druid", value: "class/druid", color: "hsl(322, 95%, 90%)"}
      - { label: "class/expert-sidekick", value: "class/expert-sidekick", color: "hsl(239, 95%, 90%)"}
      - { label: "class/fighter", value: "class/fighter", color: "hsl(295, 95%, 90%)"}
      - { label: "class/monk", value: "class/monk", color: "hsl(201, 95%, 90%)"}
      - { label: "class/paladin", value: "class/paladin", color: "hsl(146, 95%, 90%)"}
      - { label: "class/ranger", value: "class/ranger", color: "hsl(269, 95%, 90%)"}
      - { label: "class/rogue", value: "class/rogue", color: "hsl(17, 95%, 90%)"}
      - { label: "class/sorcerer", value: "class/sorcerer", color: "hsl(203, 95%, 90%)"}
      - { label: "class/spellcaster-sidekick", value: "class/spellcaster-sidekick", color: "hsl(95, 95%, 90%)"}
      - { label: "class/warlock", value: "class/warlock", color: "hsl(98, 95%, 90%)"}
      - { label: "class/warrior-sidekick", value: "class/warrior-sidekick", color: "hsl(351, 95%, 90%)"}
      - { label: "class/wizard", value: "class/wizard", color: "hsl(79, 95%, 90%)"}
      - { label: "communication", value: "communication", color: "hsl(238, 95%, 90%)"}
      - { label: "email", value: "email", color: "hsl(308, 95%, 90%)"}
      - { label: "compendium/src/5e/ai", value: "compendium/src/5e/ai", color: "hsl(223, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  location:
    input: relation
    accessorKey: location
    key: location
    id: location
    label: location
    position: 5
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
      related_note_path: Locations/_Location DB.md
      relation_color: hsl(0,0%,42%)
  parent_org:
    input: relation
    accessorKey: parent_org
    key: parent_org
    id: organisation
    label: parent_org
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 100
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Organisations/_Organisation DB.md
      relation_color: hsl(0,0%,65%)
  the:
    input: checkbox
    accessorKey: the
    key: the
    id: the
    label: the
    position: 100
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
config:
  remove_field_when_delete_column: false
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
  source_form_result: "FROM \"Encyclopedia/Organisations\""
  source_destination_path: Encyclopedia/Organisations
  row_templates_folder: Generators/templates
  current_row_template: Databases/_DB _ Organisations.md
  pagination_size: 100
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: yyyy-MM-dd
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```