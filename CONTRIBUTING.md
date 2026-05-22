# Contributing to KiwiFS documentation

Thank you for improving the docs at [docs.kiwifs.com](https://docs.kiwifs.com).

## Before you edit

1. Read [AGENTS.md](./AGENTS.md) — terminology, tone, and what not to document (internal implementation).
2. Verify behavior against the [kiwifs/kiwifs](https://github.com/kiwifs/kiwifs) source or a running server.
3. Use **KiwiFS** in prose; `kiwifs` only in CLI/code examples.

## Local development

```bash
npm i -g mint
cd kiwi/docs
mint dev
```

Preview at `http://localhost:3000`. Check links:

```bash
mint broken-links
```

## Adding a page

1. Create `path/to/page.mdx` with YAML frontmatter (`title`, `description`, `icon`).
2. Register the page in `docs.json` under the correct group.
3. Link from related pages with Mintlify paths (e.g. `/concepts/mcp`).

## Pull requests

- One logical topic per PR when possible.
- Include curl examples for new API endpoints.
- Do not document unreleased hosted services unless explicitly marked as preview.

## Edit on GitHub

You can also use the **Edit** button on any published page to propose changes directly in the docs repository.
