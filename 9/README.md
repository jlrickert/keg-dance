# Entity: Reference note structure (reference)

Reference notes are stable lookup notes for dance-related data in the
dance KEG -- timing charts, style comparisons, music tempo ranges, and
other structured information. A reference answers *how* to use something
rather than *what* it is (use a [concept](../8) for that). References are
updated in place rather than versioned.

## Title format

- `# Reference: DESCRIPTION`

## Minimal template

```md
# Reference: DESCRIPTION

One to three sentence summary of what this reference covers.

## (data sections as needed -- tables, lists, specs)

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: reference
tags:
    - dance
```

## Related

- [Entity: Concept note structure (concept)](../8)
- [Entity: Guide note structure (guide)](../10)
- [System: Entity selection guide - dance](../5)