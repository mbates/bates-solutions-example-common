# Microservices : Example Common Components

Common components to use with `bates-solutions-example` project

This repository is part of a this simple microservices example group:
 * [Microservices : Monorepo Example](https://github.com/mbates/bates-solutions-example)
 * [Microservices : Example Common Components](https://github.com/mbates/bates-solutions-example-common)
 * [Microservices : Global Common Components](https://github.com/mbates/bates-solutions-common)


## Publishing to NPM

First (manual ) publish to `npm` should specify if the package will be public

`npm publish --access public`

## Github

Add github Action secret `NPM_TOKEN`

## Versioning

Github workflow will only update minor version.

For hotfixes (patch version) and breaking changes (major version), manually publish an update.

(this can be automated with `semver`)
