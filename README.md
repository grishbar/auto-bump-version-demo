# auto-bump-version demo

Simple React + Vite app with [`@niazox/auto-bump-version`](https://www.npmjs.com/package/@niazox/auto-bump-version).

Each new commit against `origin/main` bumps the patch version in `package.json` (Husky pre-commit). Pull requests also check the version in GitHub Actions.

```bash
npm install
npm run dev
```
