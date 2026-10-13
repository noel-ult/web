# web source reference


Source reviewed: [`12c13feafb71`](https://github.com/noel-ult/web/commit/12c13feafb715beaf458f4c08a0a6c0e8fde195a).

This reference records the checked-in source, scripts, configuration names, and route declarations. It is a navigation aid; service availability and successful test execution require separate verification.

## Package commands

Run each command in the directory containing its package manifest. A declared script is not necessarily a passing check; guides call out placeholders and known mismatches.

### package.json

| Script | Shell command |
| --- | --- |
| `dev` | `next dev` |
| `build` | `next build` |
| `start` | `next start` |
| `lint` | `eslint` |

Manifest: [package.json](../package.json).

## File-based pages and handlers

- [app/page.js](../app/page.js)

## Existing documentation

Historical plans/reports describe their own revision; use current source when they disagree.

- [AGENTS.md](../AGENTS.md)
- [CLAUDE.md](../CLAUDE.md)
- [README.md](../README.md)

## Source and configuration map

Generated lockfiles, binary assets, compiled output, vendored dependencies, and cached bytecode are omitted. Test files remain listed so coverage can be located.

- [app/globals.css](../app/globals.css)
- [app/layout.js](../app/layout.js)
- [app/page.js](../app/page.js)
- [app/page.module.css](../app/page.module.css)
- [eslint.config.mjs](../eslint.config.mjs)
- [jsconfig.json](../jsconfig.json)
- [next.config.mjs](../next.config.mjs)
- [package.json](../package.json)
