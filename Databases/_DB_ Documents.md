---

database-plugin: basic

---

```yaml:dbfolder
name: DB
description: Database of documents
columns:
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
    position: 0
    isHidden: false
    sortIndex: -1
    width: 139
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
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 166
    options:
      - { label: "document", value: "document", color: "hsl(120, 95%, 90%)"}
      - { label: "location", value: "location", color: "hsl(144, 95%, 90%)"}
      - { label: "organisation", value: "organisation", color: "hsl(348, 95%, 90%)"}
      - { label: "pc", value: "pc", color: "hsl(338, 95%, 90%)"}
      - { label: "npc", value: "npc", color: "hsl(357, 95%, 90%)"}
      - { label: "document/letter", value: "document/letter", color: "hsl(29, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  note_type:
    input: text
    accessorKey: note_type
    key: note_type
    id: note_type
    label: note_type
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
  author:
    input: text
    accessorKey: author
    key: author
    id: author
    label: author
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 122
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  document_type:
    input: select
    accessorKey: document_type
    key: document_type
    id: document_type
    label: document_type
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "song", value: "song", color: "hsl(195, 95%, 90%)"}
      - { label: "letter", value: "letter", color: "hsl(189, 95%, 90%)"}
      - { label: "speech", value: "speech", color: "hsl(125, 95%, 90%)"}
      - { label: "ledger", value: "ledger", color: "hsl(1, 95%, 90%)"}
      - { label: "newspaper", value: "newspaper", color: "hsl(9, 95%, 90%)"}
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
  sticky_first_column: true
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
  source_form_result: "FROM \"Encyclopedia/Documents\""
  source_destination_path: Encyclopedia/Documents
  row_templates_folder: Ξ tools/templates
  current_row_template: 
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