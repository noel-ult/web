# web: verification and operations

Reviewed against [default-branch commit ecfbe3298985](https://github.com/noel-ult/web/commit/ecfbe329898598cca969c30c774a300444d01064) on 2026-10-28. Start with the [developer guide](../README.md) for installation and architecture, and the [source reference](REFERENCE.md) for exact scripts, configuration readers, routes, and source locations.

## Next starter

Run declared lint/build commands and check the homepage, assets, navigation links, and font loading at desktop/mobile widths.

These are acceptance scenarios for a maintainer to run in the documented environment. Their inclusion is not a claim that live integrations or production credentials were tested during this documentation update.

## Deployment and failure diagnosis

Use a Node host compatible with the pinned Next version. Build network access may be needed for fonts; there is no application database to configure.

## Maintaining the contract

When behavior changes, update the guide and examples in the same PR. Check the entry point and working directory before copying commands. Use the linked source readers to distinguish build-time configuration from process environment. For failures, capture the first application error, runtime version, selected mode, and redacted configuration names before later proxy or port errors.

Keep changes tied to evidence: a declared command is not proof it passes, a process health response is not a successful end-to-end workflow, and a historical report describes its own revision. Record actual check results and any unavailable external services in the PR.
