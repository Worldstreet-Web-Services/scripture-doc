# Scriipture docs

Documentation site for [Scriipture](https://github.com/Worldstreet-Web-Services/scripture) — a TypeScript-to-Solidity transpiler with a built-in 9-gate security pipeline, browser-wallet deploys, and multi-chain support.

Live site: [https://tsionark.mintlify.app](https://tsionark.mintlify.app)

Built with [Mintlify](https://mintlify.com).

## Structure

- `introduction.mdx`, `install.mdx`, `quickstart.mdx` — getting started
- `concepts/` — decorators, type mapping, security pipeline, browser wallet, supported chains
- `commands/` — one page per CLI subcommand
- `guides/` — task-oriented walkthroughs
- `reference/` — library API and all-commands index
- `docs.json` — navigation, theme, and site config

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the dev server from the repo root (where `docs.json` lives):

```bash
mint dev
```

Preview at `http://localhost:3000`.

## Publishing

Pushes to the default branch deploy automatically via the Mintlify GitHub app.

## Contributing

Content lives in `.mdx` files. Edit the relevant page, run `mint dev` to preview, then open a PR. For upstream Scriipture changes (new CLI flags, decorators, chains), update the matching page under `commands/`, `concepts/`, or `reference/`.

## Links

- Scriipture repo: [https://github.com/Worldstreet-Web-Services/scripture](https://github.com/Worldstreet-Web-Services/scripture)
- npm package: [https://www.npmjs.com/package/scriipture](https://www.npmjs.com/package/scriipture)