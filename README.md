# @x12i/continuix-docs usage example

Continuix docs knowledge SDK — install as a devDependency only. Catalog, use cases, and markdown packs for humans and agents.

This consuming application demonstrates **list the bundled guides and read a use case** using the published npm package, pinned to `1.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

This is a documentation knowledge SDK. It is installed as a development dependency. The example lists its books and use cases, then reads the first available use-case guide from the package.

## When to use the package

- Install @x12i/continuix-docs as a development dependency so the product guides and package index are available to developers and coding assistants.
- Read the bundled continuix documentation or use-case catalog without requiring a live documentation website.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/continuix-docs)
- [Implementation monorepo](https://github.com/x12i/continuix)
- [Reviewed package source](https://github.com/x12i/continuix/tree/5a16693de320d31465a2fe6fad3468546b489fed/continuix-docs/packages/continuix-docs)

The current source snapshot has a different manifest version from the pinned npm dependency. This example is validated against the installed npm release.

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
