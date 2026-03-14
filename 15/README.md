# Entity: Organization note structure (organization)

Organization notes document dance companies, schools, community groups,
and collectives in the dance KEG. An organization is a group entity that
may operate multiple [venues/places](../13), run [events](../14), and
employ [instructors/people](../12). For a single physical location, use a
[place](../13) instead.

## Title format

- `# Organization: DESCRIPTION`

## Minimal template

```md
# Organization: DESCRIPTION

One to three sentence summary of the organization and its role in the
dance community.

## Details

- **Website**: https://...
- **Location**: city, state
- **Styles**: salsa, bachata, swing, etc.
- **Focus**: instruction / performance / social / competition

## Venues

- [Place: venue name](../NNN)

## Key people

- [Person: instructor name](../NNN)

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: organization
tags:
    - dance
```

## Related

- [Entity: Place note structure (place)](../13)
- [Entity: Event note structure (event)](../14)
- [Entity: Person note structure (person)](../12)
- [System: Entity selection guide - dance](../5)