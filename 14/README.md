# Entity: Event note structure (event)

Event notes document scheduled dance occurrences -- socials, workshops,
festivals, classes, and performances. Each event note captures timing,
[venue/place](../13), [instructors/people](../12) involved, and outcomes.
For the group that organises events, use an [organization](../15) instead.

## Title format

- `# Event: DESCRIPTION (YYYY-MM-DD)`

## Minimal template

```md
# Event: DESCRIPTION (YYYY-MM-DD)

One to three sentence summary of the event.

## Details

- **Date**: YYYY-MM-DD
- **Time**: H:MM AM/PM
- **Location**: [Place name](../NNN)
- **Instructor/Host**: [Person name](../NNN)
- **Style**: salsa / bachata / swing / etc.
- **Cost**: free / $X

## Description

What this event covers and who it is for.

## Notes

Personal observations, key takeaways, moves learned.

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: event
tags:
    - dance
```

## Related

- [Entity: Person note structure (person)](../12)
- [Entity: Place note structure (place)](../13)
- [Entity: Organization note structure (organization)](../15)
- [System: Entity selection guide - dance](../5)