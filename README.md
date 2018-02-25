# monorepo

This is a scaffold for a node package monorepo using yarn workspaces.

It includes:
* Babel
* ESLint
* Flow
* Prettier

To use it, clone the repo and then remove the `.git` directory:
```sh
git clone https://github.com/suchipi/monorepo.git
cd monorepo
rm -rf .git
git init
```

To build all packages, run `yarn build` at the top level. To test all packages, run `yarn test`. To build all packages, watch for file changes, and automatically re-build, run `yarn build:watch`.
