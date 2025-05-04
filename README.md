# snd-nextjs-app-monorepo

Welcome to [SuperNice Dev](https://www.supernice-dev.com/en) Next.js app monorepo.

This is a monorepo for [snd-nextjs-app](https://github.com/SuperNiceDev/snd-nextjs-app) that uses [snd-react-lib](https://github.com/SuperNiceDev/snd-react-lib) and [snd-strapi-cms](https://github.com/SuperNiceDev/snd-strapi-cms).


## Setup

- install Node.js:
https://nodejs.org/en/download


- install yarn:
https://yarnpkg.com/getting-started/install
https://classic.yarnpkg.com/en/docs/install#mac-stable


- init all git submodules:
```sh
git submodule update --init --recursive
```

- install node modules:
```sh
yarn
```

- setup [snd-nextjs-app README](./src/apps/snd-nextjs-app/README.md).

- see [package.json](./package.json) and run the needed scripts.

- see [snd-react-lib README](./src/packages/snd-react-lib/README.md)
