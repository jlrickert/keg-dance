# Entity: Draft note structure (draft)

Draft notes hold work-in-progress content that has not yet been assigned a
final [entity type](../6). Use a draft when you are unsure which entity
fits or when content is still forming. Promote drafts to the correct
entity type (e.g. [concept](../8), [move](../16), [reference](../9),
[article](../11)) once the content stabilizes.

## Title format

- `# Draft: DESCRIPTION`

## Minimal template

```md
# Draft: DESCRIPTION

One to three sentence summary of the draft content and intended direction.

## Notes

Raw content, ideas, and unstructured information.

## Intended entity

Which entity type this will likely become (e.g. concept, move, guide).

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: draft
tags:
    - dance
    - draft
```

## Related

- [Entity: Entity note structure (entity)](../6)
- [System: Entity selection guide - dance](../5)
- [System: operating reference - dance](../2)