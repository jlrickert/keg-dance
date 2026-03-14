# System: Interlinking best practices - dance

Canonical interlinking rules for the dance KEG. Every note must follow
these conventions so graph traversal, backlinks, and discovery remain
useful as the KEG grows. Adapted from the
[dev interlinking best practices](keg:dev/5).

## Link syntax

- **Internal links**: `[anchor text](../NODEID)` -- always include
  descriptive anchor text. Bare `../NODEID` without link text is not valid.
- **Cross-KEG links**: `[anchor text](keg:ALIAS/NODEID)` -- same anchor
  text rule applies.
- **External links**: standard markdown `[text](https://...)`.
- **Node-local assets**: `[anchor text](./assets/FILENAME)` -- for file
  attachments stored in the node's `assets/` subdirectory.
- **Node-local images**: `![alt text](./images/FILENAME)` -- for images
  stored in the node's `images/` subdirectory.
- **No links in H1** -- the title line must remain plain unlinked text.

## Core rules

1. Link the first meaningful mention of a concept in each major section,
   not every repeated occurrence.
2. Prefer internal KEG links for KEG concepts before reaching for external
   URLs.
3. Use descriptive anchor text that names the destination concept -- never
   generic words like "this" or "here".
4. Keep `## Related` focused on the closest supporting notes (at least
   three), not a large dump.
5. Do not duplicate the same link repeatedly within one section.
6. Keep link text current -- update anchor text when a target note's title
   changes.
7. Node-local file references must use `./assets/` or `./images/` prefix.

## Cross-KEG linking

This KEG links to the `pub` KEG for non-dance content. Dance content
now lives locally:

- [Partner dancing (dancing)](../40) -- partner dancing overview
- [Place: Onereason dance studio (onereason)](../25) -- studio information
- [Salsa (salsa)](../26), [Bachata (bachata)](../27),
  [Lindy hop (lindy)](../24) -- style overviews

Use cross-KEG links when referencing [concepts](../8) or
[references](../9) that live in another KEG rather than duplicating
content. Link to `keg:onereason` for business operations context.

## Interlinking workflow

1. **Baseline** -- read the note, check backlinks, search for targets.
2. **Identify** link-worthy phrases -- [moves](../16),
   [concepts](../8), [people](../12), [places](../13),
   [events](../14), [organizations](../15) that have nodes.
3. **Apply** links using the syntax above. Prioritize first meaningful
   mention per section.
4. **Strengthen** `## Related` with at least three relevant references.
5. **Validate** -- re-read the note, confirm links resolve.

## Anti-patterns

- Linking generic words ("this", "here", "see above").
- Adding markdown links in H1/title text.
- Adding unrelated links just to increase link count.
- Repeating the same link multiple times in one section.
- Leaving outdated anchor text after a target note title changed.
- Leaving important domain or entity phrases unlinked.
- Using bare filenames instead of `./assets/` or `./images/` prefix.

## Related

- [System: operating reference - dance](../2)
- [System: Markdown style guide - dance](../3)
- [Entity: Entity note structure (entity)](../6)