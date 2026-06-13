# Changelog

## 7.0.0

### Major Changes

- [`a07d261`](https://github.com/dotansimha/graphql-code-generator-community/commit/a07d2610cdd0c3a64bbbc2b4ceaaa272fe0329e6)
  Thanks [@davedbase](https://github.com/davedbase)! - Added `solid-urql` and `solidstart-urql`
  plugins to the codegen library. The plugins generate fully typed Solid primitives for URQL,
  including `createQuery`, `createMutation`, and `createSubscription`. Both versions for Solid
  (client-side) and SolidStart (SSR framework) are provided.

## [1.0.0] - 2026-01-12

### Added

- Initial release of GraphQL Code Generator plugin for SolidJS and URQL
- Support for generating typed `createQuery` wrappers
- Support for generating typed `createMutation` wrappers
- Support for generating typed `createSubscription` wrappers
- Configuration option `withPrimitives` to enable/disable primitive generation
- Configuration option `urqlImportFrom` to customize import source
- Full TypeScript support with proper type inference
- Comprehensive documentation and examples

### Features

- Generates wrapper functions around solid-urql primitives
- Proper handling of required vs optional variables
- Compatible with @urql/core and solid-urql
- Follows SolidJS conventions (uses `create*` naming instead of `use*`)
