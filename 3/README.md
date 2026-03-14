# System: Markdown style guide - dance

Canonical markdown conventions for all notes in the dance KEG. Every note
must follow these rules so content renders consistently and tooling
(indexes, parsers, doctor checks) works correctly. Adapted from the
[dev Markdown style guide](keg:dev/3).

## Headings

- **H1** (`# Title`) -- exactly one per note, first line of `README.md`.
  Must be plain text with no markdown links, no inline code, no emphasis.
- **H2** (`## Section`) -- top-level sections. Use sentence case.
- **H3** (`### Subsection`) -- subtopics within a section.
- **H4-H6** -- avoid unless nesting is genuinely needed.
- Leave one blank line before and after every heading.

## Lead paragraph

Every note must have a lead paragraph -- one to three sentences immediately
after the H1 that summarise the note's purpose. This is used by indexes
and search results. Do not start a note with a heading or list after the
H1.

## Links

### Syntax

- **Internal KEG links**: `[anchor text](../NODEID)` -- always include
  descriptive anchor text.
- **Cross-KEG links**: `[anchor text](keg:ALIAS/NODEID)` -- same anchor
  text rule applies.
- **External links**: standard markdown `[text](https://...)`.
- **No links in H1** -- title must remain plain text.

### Best practices

1. Link first meaningful mention of a concept in each major section, not
   every repeated occurrence.
2. Prefer internal KEG links for KEG concepts before reaching for external
   URLs.
3. Use descriptive anchor text that names the destination concept -- avoid
   generic words like "this" or "here".
4. Keep `## Related` focused on the closest supporting notes (at least
   three), not a large dump of tangentially related nodes.
5. Do not duplicate the same link repeatedly within one section.
6. Keep link text current -- update anchor text when a target note's title
   changes.

## Lists

- Use `-` for unordered lists (not `*` or `+`).
- Use `1.` for ordered lists (let markdown handle numbering).
- Indent nested lists with four spaces.

## Code

- **Inline code**: single backticks for commands, file names, and short
  expressions.
- **Fenced code blocks**: triple backticks with a language identifier.
- Do not use indented code blocks. Always use fences.

## Emphasis

- **Bold** (`**text**`) -- for key terms on first introduction or critical
  warnings.
- _Italic_ (`*text*`) -- for titles of external works or slight emphasis.
- Do not combine bold and italic. Do not use emphasis in headings.

## Tables

- Use tables for structured comparisons and reference data.
- Align columns with pipes and dashes. Include a header row.
- Keep cell content short.

## Images

- Store images in `<node>/images/` (not the node root).
- Reference as `![alt text](./images/filename.jpg)`.
- Always include meaningful alt text.

## Metadata

- `meta.yaml` -- user-facing tags, entity type, title.
- File names must be exact: `meta.yaml` (not `meta.yml`).

## Whitespace and line length

- One blank line between sections, paragraphs, and before/after code
  blocks.
- No trailing whitespace.
- Wrap prose at 80-120 characters for readability.

## Related

- [System: operating reference - dance](../2)
- [Entity: Entity note structure (entity)](../6)
- [System: Interlinking best practices - dance](../4)