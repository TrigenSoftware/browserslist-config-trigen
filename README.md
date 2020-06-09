# browserslist-config-trigen

[![NPM version][npm]][npm-url]
[![Node version][node]][node-url]
[![Build status][build]][build-url]
[![Dependabot badge][dependabot]][dependabot-url]

[npm]: https://img.shields.io/npm/v/browserslist-config-trigen.svg
[npm-url]: https://npmjs.com/package/browserslist-config-trigen

[node]: https://img.shields.io/node/v/browserslist-config-trigen.svg
[node-url]: https://nodejs.org

[build]: http://img.shields.io/travis/com/TrigenSoftware/browserslist-config-trigen.svg
[build-url]: https://travis-ci.com/TrigenSoftware/browserslist-config-trigen

[dependabot]: https://api.dependabot.com/badges/status?host=github&repo=TrigenSoftware/browserslist-config-trigen
[dependabot-url]: https://dependabot.com/

Trigen's browserslist config.

## Install

```bash
npm i -D browserslist-config-trigen
# or
yarn add -D browserslist-config-trigen
```

## Configure

Create `.browserslistrc` with next content:

```
extends browserslist-config-trigen
```

### Other configs

There are other configs for different platforms:

| Config | Description |
|--------|-------------|
| browserslist-config-trigen/browsers | Only browsers. |
| browserslist-config-trigen/node | Only NodeJS. |
