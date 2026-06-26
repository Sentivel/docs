# Sentivel documentation: project instructions

The public docs for Sentivel (a unified reliability platform: monitoring, status
pages, and dependency/cascade watching). Built on [Mintlify](https://mintlify.com):
MDX pages with YAML frontmatter, config in `docs.json`. The API reference is
generated from the live OpenAPI spec at `https://www.sentivel.com/api/v1/openapi.json`.

- Mintlify product knowledge (components, config) via the Mintlify MCP server
  `https://mcp.mintlify.com`, or query docs via `https://www.mintlify.com/docs/mcp`.

## Voice: read this first

Write like a senior engineer explaining to a peer. **Never like AI.** The full
checklist is in `STYLE.md` (the canonical voice guide). The short version:

- Second person, imperative. Instruct, don't narrate.
- Short declarative sentences (~8–15 words). One idea per sentence. Active voice.
- Context, then action. No preamble; don't restate the heading.
- Task-based, sentence-case headings ("Add a monitor", not "Configuration").
- Real, runnable code; show the actual response.
- Bold for UI elements (Click **Settings**); code formatting for files, commands,
  paths.
- **Banned (AI tells):** powerful, robust, seamless, effortless, comprehensive,
  leverage, unlock, elevate, supercharge, easily, simply, just, "feel free to",
  "delve", "dive in", em dashes, Title Case Everything. See `STYLE.md` for the
  full list. Read every page aloud and cut what doesn't change the meaning.

## Terminology

- **Workspace**, not "project" or "organization" (in user-facing copy).
- **Member**, not "user".
- **Component** = a unit shown on a status page. **Monitor** = a check that drives
  a component's status. **Status page** = the public page.
- **Cascade** = a depended-on provider's incident flagging your component.
- **Upstream advisory** = the plain-English message cascade posts on your page.

## Content boundaries

- Document only shipped behaviour. Never overclaim. (Example: checks run from a
  single region today; don't imply multi-region consensus is the default.)
- No novelty claims ("first", "only", "we invented"). Others do parts of cascade.
- Don't document internal staff/admin tooling or unreleased features. Billing is
  not documented until it ships.
- Honest copy: state what is true, promise nothing the product can't keep.
