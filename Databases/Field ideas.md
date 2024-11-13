## Locations
   - parent_loc
   - sub_locs
   - neighbours
   - loc_type

## Organisations 
   - parent_org
   - sub_orgs
   - allies
   - rivals
   - purpose?
   
# People
   - affiliation
   - relationships
   - role
   
## Biology
   - classification?
   - habitats?
   
## Religion

## Documents
   - author
   - document_type
   - date
## Secrets
   - related_persons?
- related_locations
   
   - location: Link the secret to a specific place.

## Summaries
   - act / session_number: Track the campaign progress through acts or sessions.
   - key_events: A summary of major events in each session or act.
   - characters_involved?

## Things
   - category (e.g., Resource, Ship): Use for broader classifications.
   - owner?
   - source
   - properties?
---

### Example of Metadata Structure

For a file in the Locations folder:
```yaml
---
parent_loc: [[Northern Scattered Isles]]
sub_locs: [[New Destiny]], [[Mission]]
neighbors: [[Fort Island]], [[Eleuthera]]
region_type: "Archipelago"
description: "Cluster of islands known for..."
---
```

For a file in the Organisations folder:
```yaml
---
parent_org: [[Republic]]
sub_orgs: [[The Sea Dogs]], [[The Bards]]
allies: [[Siblín Guilds]]
rivals: [[Steorr]]
purpose: "Naval defense and exploration."
---
```

This should provide you with flexible but clear structures for each type of content in your vault. Let me know if you’d like help implementing these structures in your metadata script!