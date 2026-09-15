# Changelog

## [0.2.0](https://github.com/amritk/galaxy-staging-rs/compare/v0.1.0...v0.2.0) (2026-09-15)


### Features

* **api:** initial SDK generation ([5ba8e11](https://github.com/amritk/galaxy-staging-rs/commit/5ba8e116c556d0eac6ac1b358a29679cf4c68e65))


### Chores

* **api:** update generated SDK content ([4d57c9f](https://github.com/amritk/galaxy-staging-rs/commit/4d57c9fbcb12be5b85fb5bf3a2c0ca32d7de4a8a))

## Changelog

All notable changes to `demo-api-scalar-galaxy` are documented here. Release
tooling appends a section per released version below.

## Unreleased

- Initial generation of the `demo-api-scalar-galaxy` SDK.
- Response-only models are marked `#[non_exhaustive]`, so new response
  fields can be added in future versions without a breaking release;
  request models stay literally constructible.
