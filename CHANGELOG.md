# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- next-header -->

## [Unreleased] - ReleaseDate

## [1.2.2] - 2022-10-10
- Add manpage printing via `--print-manpage`
- Add completions printing via `--print-completions`

## [1.2.1] - 2022-10-10
- Enable multiple parallel decryptions to run in bruteforce [#414](https://github.com/svenstaro/genact/pull/414) (thanks @equal-l2)

## [1.2.0] - 2022-10-09
- Add bruteforce module [#408](https://github.com/svenstaro/genact/pull/408) (thanks @equal-l2)

## [1.1.1] - 2022-09-13
- Fixed julia module logo in web version [#400](https://github.com/svenstaro/genact/pull/392) (thanks @FedericoStra)
- Update deps

## [1.1.0] - 2022-09-13
- Use musl binaries inside container image
- Add julia module [#392](https://github.com/svenstaro/genact/pull/392) (thanks @FedericoStra)
- Fix wasm version

## [1.0.2] - 2022-09-10
- Use less CPU when printing large strings
- Improve release flow

## [1.0.1] - 2022-09-09
- Update deps
- Fix Docker Hub image publishing

## [1.0.0] - 2022-09-07
- Add a bunch more extensions and file formats
- Add rkhunter module [#381](https://github.com/svenstaro/genact/pull/381) (thanks @Kovah)

## [0.12.0] - 2022-02-21
- Add Ansible module [#301](https://github.com/svenstaro/genact/issues/301)

## [0.11.0] - 2021-03-19
- Add docker_build module [#103](https://github.com/svenstaro/genact/pull/103) (thanks @Kovah)
- Refactored modules to implement a common trait

## [0.10.0] - 2020-08-27
- Add `--exit-after-modules` options which can be used to make genact exit after running that many modules

## [0.9.0] - 2020-08-10
- Add global speed [#132](https://github.com/svenstaro/genact/issues/132)

## [0.8.1] - 2020-08-10
- Refactor entrypoint, modules, and file structure
- Use structopt instead of clap which should give better errors
- Improve wasm download size

## [0.8.0] - 2020-08-05
- Enhance download module
- Rewrite web version using wasm-bindgen

<!-- next-url -->
[Unreleased]: https://github.com/svenstaro/genact/compare/v1.2.2...HEAD
[1.2.2]: https://github.com/svenstaro/genact/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/svenstaro/genact/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/svenstaro/genact/compare/v1.1.1...v1.2.0
[1.1.1]: https://github.com/svenstaro/genact/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/svenstaro/genact/compare/v1.0.2...v1.1.0
[1.0.2]: https://github.com/svenstaro/genact/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/svenstaro/genact/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/svenstaro/genact/compare/v0.12.0...v1.0.0
[0.12.0]: https://github.com/svenstaro/genact/compare/v0.11.0...v0.12.0
[0.11.0]: https://github.com/svenstaro/genact/compare/v0.10.0...v0.11.0
[0.10.0]: https://github.com/svenstaro/genact/compare/v0.9.0...v0.10.0
[0.9.0]: https://github.com/svenstaro/genact/compare/v0.8.1...v0.9.0
[0.8.1]: https://github.com/svenstaro/genact/compare/v0.8.0...v0.8.1
[0.8.0]: https://github.com/svenstaro/proby/compare/0.7.0...v0.8.0
