# Next.js webpage starter

A small Next.js App Router starter whose homepage says “New Webpage creation Via Github.” The package name is `thepoolapp`, but no pooling product, authentication, or backend API is implemented in this branch.

## Run

```sh
npm ci
npm run dev
```

Visit http://localhost:3000. Use a Node.js version compatible with the pinned Next.js version in `package.json`; the repository does not declare its own Node engine range.

## Files and commands

- `app/page.js`: homepage content and links.
- `app/layout.js`: root page layout and font configuration.
- `app/page.module.css`: homepage styles.
- `app/globals.css`: global styles.
- `public/`: static image assets.
- `next.config.mjs`: Next.js configuration.

`npm run lint` runs ESLint. `npm run build` creates the production build; `npm start` serves that build. No environment variables or application database are required by the current source, and no automated tests are tracked. Font fetching during a build may require network access.

Read `AGENTS.md` before changing Next.js code. After edits, run lint/build and check the homepage links and images. Deploy using the repository root on a host that supports this Next.js version.

## More documentation

- [Source, command, and configuration reference](docs/REFERENCE.md)
- [Contributing](CONTRIBUTING.md)

<!-- developer-handbook-20261028 -->
[Source reference](docs/REFERENCE.md) · [Verification and operations](docs/OPERATIONS.md)
<!-- /developer-handbook-20261028 -->
