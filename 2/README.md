# System: operating reference - dance

The `dance` KEG is a private knowledge base for partner dancing -- styles,
techniques, [moves](../16), venues, community events, and instruction
notes. Content focuses on the Twin Cities dance scene but covers general
partner dance knowledge as well.

## Purpose

Personal partner dance knowledge store. Notes cover dance styles,
technique breakdowns, individual [moves](../16), venue information,
instructor notes, and community events. Content is written for personal
reference and long-term skill development.

## Scope

Belongs here:

- Partner dance styles (salsa, bachata, lindy hop, swing, modern jive,
  kizomba, cumbia, merengue, and others)
- Individual dance moves and patterns
- Technique breakdowns and body mechanics
- Dance venues, studios, and practice spaces
- Community events, socials, and workshops
- Instructor notes and lesson summaries
- Dance organizations and communities
- Twin Cities dance scene information

Belongs elsewhere:

- OneReason business operations -> `onereason`
- Public dance information -> `pub`
- Development and technical notes -> `dev`
- Personal notes -> `priv`

## Entity types

This KEG uses 12 [entity types](../6). See the
[entity selection guide](../5) for a decision tree on choosing the right
entity for a new note.

| Group | Entities |
|-------|----------|
| Meta | [entity](../6), [system](../7) |
| Knowledge | [concept](../8), [reference](../9), [guide](../10), [article](../11) |
| People/Places | [person](../12), [place](../13), [event](../14), [organization](../15) |
| Dance | [move](../16) |
| Supporting | [draft](../17) |

## Tagging conventions

- Tags are lowercase and hyphen-separated.
- Use `dance` on system and canonical notes about this KEG.
- Use `canonical` for authoritative reference notes.
- Use entity type names as tags on entity definition notes.
- Dance style tags: `salsa`, `bachata`, `lindy-hop`, `swing`,
  `modern-jive`, `kizomba`, `cumbia`, `merengue`.
- Location tag: `twin-cities`.

## Cross-KEG links

| Alias | Purpose |
|-------|---------|
| `pub` | Public zettelkasten -- general non-dance content |
| `onereason` | OneReason business operations (scope boundary) |
| `dev` | Development notes (scope boundary) |

## Related

- [System: Landing page - dance](../1)
- [Entity: Entity note structure (entity)](../6)
- [System: Markdown style guide - dance](../3)
- [System: Interlinking best practices - dance](../4)
- [System: Entity selection guide - dance](../5)