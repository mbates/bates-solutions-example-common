# Microservices Example - Common Components

## Publishing to NPM

First (manual ) publish to `npm` should specify if the package will be public

`npm publish --access public`

## Github

Add github Action secret `NPM_TOKEN`

## Versioning

Github workflow will only update minor version.

For hotfixes (patch version) and breaking changes (major version), manually publish an update.

(this can be automated with `semver`)
