# Entity: Place note structure (place)

Place notes document physical locations relevant to partner dancing --
dance studios, practice spaces, social venues, and event halls. Each place
note captures location, capacity, and what dance styles or
[events](../14) it hosts. For the group that runs a venue, use an
[organization](../15) instead.

## Title format

- `# Place: DESCRIPTION`

## Minimal template

```md
# Place: DESCRIPTION

One to three sentence summary of the venue and its primary dance use.

## Details

- **Address**: street address, city, state
- **Styles**: salsa, bachata, swing, etc.
- **Floor**: wood / concrete / sprung / etc.
- **Capacity**: approximate number of dancers

## Schedule

Regular events held at this venue.

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: place
tags:
    - dance
    - twin-cities
```

## Related

- [Entity: Event note structure (event)](../14)
- [Entity: Organization note structure (organization)](../15)
- [System: Entity selection guide - dance](../5)