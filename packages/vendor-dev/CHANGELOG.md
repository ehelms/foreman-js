# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0-next-storybook-v6.0](https://github.com/theforeman/foreman-js/compare/v6.1.0-next.1...v7.0.0-next-storybook-v6.0) (2020-11-17)


### Features

* **stories:** update Storybook to v6 ([8fb4134](https://github.com/theforeman/foreman-js/commit/8fb4134323c9e103b848bcfbc1c4d9170fd02dca))


### BREAKING CHANGES

* **stories:** @storybook/addon-knobs, @storybook/addon-actions,
and @storybook/addon-storysource are no longer re-exported
from @theforeman/stories.  Going forward, import these items
directly: e.g. `import { withKnobs } from @storybook/addon-knobs`
instead of `import { withKnobs } from @theforeman/stories`.
Deprecation error messages have been added where appropriate.
* **stories:** The Preview component has been renamed to Canvas.
* **stories:** The Props component has been renamed to ArgsTable.
* **stories:** Custom separators are no longer supported in story titles.
Instead of `title: 'Components|DiffView'` you must write `title: 'Components/DiffView'`.





# [6.1.0-next.1](https://github.com/theforeman/foreman-js/compare/v6.1.0-next.0...v6.1.0-next.1) (2020-11-10)

**Note:** Version bump only for package @theforeman/vendor-dev





# [6.1.0-next.0](https://github.com/theforeman/foreman-js/compare/v6.0.1-next.0...v6.1.0-next.0) (2020-11-10)

**Note:** Version bump only for package @theforeman/vendor-dev





## [6.0.1-next.0](https://github.com/theforeman/foreman-js/compare/v6.0.0...v6.0.1-next.0) (2020-11-09)

**Note:** Version bump only for package @theforeman/vendor-dev





# [6.0.0](https://github.com/theforeman/foreman-js/compare/v4.15.2...v6.0.0) (2020-11-04)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.15.2](https://github.com/theforeman/foreman-js/compare/v4.15.1...v4.15.2) (2020-10-12)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.15.1](https://github.com/theforeman/foreman-js/compare/v4.15.0...v4.15.1) (2020-09-07)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.15.0](https://github.com/theforeman/foreman-js/compare/v4.14.6...v4.15.0) (2020-09-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.6](https://github.com/theforeman/foreman-js/compare/v4.14.5...v4.14.6) (2020-09-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.5](https://github.com/theforeman/foreman-js/compare/v4.14.4...v4.14.5) (2020-09-01)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.4](https://github.com/theforeman/foreman-js/compare/v4.14.3...v4.14.4) (2020-09-01)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.3](https://github.com/theforeman/foreman-js/compare/v4.14.2...v4.14.3) (2020-08-27)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.2](https://github.com/theforeman/foreman-js/compare/v4.14.1...v4.14.2) (2020-08-17)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.14.1](https://github.com/theforeman/foreman-js/compare/v4.14.0...v4.14.1) (2020-08-17)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.14.0](https://github.com/theforeman/foreman-js/compare/v4.13.3...v4.14.0) (2020-08-17)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.13.3](https://github.com/theforeman/foreman-js/compare/v4.13.2...v4.13.3) (2020-08-12)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.13.2](https://github.com/theforeman/foreman-js/compare/v4.13.1...v4.13.2) (2020-08-06)


### Bug Fixes

* **eslint-plugin-foreman:** allow linting plugins without foreman ([#190](https://github.com/theforeman/foreman-js/issues/190)) ([3487135](https://github.com/theforeman/foreman-js/commit/348713592614cf11a25adbe5b79a6301e87a71fe))





## [4.13.1](https://github.com/theforeman/foreman-js/compare/v4.13.0...v4.13.1) (2020-08-02)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.13.0](https://github.com/theforeman/foreman-js/compare/v4.12.0...v4.13.0) (2020-08-02)


### Features

* **vendor-dev:** use find-foreman for eslint extraneous dependencies ([ee4fe96](https://github.com/theforeman/foreman-js/commit/ee4fe96072f101f0a18cbc2a2214a5fe2781ef0f)), closes [/github.com/Katello/katello/blob/f9a239d4e42ab95dcf2561f372df00d0cb47c42b/webpack/.eslintrc.js#L36](https://github.com//github.com/Katello/katello/blob/f9a239d4e42ab95dcf2561f372df00d0cb47c42b/webpack/.eslintrc.js/issues/L36)





# [4.12.0](https://github.com/theforeman/foreman-js/compare/v4.11.1...v4.12.0) (2020-07-28)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.11.1](https://github.com/theforeman/foreman-js/compare/v4.11.0...v4.11.1) (2020-07-08)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.11.0](https://github.com/theforeman/foreman-js/compare/v4.10.2...v4.11.0) (2020-07-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.10.2](https://github.com/theforeman/foreman-js/compare/v4.10.1...v4.10.2) (2020-07-01)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.10.1](https://github.com/theforeman/foreman-js/compare/v4.10.0...v4.10.1) (2020-07-01)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.10.0](https://github.com/theforeman/foreman-js/compare/v4.9.0...v4.10.0) (2020-06-30)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.9.0](https://github.com/theforeman/foreman-js/compare/v4.8.0...v4.9.0) (2020-06-30)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.8.0](https://github.com/theforeman/foreman-js/compare/v4.7.1...v4.8.0) (2020-06-16)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.7.1](https://github.com/theforeman/foreman-js/compare/v4.7.0...v4.7.1) (2020-06-16)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.7.0](https://github.com/theforeman/foreman-js/compare/v4.6.0...v4.7.0) (2020-06-10)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.6.0](https://github.com/theforeman/foreman-js/compare/v4.5.0...v4.6.0) (2020-05-19)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.5.0](https://github.com/theforeman/foreman-js/compare/v4.4.0...v4.5.0) (2020-04-26)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.4.0](https://github.com/theforeman/foreman-js/compare/v4.3.0...v4.4.0) (2020-04-26)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.3.0](https://github.com/theforeman/foreman-js/compare/v4.2.1...v4.3.0) (2020-03-23)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.2.1](https://github.com/theforeman/foreman-js/compare/v4.2.0...v4.2.1) (2020-03-15)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.2.0](https://github.com/theforeman/foreman-js/compare/v4.1.0...v4.2.0) (2020-03-15)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.1.0](https://github.com/theforeman/foreman-js/compare/v4.0.9...v4.1.0) (2020-03-12)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.9](https://github.com/theforeman/foreman-js/compare/v4.0.8...v4.0.9) (2020-03-04)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.8](https://github.com/theforeman/foreman-js/compare/v4.0.7...v4.0.8) (2020-02-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.7](https://github.com/theforeman/foreman-js/compare/v4.0.6...v4.0.7) (2020-01-27)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.6](https://github.com/theforeman/foreman-js/compare/v4.0.5...v4.0.6) (2020-01-20)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.5](https://github.com/theforeman/foreman-js/compare/v4.0.4...v4.0.5) (2020-01-13)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.4](https://github.com/theforeman/foreman-js/compare/v4.0.3...v4.0.4) (2020-01-08)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.3](https://github.com/theforeman/foreman-js/compare/v4.0.2...v4.0.3) (2020-01-08)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.2](https://github.com/theforeman/foreman-js/compare/v4.0.1...v4.0.2) (2020-01-05)

**Note:** Version bump only for package @theforeman/vendor-dev





## [4.0.1](https://github.com/theforeman/foreman-js/compare/v4.0.0...v4.0.1) (2020-01-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [4.0.0](https://github.com/theforeman/foreman-js/compare/v3.12.0...v4.0.0) (2020-01-02)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.12.0](https://github.com/theforeman/foreman-js/compare/v3.11.1...v3.12.0) (2019-12-31)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.11.1](https://github.com/theforeman/foreman-js/compare/v3.11.0...v3.11.1) (2019-12-31)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.11.0](https://github.com/theforeman/foreman-js/compare/v3.10.1...v3.11.0) (2019-12-31)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.10.1](https://github.com/theforeman/foreman-js/compare/v3.10.0...v3.10.1) (2019-12-29)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.10.0](https://github.com/theforeman/foreman-js/compare/v3.9.3...v3.10.0) (2019-12-29)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.9.3](https://github.com/theforeman/foreman-js/compare/v3.9.2...v3.9.3) (2019-12-19)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.9.2](https://github.com/theforeman/foreman-js/compare/v3.9.1...v3.9.2) (2019-12-18)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.9.1](https://github.com/theforeman/foreman-js/compare/v3.9.0...v3.9.1) (2019-12-18)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.9.0](https://github.com/theforeman/foreman-js/compare/v3.8.2...v3.9.0) (2019-12-17)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.8.2](https://github.com/theforeman/foreman-js/compare/v3.8.1...v3.8.2) (2019-12-17)


### Bug Fixes

* **env:** add coverage output directory ([91a43b7](https://github.com/theforeman/foreman-js/commit/91a43b7))





## [3.8.1](https://github.com/theforeman/foreman-js/compare/v3.8.0...v3.8.1) (2019-12-15)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.8.0](https://github.com/theforeman/foreman-js/compare/v3.7.2...v3.8.0) (2019-12-12)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.7.2](https://github.com/theforeman/foreman-js/compare/v3.7.1...v3.7.2) (2019-12-12)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.7.1](https://github.com/theforeman/foreman-js/compare/v3.7.0...v3.7.1) (2019-12-12)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.7.0](https://github.com/theforeman/foreman-js/compare/v3.6.4...v3.7.0) (2019-12-11)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.6.4](https://github.com/theforeman/foreman-js/compare/v3.6.3...v3.6.4) (2019-12-11)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.6.3](https://github.com/theforeman/foreman-js/compare/v3.6.2...v3.6.3) (2019-12-09)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.6.2](https://github.com/theforeman/foreman-js/compare/v3.6.1...v3.6.2) (2019-12-08)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.6.1](https://github.com/theforeman/foreman-js/compare/v3.6.0...v3.6.1) (2019-12-08)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.6.0](https://github.com/theforeman/foreman-js/compare/v3.5.2...v3.6.0) (2019-12-08)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.5.2](https://github.com/theforeman/foreman-js/compare/v3.5.1...v3.5.2) (2019-12-05)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.5.1](https://github.com/theforeman/foreman-js/compare/v3.5.0...v3.5.1) (2019-12-05)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.5.0](https://github.com/theforeman/foreman-js/compare/v3.4.0...v3.5.0) (2019-12-05)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.4.0](https://github.com/theforeman/foreman-js/compare/v3.3.2...v3.4.0) (2019-12-04)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.3.2](https://github.com/theforeman/foreman-js/compare/v3.3.1...v3.3.2) (2019-12-02)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.3.1](https://github.com/theforeman/foreman-js/compare/v3.3.0...v3.3.1) (2019-12-01)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.3.0](https://github.com/theforeman/foreman-js/compare/v3.2.2...v3.3.0) (2019-11-26)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.2.2](https://github.com/theforeman/foreman-js/compare/v3.2.1...v3.2.2) (2019-11-24)

**Note:** Version bump only for package @theforeman/vendor-dev





## [3.2.1](https://github.com/theforeman/foreman-js/compare/v3.2.0...v3.2.1) (2019-11-21)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.2.0](https://github.com/theforeman/foreman-js/compare/v3.1.1...v3.2.0) (2019-11-21)


### Features

* **babel:** adds babel package ([e5fc141](https://github.com/theforeman/foreman-js/commit/e5fc141))





## [3.1.1](https://github.com/theforeman/foreman-js/compare/v3.1.0...v3.1.1) (2019-11-18)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.1.0](https://github.com/theforeman/foreman-js/compare/v3.0.0...v3.1.0) (2019-11-17)

**Note:** Version bump only for package @theforeman/vendor-dev





# [3.0.0](https://github.com/theforeman/foreman-js/compare/v2.15.7...v3.0.0) (2019-10-31)


### Features

* **root:** switching deprecated babel/polyfill ([08a6812](https://github.com/theforeman/foreman-js/commit/08a6812))


### BREAKING CHANGES

* **root:** Removed deprecated babe/polyfill and added 'core-js/shim', 'regenerator-runtime/runtime' packages





## [2.15.7](https://github.com/theforeman/foreman-js/compare/v2.15.6...v2.15.7) (2019-10-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.15.6](https://github.com/theforeman/foreman-js/compare/v2.15.5...v2.15.6) (2019-10-06)


### Bug Fixes

* **root:** attempt to fix the lock files update in the CI ([b9dc3cb](https://github.com/theforeman/foreman-js/commit/b9dc3cb))





## [2.15.5](https://github.com/theforeman/foreman-js/compare/v2.15.4...v2.15.5) (2019-10-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.15.4](https://github.com/theforeman/foreman-js/compare/v2.15.3...v2.15.4) (2019-10-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.15.3](https://github.com/theforeman/foreman-js/compare/v2.15.2...v2.15.3) (2019-10-06)


### Bug Fixes

* **root:** attempt to fix the lock files update in the CI ([7a4ac4d](https://github.com/theforeman/foreman-js/commit/7a4ac4d))





## [2.15.2](https://github.com/theforeman/foreman-js/compare/v2.15.1...v2.15.2) (2019-10-06)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.15.1](https://github.com/theforeman/foreman-js/compare/v2.15.0...v2.15.1) (2019-10-06)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.15.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.15.0) (2019-10-04)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.14.4](https://github.com/theforeman/foreman-js/compare/v0.1.0...v2.14.4) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.14.3](https://github.com/theforeman/foreman-js/compare/v0.1.0...v2.14.3) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.14.2](https://github.com/theforeman/foreman-js/compare/v0.1.0...v2.14.2) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.14.1](https://github.com/theforeman/foreman-js/compare/v0.1.0...v2.14.1) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.14.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.14.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.13.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.13.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.12.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.12.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.11.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.11.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.10.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.10.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.9.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.9.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.8.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.8.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.7.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.7.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.6.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.6.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.5.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.5.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.4.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.4.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.3.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.3.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.2.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.2.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.1.0](https://github.com/theforeman/foreman-js/compare/v2.0.1...v2.1.0) (2019-10-03)

**Note:** Version bump only for package @theforeman/vendor-dev





## [2.0.1](https://github.com/theforeman/foreman-js/compare/v2.0.0...v2.0.1) (2019-10-02)

**Note:** Version bump only for package @theforeman/vendor-dev





# [2.0.0](https://github.com/theforeman/foreman-js/compare/v1.7.0...v2.0.0) (2019-10-02)


### Features

* **vendor-core:** update redux to enable hooks ([b3db69d](https://github.com/theforeman/foreman-js/commit/b3db69d)), closes [#27393](https://github.com/theforeman/foreman-js/issues/27393)


### BREAKING CHANGES

* **vendor-core:** update redux to v.4





# [1.7.0](https://github.com/theforeman/foreman-js/compare/v1.6.0...v1.7.0) (2019-09-22)

**Note:** Version bump only for package @theforeman/vendor-dev





# [1.6.0](https://github.com/theforeman/foreman-js/compare/v1.5.0...v1.6.0) (2019-09-16)

**Note:** Version bump only for package @theforeman/vendor-dev





# [1.5.0](https://github.com/theforeman/foreman-js/compare/v1.4.1...v1.5.0) (2019-09-15)

**Note:** Version bump only for package @theforeman/vendor-dev





## [1.4.1](https://github.com/theforeman/foreman-js/compare/v1.4.0...v1.4.1) (2019-09-15)

**Note:** Version bump only for package @theforeman/vendor-dev





# [1.4.0](https://github.com/theforeman/foreman-js/compare/v1.3.1...v1.4.0) (2019-08-14)

**Note:** Version bump only for package @theforeman/vendor-dev





## [1.3.1](https://github.com/theforeman/foreman-js/compare/v1.3.0...v1.3.1) (2019-08-12)

**Note:** Version bump only for package @theforeman/vendor-dev





# [1.3.0](https://github.com/theforeman/foreman-js/compare/v1.2.3...v1.3.0) (2019-08-11)


### Features

* **vendor-core:** bump patternfly-react ([05615b7](https://github.com/theforeman/foreman-js/commit/05615b7))





## [1.2.3](https://github.com/theforeman/foreman-js/compare/v1.2.2...v1.2.3) (2019-08-10)

**Note:** Version bump only for package @theforeman/vendor-dev





## [1.2.2](https://github.com/theforeman/foreman-js/compare/v1.2.1...v1.2.2) (2019-08-09)


### Bug Fixes

* **root:** fix auto npm deploy ([b860f5b](https://github.com/theforeman/foreman-js/commit/b860f5b))





# 1.0.0 (2019-08-07)


### Bug Fixes

* **vendor-dev-babel:** stop using NODE_ENV in babel ([640959e](https://github.com/theforeman/foreman-js/commit/640959e))
* use babel test plugins in storybook env ([867f5e6](https://github.com/theforeman/foreman-js/commit/867f5e6))
* **CustomModules:** Fix custom modules in vendor-dev ([a244f59](https://github.com/theforeman/foreman-js/commit/a244f59))


### Features

* **root:** switch lerna to use locked versions ([9cc12c6](https://github.com/theforeman/foreman-js/commit/9cc12c6))
* **vendor-dev:** expose scss folder pointing to vendor-core ([6026737](https://github.com/theforeman/foreman-js/commit/6026737)), closes [#GH-39](https://github.com/theforeman/foreman-js/issues/GH-39) [#27531](https://github.com/theforeman/foreman-js/issues/27531)





# 1.0.0 (2019-08-07)


### Bug Fixes

* **vendor-dev-babel:** stop using NODE_ENV in babel ([640959e](https://github.com/theforeman/foreman-js/commit/640959e))
* use babel test plugins in storybook env ([867f5e6](https://github.com/theforeman/foreman-js/commit/867f5e6))
* **CustomModules:** Fix custom modules in vendor-dev ([a244f59](https://github.com/theforeman/foreman-js/commit/a244f59))


### Features

* **vendor-dev:** expose scss folder pointing to vendor-core ([6026737](https://github.com/theforeman/foreman-js/commit/6026737)), closes [#GH-39](https://github.com/theforeman/foreman-js/issues/GH-39) [#27531](https://github.com/theforeman/foreman-js/issues/27531)
