# Pre-configured svelte template

## Set-up:

- [Vite](https://vitejs.dev/) — Native ESM fast build tool
- [ESLint](https://eslint.org/) — JS code linter with [airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) config
- [Prettier](https://prettier.io/) — Code formatter. Configured with svelte & eslint support
- [Husky](https://github.com/typicode/husky) — Git hooks manager
- [commitlint](https://commitlint.js.org/) — Configuration-based commit linter with [Conventional Commits](https://www.conventionalcommits.org/) specification

## How to run

It is recommended to use the [pnpm](https://pnpm.io/) manager

1. `pnpx degit yukioru/svelte-ready-template my-app`
2. `cd my-app`
3. `pnpm i`
4. `pnpm dev`
