# Entity: Entity note structure (entity)

Entity notes define canonical structure expectations for every note type in
the dance KEG. Each [entity note](../6) is the source of truth for
formatting, required sections, and metadata expectations for its entity
type. See the [operating reference](../2) for the full list of entity
types.

## Title format

- `# Entity: DESCRIPTION (SLUG)` where SLUG is the lowercase entity name.
- Example: `# Entity: Move note structure (move)`

## Minimal template

```md
# Entity: <Type> note structure (<slug>)

One to three sentence summary of what this entity type covers.

## Title format

- `# <Prefix>: DESCRIPTION`

## Minimal template

(copy-paste starter for this entity type)

## Metadata template

(yaml block showing entity and recommended tags)

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: entity
tags:
    - entity
    - canonical
    - dance
```

## Required contents

- H1 title starts with `Entity:` and ends with the entity slug in
  parentheses.
- A one to three sentence lead paragraph that defines scope.
- A `## Title format` section with the expected H1 pattern.
- A `## Minimal template` section with a short copy-paste starter.
- A `## Metadata template` section showing `entity:` and recommended tags.
- A `## Related` section linking to at least three related notes.

## Related

- [System: operating reference - dance](../2)
- [System: Markdown style guide - dance](../3)
- [System: Entity selection guide - dance](../5)