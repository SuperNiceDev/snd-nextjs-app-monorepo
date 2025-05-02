# install, development and build

install Node.js
https://nodejs.org/en/download

install yarn
https://yarnpkg.com/getting-started/install
https://classic.yarnpkg.com/en/docs/install#mac-stable

--------------------------------------------

1. Init all git submodules
```sh
git submodule update --init --recursive
```

2. Install dependencies
```sh
yarn
```

3. See ```./package.json``` and run the needed scripts

--------------------------------------------

Readme:
[snd-nextjs-app](./src/apps/snd-nextjs-app/README.md)
[snd-strapi-cms](./src/apps/snd-strapi-cms/README.md)
[snd-react-lib](./src/packages/snd-react-lib/README.md)