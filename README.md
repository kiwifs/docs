# KiwiFS documentation

Public documentation for [KiwiFS](https://github.com/kiwifs/kiwifs), built with [Mintlify](https://mintlify.com).

Published at [docs.kiwifs.com](https://docs.kiwifs.com).

## Local preview

```bash
npm i -g mint
cd kiwi/docs
mint dev
```

Open `http://localhost:3000`.

## Contributing

Read [AGENTS.md](./AGENTS.md) for terminology, style, and scope. Edit MDX pages and update `docs.json` when adding routes.

```bash
mint broken-links
```

## Repository layout

| Path | Purpose |
| --- | --- |
| `*.mdx` | Documentation pages |
| `docs.json` | Navigation and site config |
| `AGENTS.md` | Authoring guide for humans and agents |
| `concepts/` | Product concepts |
| `guides/` | How-to guides (web UI, protocols, FAQ, examples) |
| `api/` | REST API reference |
| `cli/` | CLI reference |
| `import/` / `export/` | Data movement |
| `deploy/` | Docker, Kubernetes, Go embed |

Source-of-truth behavior lives in the [kiwifs/kiwifs](https://github.com/kiwifs/kiwifs) repository; these docs describe the public API, CLI, and configuration only.
