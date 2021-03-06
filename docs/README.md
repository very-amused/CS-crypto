cs-crypto / [Exports](modules.md)

# CS-crypto
A comprehensive, simple, and secure wrapper around the native WebCrypto API. The core of CSplan's client-side cryptography.

[![Tests](https://img.shields.io/github/workflow/status/very-amused/cs-crypto/Tests?label=Tests&logo=github&style=flat-square)](https://github.com/very-amused/CS-crypto/actions?query=workflow%3ATests)
[![NPM](https://img.shields.io/npm/v/cs-crypto?color=darkred&logo=npm&style=flat-square)](https://www.npmjs.com/package/cs-crypto)

## Documentation
For documentation, see [docs](docs/globals.md). This documentation is automatically built using TypeDoc and [typedoc-plugin-markdown](https://www.npmjs.com/package/typedoc-plugin-markdown).

## Package Managers
[cs-crypto on Yarn](https://yarn.pm/cs-crypto)

[cs-crypto on NPM](https://www.npmjs.com/package/cs-crypto)

Install using yarn:
```sh
yarn add cs-crypto
```
Install using npm:
```sh
npm install cs-crypto
```

## Distributed Builds
These builds are pulled from the latest npm package and hosted across multiple awesome automated CDNs for npm packages. Although the minified version of cs-crypto only clocks in at 1.5kb gzipped currently, using a CDN in production is still encouraged to facilitate best practices of caching and localized distribution for end users.

The ESM build is preferred if you only need to target modern browsers, this build utilizes the latest js language features. If you need to support browsers without ESM support, an IIFE build is also offered. Both of these builds are bundled as non-transpiled es2019 javascript. If you need to support anything older than that, the only option is to install using a package manager (as shown above) and transpile yourself.

If self-hosting is still absolutely necessary or preferred, you can always download one of these builds and host on your own server/CDN.

### Unpkg
- ESM: https://unpkg.com/cs-crypto@latest/dist/cs-crypto.esm.min.js
- IIFE: https://unpkg.com/cs-crypto@latest/dist/cs-crypto.min.js

### jsDelivr
- ESM: https://cdn.jsdelivr.net/npm/cs-crypto@latest/dist/cs-crypto.esm.min.js
- IIFE: https://cdn.jsdelivr.net/npm/cs-crypto@latest/dist/cs-crypto.min.js
