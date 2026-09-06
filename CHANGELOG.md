# Changelog

## [6.0.0](https://github.com/fabian-basurto/dynamodb-gui/compare/v5.3.3...v6.0.0) (2026-09-06)


### ⚠ BREAKING CHANGES

* migrate to aws-sdk 3 ([#447](https://github.com/fabian-basurto/dynamodb-gui/issues/447))

### Features

* add base-path support for running behind reverse proxy ([#515](https://github.com/fabian-basurto/dynamodb-gui/issues/515)) ([f2c524f](https://github.com/fabian-basurto/dynamodb-gui/commit/f2c524f4cd268d461d08d6272591e3d455d79afa))
* add page size dropdown ([#324](https://github.com/fabian-basurto/dynamodb-gui/issues/324)) ([15b408f](https://github.com/fabian-basurto/dynamodb-gui/commit/15b408fed9dceb3a177adc32d5e0469ce1fc1a2c))
* add release workflow ([0cac2d3](https://github.com/fabian-basurto/dynamodb-gui/commit/0cac2d3d4cef7c681826cc3f664be3fbeb4a2ca8))
* add TTL tab to display time-to-live status ([#520](https://github.com/fabian-basurto/dynamodb-gui/issues/520)) ([ee29325](https://github.com/fabian-basurto/dynamodb-gui/commit/ee29325c51664681c8920b454976bec466df0399))
* delete/purge multiple tables at once ([#248](https://github.com/fabian-basurto/dynamodb-gui/issues/248)) ([9c726d5](https://github.com/fabian-basurto/dynamodb-gui/commit/9c726d56da0bebe6d386dbfee7d091d4661a2389))
* expose Purge table button in Table's Meta section ([#455](https://github.com/fabian-basurto/dynamodb-gui/issues/455)) ([7d5f0d3](https://github.com/fabian-basurto/dynamodb-gui/commit/7d5f0d3cb20a3fd74ff8b7486be2601c8bb58964))
* guess whether timestamp is in seconds or milliseconds ([#456](https://github.com/fabian-basurto/dynamodb-gui/issues/456)) ([e812f92](https://github.com/fabian-basurto/dynamodb-gui/commit/e812f92407ac8d66327f8dc28184b7471e1635d2))
* retain table filter value on navigation ([#453](https://github.com/fabian-basurto/dynamodb-gui/issues/453)) ([91d6079](https://github.com/fabian-basurto/dynamodb-gui/commit/91d60790f3aad3c3efaed324936d71e774b8f8a4))
* support AWS_SESSION_TOKEN ([#522](https://github.com/fabian-basurto/dynamodb-gui/issues/522)) ([75bc916](https://github.com/fabian-basurto/dynamodb-gui/commit/75bc91644182c48a159002b6458607f2412f4a81))


### Bug Fixes

* add tini to dockerfile ([#427](https://github.com/fabian-basurto/dynamodb-gui/issues/427)) ([c7da326](https://github.com/fabian-basurto/dynamodb-gui/commit/c7da3263835d0169abe9e59ec1f31c16fc358431))
* allow passing custom express instance to createServer ([#383](https://github.com/fabian-basurto/dynamodb-gui/issues/383)) ([3b4a32b](https://github.com/fabian-basurto/dynamodb-gui/commit/3b4a32b357396ba8558170f1d727a247c0727179))
* dark mode styles for recently added table header ([#348](https://github.com/fabian-basurto/dynamodb-gui/issues/348)) ([e2eddb1](https://github.com/fabian-basurto/dynamodb-gui/commit/e2eddb1b1dc7ac810779b3caf9a557476fca3dc9))
* docker image building ([#448](https://github.com/fabian-basurto/dynamodb-gui/issues/448)) ([fb2af26](https://github.com/fabian-basurto/dynamodb-gui/commit/fb2af265283c0b733779ba700f34c71de37e6fb0))
* docker publish ([657074b](https://github.com/fabian-basurto/dynamodb-gui/commit/657074b8619a3614ddde9b0a7998a2c9fbfaa2ae))
* **docker:** only include production dependencies (smaller size) ([#205](https://github.com/fabian-basurto/dynamodb-gui/issues/205)) ([73fcc2a](https://github.com/fabian-basurto/dynamodb-gui/commit/73fcc2a0c83bc30627596607ef643f422dae10f9))
* **docs:** Use "set" on Windows to set env variable ([#99](https://github.com/fabian-basurto/dynamodb-gui/issues/99)) ([2b23c40](https://github.com/fabian-basurto/dynamodb-gui/commit/2b23c400323f57a6f92a6abb698f15f39b7efc0a))
* encode table name in the breadcrumb ([#457](https://github.com/fabian-basurto/dynamodb-gui/issues/457)) ([6c9f9d0](https://github.com/fabian-basurto/dynamodb-gui/commit/6c9f9d0e789263a24921a055fc699ac7880975c9))
* ensure DYNAMO_ENDPOINT env overwrites default endpoint when set ([#451](https://github.com/fabian-basurto/dynamodb-gui/issues/451)) ([07c9c17](https://github.com/fabian-basurto/dynamodb-gui/commit/07c9c17a1522fa32bcf4516840cd3aac099e341d))
* escape keys properly for expression attribute names ([#103](https://github.com/fabian-basurto/dynamodb-gui/issues/103)) ([043e7b8](https://github.com/fabian-basurto/dynamodb-gui/commit/043e7b815d69fcf625f11772735da39f036535b9))
* escape table name passed to the API ([#452](https://github.com/fabian-basurto/dynamodb-gui/issues/452)) ([624363b](https://github.com/fabian-basurto/dynamodb-gui/commit/624363ba5fbb711bf4754ee24d7aa86dfb862d08))
* forward dynamo messages on errors during items listing ([40709c3](https://github.com/fabian-basurto/dynamodb-gui/commit/40709c38cf9cb2b3e4da27d2379e6912f71f4f20))
* improve handling of API errors ([#454](https://github.com/fabian-basurto/dynamodb-gui/issues/454)) ([974efc6](https://github.com/fabian-basurto/dynamodb-gui/commit/974efc67ce16599103d6f1bc2f2ea3a1006bf7cd))
* make range (sort) key optional ([f7091d9](https://github.com/fabian-basurto/dynamodb-gui/commit/f7091d923e4dec55b366b2059a0ba55a2c3cba1b))
* make range (sort) key optional ([9c702bb](https://github.com/fabian-basurto/dynamodb-gui/commit/9c702bbc5958f5871e4e3f25865ffd9a171d16b5)), closes [#143](https://github.com/fabian-basurto/dynamodb-gui/issues/143)
* make secondary index count start from 1 ([9c87da3](https://github.com/fabian-basurto/dynamodb-gui/commit/9c87da3b245cbdbe5930b310d095af5807000ce6))
* npm package missing html code ([#459](https://github.com/fabian-basurto/dynamodb-gui/issues/459)) ([5933e2c](https://github.com/fabian-basurto/dynamodb-gui/commit/5933e2c671116c014136ba35c1e9fa41e5dadb81))
* place dark mode toggle in the breadcrumb header ([#228](https://github.com/fabian-basurto/dynamodb-gui/issues/228)) ([63903d8](https://github.com/fabian-basurto/dynamodb-gui/commit/63903d819e6e690b5112e125906fb4797914ed79))
* small style issues ([887aa01](https://github.com/fabian-basurto/dynamodb-gui/commit/887aa01e7efae8bc00c480e2c03af093d5d53ecf))
* switch back default host to undefined ([b8c01f1](https://github.com/fabian-basurto/dynamodb-gui/commit/b8c01f1522b0c52935d860a69aa1f172edd9d4b4))
* switch back default host to undefined ([badc164](https://github.com/fabian-basurto/dynamodb-gui/commit/badc16438a7cf29e6408632ad5f4ffc3589956a8))
* update docs ([#528](https://github.com/fabian-basurto/dynamodb-gui/issues/528)) ([dcb89c6](https://github.com/fabian-basurto/dynamodb-gui/commit/dcb89c619a0afc06b01bd42062c17b00ff6c33f7))
* update node to v16 in docker image ([c0d60f3](https://github.com/fabian-basurto/dynamodb-gui/commit/c0d60f3541f4f1350955697d158aeeb265d0bbf0))
* update node version for docker image ([127f0eb](https://github.com/fabian-basurto/dynamodb-gui/commit/127f0eb2a8c5e10e72754c94e288d54753d74f5b))
* update patch/minor dependencies ([db1e3cc](https://github.com/fabian-basurto/dynamodb-gui/commit/db1e3cc5a62db002cd764011b1d0c39a0c927147))
* update repository URL ([#530](https://github.com/fabian-basurto/dynamodb-gui/issues/530)) ([b9eff1f](https://github.com/fabian-basurto/dynamodb-gui/commit/b9eff1fa626004dbe37751f4324533e92357e98f))
* update rollup ([#533](https://github.com/fabian-basurto/dynamodb-gui/issues/533)) ([9543786](https://github.com/fabian-basurto/dynamodb-gui/commit/95437860f620c981c3e1c65283af2be242c5b905))
* update rollup ([#534](https://github.com/fabian-basurto/dynamodb-gui/issues/534)) ([830cf47](https://github.com/fabian-basurto/dynamodb-gui/commit/830cf47ad5fdd4e4542cd478afca825a5fa3d3e6))
* update rollup ([#535](https://github.com/fabian-basurto/dynamodb-gui/issues/535)) ([afe684f](https://github.com/fabian-basurto/dynamodb-gui/commit/afe684fe8ad36997219253b31834dec9a20a13d1))


### Refactors

* class for dynamo api ([#460](https://github.com/fabian-basurto/dynamodb-gui/issues/460)) ([0b3c61d](https://github.com/fabian-basurto/dynamodb-gui/commit/0b3c61dce0d73e48592f84dc10d6221048313c75))
* extract api creation into its own file ([#446](https://github.com/fabian-basurto/dynamodb-gui/issues/446)) ([ac4445c](https://github.com/fabian-basurto/dynamodb-gui/commit/ac4445c97351a64c3f23589a8a8c776326016d2d))
* migrate codebase to typescript ([#444](https://github.com/fabian-basurto/dynamodb-gui/issues/444)) ([11f32c0](https://github.com/fabian-basurto/dynamodb-gui/commit/11f32c0429b947b2e7f8c18f03e229671ebbc7b5))
* migrate to aws-sdk 3 ([#447](https://github.com/fabian-basurto/dynamodb-gui/issues/447)) ([18fbc66](https://github.com/fabian-basurto/dynamodb-gui/commit/18fbc665a793e32d39b3913fba5a083d148c164d))
* replace `cli-color` with `picocolors` ([#509](https://github.com/fabian-basurto/dynamodb-gui/issues/509)) ([f60c740](https://github.com/fabian-basurto/dynamodb-gui/commit/f60c740527175b58c9cf066ff5898a66b5f0de40))
* use node 20 in docker container ([7d3b162](https://github.com/fabian-basurto/dynamodb-gui/commit/7d3b162edca81ea03263dc0d348c4ac0399fe12e))

## [5.3.3](https://github.com/aaronshaf/dynamodb-admin/compare/v5.3.2...v5.3.3) (2026-06-10)


### Bug Fixes

* update rollup ([#533](https://github.com/aaronshaf/dynamodb-admin/issues/533)) ([9543786](https://github.com/aaronshaf/dynamodb-admin/commit/95437860f620c981c3e1c65283af2be242c5b905))

## [5.3.2](https://github.com/aaronshaf/dynamodb-admin/compare/v5.3.1...v5.3.2) (2026-06-10)


### Bug Fixes

* update repository URL ([#530](https://github.com/aaronshaf/dynamodb-admin/issues/530)) ([b9eff1f](https://github.com/aaronshaf/dynamodb-admin/commit/b9eff1fa626004dbe37751f4324533e92357e98f))

## [5.3.1](https://github.com/aaronshaf/dynamodb-admin/compare/v5.3.0...v5.3.1) (2026-06-10)


### Bug Fixes

* update docs ([#528](https://github.com/aaronshaf/dynamodb-admin/issues/528)) ([dcb89c6](https://github.com/aaronshaf/dynamodb-admin/commit/dcb89c619a0afc06b01bd42062c17b00ff6c33f7))

## [5.3.0](https://github.com/aaronshaf/dynamodb-admin/compare/v5.2.0...v5.3.0) (2026-06-10)


### Features

* add release workflow ([0cac2d3](https://github.com/aaronshaf/dynamodb-admin/commit/0cac2d3d4cef7c681826cc3f664be3fbeb4a2ca8))
* add TTL tab to display time-to-live status ([#520](https://github.com/aaronshaf/dynamodb-admin/issues/520)) ([ee29325](https://github.com/aaronshaf/dynamodb-admin/commit/ee29325c51664681c8920b454976bec466df0399))
* support AWS_SESSION_TOKEN ([#522](https://github.com/aaronshaf/dynamodb-admin/issues/522)) ([75bc916](https://github.com/aaronshaf/dynamodb-admin/commit/75bc91644182c48a159002b6458607f2412f4a81))


### Refactors

* replace `cli-color` with `picocolors` ([#509](https://github.com/aaronshaf/dynamodb-admin/issues/509)) ([f60c740](https://github.com/aaronshaf/dynamodb-admin/commit/f60c740527175b58c9cf066ff5898a66b5f0de40))
