# Entity: Move note structure (move)

Move notes document individual dance moves, patterns, and combinations in
the dance KEG. Each move note captures the name, dance style, lead-follow
mechanics, and technique details. For broader principles like connection
or frame, use a [concept](../8) instead. For step-by-step practice drills,
use a [guide](../10).

## Title format

- `# Move: DESCRIPTION`

## Minimal template

```md
# Move: DESCRIPTION

One to three sentence summary of the move and which style it belongs to.

## Style

- **Dance**: salsa / bachata / lindy hop / etc.
- **Level**: beginner / intermediate / advanced
- **Count**: timing pattern (e.g. 1-2-3, 5-6-7 for salsa)

## Technique

Step-by-step breakdown of the lead and follow mechanics.

### Lead

What the lead does.

### Follow

What the follow does.

## Variations

Named variations or styling options for this move.

## Prerequisites

- [Move: prerequisite move](../NNN)
- [Concept: prerequisite concept](../NNN)

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: move
tags:
    - dance
    - STYLE_TAG
```

Use the dance style as a tag (e.g. `salsa`, `bachata`, `lindy-hop`).

## Related

- [Entity: Concept note structure (concept)](../8)
- [Entity: Guide note structure (guide)](../10)
- [System: Entity selection guide - dance](../5)