# KiwiFS documentation project instructions

## About this project

- Documentation site for [KiwiFS](https://github.com/kiwifs/kiwifs), built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "KiwiFS" (capital K, i, F, S), never "kiwifs" in prose (lowercase is fine in code/CLI examples)
- Use "knowledge base" not "wiki" or "database" when referring to the content store
- Use "knowledge server" when describing the product category
- Use "agent" not "AI" or "LLM" when referring to the consumer of the filesystem interface
- Use "web UI" not "frontend" or "dashboard"
- Use "wiki links" not "wikilinks" or "internal links"
- Use "frontmatter" not "metadata" when referring to YAML headers in markdown files

## Style preferences

- Active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Show curl examples for API endpoints
- Use Tabs component for alternative approaches (e.g., CLI vs REST vs MCP)
- Use CardGroup for navigation between related pages
- Use AccordionGroup for reference lists (CLI flags, function lists)
- No emojis

## Content boundaries

- Document the public API, CLI, and configuration — not internal implementation details
- Don't document unstable or experimental features without marking them as such
- Keep the source of truth in the source code; docs describe behavior, not implementation
