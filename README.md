# monorepo

This is a scaffold for a node package monorepo using yarn workspaces.

It includes:
* Babel
* ESLint
* Flow
* Prettier

## Installation

To use it, clone the repo and then remove the `.git` directory:
```sh
git clone https://github.com/suchipi/monorepo.git
cd monorepo
rm -rf .git
git init
```

If you are on Node 8 or higher, you can also use [`degit`](https://www.npmjs.com/package/degit):
```sh
npx degit suchipi/monorepo my-project
```

## Usage

To build all packages, run `yarn build` at the top level. To test all packages, run `yarn test`. To build all packages, watch for file changes, and automatically re-build, run `yarn build:watch`.

## License

MIT
