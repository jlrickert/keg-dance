# Entity: Person note structure (person)

Person notes document individuals relevant to partner dancing --
instructors, dance partners, notable dancers, and community figures. Each
person note captures their styles, teaching focus, and connections to
[events](../14) and [organizations](../15).

## Title format

- `# Person: FULL_NAME`

## Minimal template

```md
# Person: FULL_NAME

One to three sentence summary of who this person is and their role in the
dance community.

## Details

- **Styles**: salsa, bachata, etc.
- **Role**: Instructor / Partner / Performer
- **Location**: city or venue

## Notes

Context about this person and what I have learned from them.

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: person
tags:
    - dance
```

## Related

- [Entity: Event note structure (event)](../14)
- [Entity: Organization note structure (organization)](../15)
- [System: Entity selection guide - dance](../5)