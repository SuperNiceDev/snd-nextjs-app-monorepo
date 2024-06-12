# install, development and build

install Node.js
https://nodejs.org/en/download

install yarn
https://yarnpkg.com/getting-started/install
https://classic.yarnpkg.com/en/docs/install#mac-stable

--------------------------------------------

1. init all git submodules
```sh
git submodule update --init --recursive
```

2. install dependencies
```sh
yarn
```

3. fix strapi sharp dependency error
```sh
yarn workspace snd-strapi-cms add -D sharp --ignore-engines
```

4. got to ```./package.json``` and run the needed scripts