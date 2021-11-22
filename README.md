# Installation

Require "node": "^14.16.0 || ^16.11.0 || ^17.0.0"


Locally install pnpm 

`npm install -g pnpm`

## TODO
- [ ] Dockerise

## Known issues

### Nuxt
Nuxt 2 & Nuxt 3 do not support pnpm as package manager, so symlinked `node_modules` structure does not work.
* `pnpm i --shamefully-hoist` to install deps see https://github.com/nuxt/create-nuxt-app/issues/367