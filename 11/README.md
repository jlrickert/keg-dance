# Entity: Article note structure (article)

Article notes summarise external content relevant to partner dancing --
YouTube videos, blog posts, workshop recordings, and instructional
material. Each article note captures the source, key takeaways, and
connections to [concepts](../8) and [moves](../16) in this KEG. For
original step-by-step instructions, use a [guide](../10) instead.

## Title format

- `# Article: DESCRIPTION`

## Minimal template

```md
# Article: DESCRIPTION

One to three sentence summary of the external content and why it matters.

## Source

- **URL**: https://...
- **Author**: author name
- **Date**: YYYY-MM-DD

## Key takeaways

1. First insight
2. Second insight

## Notes

Personal observations and connections to existing knowledge.

## Related

- [Related note](../NNN)
```

## Metadata template

```yaml
entity: article
tags:
    - dance
```

## Related

- [Entity: Concept note structure (concept)](../8)
- [Entity: Guide note structure (guide)](../10)
- [System: Entity selection guide - dance](../5)