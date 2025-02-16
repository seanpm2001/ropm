# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).



## [0.10.10](https://github.com/rokucommunity/ropm/compare/v0.10.9...0.10.10) - 2022-09-12
### Changed
 - upgrade to [brighterscript@0.57.2](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0572---2022-09-08). Notable changes since 0.57.0:
     - fix(parser): consider namespace function transpiled names ([brighterscript#685](https://github.com/rokucommunity/brighterscript/pull/685))
### Fixed
 - Fix typedef default param value and prefix ([#59](https://github.com/rokucommunity/ropm/pull/59))



## [0.10.9](https://github.com/rokucommunity/ropm/compare/v0.10.8...0.10.9) - 2022-09-02
### Changed
 - upgrade to [brighterscript@0.57.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0570---2022-09-02). Notable changes since 0.56.0:
     - Allow `mod` as an aa prop, aa member identifier kinds forced to Identifier ([brighterscript#684](https://github.com/rokucommunity/brighterscript/pull/684))
     - Fix case sensitivity issue with bs_const values ([brighterscript#677](https://github.com/rokucommunity/brighterscript/pull/677))
 - upgrade to [roku-deploy@3.8.1](https://github.com/rokucommunity/roku-deploy/blob/master/CHANGELOG.md#381---2022-09-02). Notable changes since 3.7.1:
     - Bump moment from 2.29.2 to 2.29.4 ([roku-deploy#98](https://github.com/rokucommunity/roku-deploy/pull/98))



## [0.10.8](https://github.com/rokucommunity/ropm/compare/v0.10.7...0.10.8) - 2022-08-24
### Changed
 - upgrade to [brighterscript@0.56.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0560---2022-08-23). Notable changes since 0.55.1:
     - Fix compile crash for scope-less files ([brighterscript#674](https://github.com/rokucommunity/brighterscript/pull/674))
     - Fix parse error for malformed dim statement ([brighterscript#673](https://github.com/rokucommunity/brighterscript/pull/673))
     - Add validation for dimmed variables ([brighterscript#672](https://github.com/rokucommunity/brighterscript/pull/672))
     - Allow const as variable name ([brighterscript#670](https://github.com/rokucommunity/brighterscript/pull/670))



## [0.10.7](https://github.com/rokucommunity/ropm/compare/v0.10.6...0.10.7) - 2022-08-12
### Changed
 - Bump moment from 2.29.2 to 2.29.4 ([#54](https://github.com/rokucommunity/ropm/pull/54))
 - upgrade to [brighterscript@0.55.1](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0551---2022-08-07). Notable changes since 0.53.1:
     - Fix scope-specific diagnostic grouping issue ([brighterscript#660](https://github.com/rokucommunity/brighterscript/pull/660))
     - Fix typescript error for ast parent setting ([brighterscript#659](https://github.com/rokucommunity/brighterscript/pull/659))
     - Fix missing constant references ([brighterscript#658](https://github.com/rokucommunity/brighterscript/pull/658))
     - Link all brs AST nodes to parent onFileValidate ([brighterscript#650](https://github.com/rokucommunity/brighterscript/pull/650))
     - Add a `toJSON` function to SymbolTable ([brighterscript#655](https://github.com/rokucommunity/brighterscript/pull/655))
     - Performance boost: better function sorting during validation ([brighterscript#651](https://github.com/rokucommunity/brighterscript/pull/651))
     - Fix broken plugin imports with custom cwd ([brighterscript#652](https://github.com/rokucommunity/brighterscript/pull/652))
     - Export some vscode interfaces ([brighterscript#644](https://github.com/rokucommunity/brighterscript/pull/644))



## [0.10.6](https://github.com/rokucommunity/ropm/compare/v0.10.5...0.10.6) - 2022-07-18
### Changed
 - upgrade to [brighterscript@0.53.1](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0531---2022-07-15). Notable changes since 0.48.0:
     - New Language Feature: Constants ([brighterscript#632](https://github.com/rokucommunity/brighterscript/pull/632))
     - Fix missing range on interface statement ([brighterscript#623](https://github.com/rokucommunity/brighterscript/pull/623))
     - Catch class circular extends ([brighterscript#619](https://github.com/rokucommunity/brighterscript/pull/619))
     - Add object and key to visitor callbacks. ([brighterscript#600](https://github.com/rokucommunity/brighterscript/pull/600))
     - fixes enums and interfaces resulting in diagnostics error when used as field types ([brighterscript#602](https://github.com/rokucommunity/brighterscript/pull/602))
     - fixes enums and interfaces resulting in diagnostics error when used as return types from a function ([brighterscript#601](https://github.com/rokucommunity/brighterscript/pull/601))
     - Better super handling ([brighterscript#590](https://github.com/rokucommunity/brighterscript/pull/590))
     - Allow interfaces and enums as function param types ([brighterscript#580](https://github.com/rokucommunity/brighterscript/pull/580))
 - upgrade to [roku-deploy@3.7.1](https://github.com/rokucommunity/roku-deploy/blob/master/CHANGELOG.md#371---2022-06-08). Notable changes since 3.4.1:
     - export `rokuDeploy` as its own variable to get better docs ([#roku-deploy3c3deb4](https://github.com/rokucommunity/roku-deploy/commit/3c3deb4))
     - Performance improvements ([roku-deploy#86](https://github.com/rokucommunity/roku-deploy/pull/86))
     - Allow negated non-root-dir top-level patterns in files array ([roku-deploy#78](https://github.com/rokucommunity/roku-deploy/pull/78))



## [0.10.5](https://github.com/rokucommunity/ropm/compare/v0.10.4...v0.10.5) - 2022-04-13
### Changed
 - updated to [brighterscript@0.48.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0480---2022-04-13)



## [0.10.4](https://github.com/rokucommunity/ropm/compare/v0.10.3...v0.10.4) - 2022-02-24
### Changed
 - updated to [brighterscript@0.45.2](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0452---2022-02-24)



## [0.10.3](https://github.com/rokucommunity/ropm/compare/v0.10.2...v0.10.3) - 2022-01-28
### Changed
 - updated to [brighterscript@0.43.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0430---2022-01-28)



## [0.10.2](https://github.com/rokucommunity/ropm/compare/v0.10.1...v0.10.2) - 2022-01-24
### Changed
 - updated to [brighterscript@0.42.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0420---2022-01-10)
### Fixed
 - noprefix module bug that wasn't handling imports properly ([#50](https://github.com/rokucommunity/ropm/pull/50))



## [0.10.1](https://github.com/rokucommunity/ropm/compare/v0.10.0...v0.10.1) - 2021-09-09
### Fixed
 - crash when processing nonstandard dirs that have brs/xml files ([#49](https://github.com/rokucommunity/ropm/pull/49))
 - ignore prod subdependencies that don't have the `ropm` keyword ([#44](https://github.com/rokucommunity/ropm/pull/44))
 - fix prefixing function reference even if module is set to `noprefix` mode ([#43](https://github.com/rokucommunity/ropm/pull/43))



## [0.10.0] - 2021-06-21
[0.10.0]: https://github.com/rokucommunity/ropm/compare/v0.9.3...v0.10.0
### Added
 - Allow option to override `rootDir` in NodeJS api options for `InstallCommand` rather than always loading from package.json



## [0.9.3] - 2021-06-01
[0.9.3]: https://github.com/rokucommunity/ropm/compare/v0.9.2...v0.9.3
### Changed
 - upgraded to [roku-deploy@3.4.1](https://github.com/rokucommunity/roku-deploy/blob/master/CHANGELOG.md#341---2021-06-01)
 - updated to [brighterscript@0.39.3](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0392---2021-05-28) which includes roku-deploy@3.4.1
### Fixed
 - crash in roku-deploy caused by missing dependency



## [0.9.2] - 2021-05-28
[0.9.2]: https://github.com/rokucommunity/ropm/compare/v0.9.1...v0.9.2
### Changed
 - upgraded to [roku-deploy@3.4.0](https://github.com/rokucommunity/roku-deploy/blob/master/CHANGELOG.md#340---2021-05-28) which brings significant zip speed improvements
 - updated to [brighterscript@0.39.2](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0392---2021-05-28)
### Fixed
 - several npm audit vulnerability issues



## [0.9.1] - 2021-02-27
[0.9.1]:   https://github.com/rokucommunity/ropm/compare/v0.9.0...v0.9.1
### Changed
 - updated to [brighterscript@0.33.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0330---2021-02-27)
### Fixed
 - bug where any function containing an immediately-invoked function expression would have its contents skipped during preprocessing (fixed by [brighterscript#343](https://github.com/rokucommunity/brighterscript/pull/343))



## [0.9.0] - 2021-02-19
[0.9.0]:   https://github.com/rokucommunity/ropm/compare/v0.8.1...v0.9.0
### Added
 - `ROPM_PREFIX` source literal to assist package authors with non-standard string function name logic ([#32](https://github.com/rokucommunity/ropm/pull/32))
### Changed
 - updated to [brighterscript@0.31.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0312---2021-02-18)
### Fixed
 - bug in d.bs type definition files causing function and class annotiations to be incorrectly associated with their parent namespaces ([#31](https://github.com/rokucommunity/ropm/pull/31))
 - add missing prefix for Task `m.top.functionName = "<someFunctionName>"` ([#34](https://github.com/rokucommunity/ropm/pull/34))
 - better class name handling in d.bs type definition files ([#33](https://github.com/rokucommunity/ropm/pull/33))
 - prevent running host project brighterscript plugins during ropm install of every ropm package ([#35](https://github.com/rokucommunity/ropm/pull/35))



## [0.8.1] - 2021-02-09
[0.8.1]:   https://github.com/rokucommunity/ropm/compare/v0.8.0...v0.8.1
### Changed
 - updated to [brighterscript@0.30.6](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0306---2021-02-07)
### Fixed
 - bug with old-style bsc plugins crashing ropm install.



## [0.8.0] - 2021-01-19
[0.8.0]:   https://github.com/rokucommunity/ropm/compare/v0.7.7...v0.8.0
### Added
 - special prefixing logic for leading underscores. See [this](https://github.com/rokucommunity/ropm#leading-underscore) for more information.



## [0.7.7] - 2021-01-07
[0.7.7]:   https://github.com/rokucommunity/ropm/compare/v0.7.6...v0.7.7
### Changed
 - updated to [brighterscript@0.23.2](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0232---2020-01-06)
 - remove direct reference to vscode-languageserver-protocol



## [0.7.6] - 2021-01-04
[0.7.6]:   https://github.com/rokucommunity/ropm/compare/v0.7.5...v0.7.6
### Fixed
 - apply prefix to `observeFieldScoped` calls ([#20](https://github.com/rokucommunity/ropm/issues/20))



## [0.7.5] - 2020-12-22
[0.7.5]:   https://github.com/rokucommunity/ropm/compare/v0.7.4...v0.7.5
### Changed
 - updated to [brighterscript@0.23.1](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0231---2020-12-22)



## [0.7.4] - 2020-12-14
[0.7.4]:   https://github.com/rokucommunity/ropm/compare/v0.7.3...v0.7.4
### Changed
 - updated to [brighterscript@0.22.1](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0221---2020-12-14)
### Fixed
 - bug with brighterscript->vscode-languageserver->vscode-languageserver-types dependency that had breaking change in minor version release.



## [0.7.3] - 2020-11-03
[0.7.3]:   https://github.com/rokucommunity/ropm/compare/v0.7.2...v0.7.3
### Fixed
 - don't wrap interface-referenced functions found in `d.bs` with a namespace



## [0.7.2] - 2020-11-02
[0.7.2]:   https://github.com/rokucommunity/ropm/compare/v0.7.1...v0.7.2
### Changed
 - updated to [brighterscript@0.18.2](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0182---2020-11-2)
 - removed unnecessary code to force bsc files to parse (because brighterscript@0.18.2 now does that automatically)



## [0.7.1] - 2020-11-01
[0.7.1]:   https://github.com/rokucommunity/ropm/compare/v0.7.0...v0.7.1
### Fixed
 - Fix bug with unprefixed functions whenever a typedef is present.



## [0.7.0] - 2020-20-30
[0.7.0]:   https://github.com/rokucommunity/ropm/compare/v0.6.6...v0.7.0
### Added
 - Prefixing support for `d.bs` (typedef) files from BrighterScript
### Changed
 - updated to [brighterscript@0.18.0](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#0180---2020-10-30)



## [0.6.6] - 2020-10-29
[0.6.6]:   https://github.com/rokucommunity/ropm/compare/v0.6.5...v0.6.6
### Fixed
 - bug where function references do not honor prefixing whitelist



## [0.6.5] - 2020-10-25
[0.6.5]:   https://github.com/rokucommunity/ropm/compare/v0.6.4...v0.6.5
### Fixed
 - prefixing bug that wasn't applying prefix to to xml field `onChange` events



## [0.6.4] - 2020-10-20
[0.6.4]:   https://github.com/rokucommunity/ropm/compare/v0.6.3...v0.6.4
### Added
 - `rootDir` prompt during first install or init
### Changed
 - `ropm.noprefix` now requires the npm alias name, **NOT** the ropm alias name (how it was previously).
 - updated to [brighterscript@0.16.11](https://github.com/rokucommunity/brighterscript/blob/master/CHANGELOG.md#01611---2020-10-20)


## [0.6.3] - 2020-10-16
[0.6.3]:   https://github.com/rokucommunity/ropm/compare/v0.6.2...v0.6.3
### Fixed
 - force delete during `ropm clean`
 - bug that was incorrectly prefixing calls to interface functions



## [0.6.2] - 2020-10-08
[0.6.2]:   https://github.com/rokucommunity/ropm/compare/v0.6.1...v0.6.2
### Fixed
 - `ropm` now disables prefixing functions that are referenced in component interfaces.



## [0.6.1] - 2020-10-08
[0.6.1]:   https://github.com/rokucommunity/ropm/compare/v0.6.0...v0.6.1
### Changed
 - use the (BrighterScript)[https://github.com/rokucommunity/brighterscript] parser to simplify prefixing.



## [0.6.0] - 2020-10-07
[0.6.0]:   https://github.com/rokucommunity/ropm/compare/v0.5.0...v0.6.0
### Fixed
 - fix missing prefixes on function references not used as a function call
 - find and prefix function names in `observeField` calls
### Known issues
 - still no support for bypassing prefixing for functions referenced in component `interface` fields. That will be coming in a future release.



## [0.5.0] - 2020-09-26
[0.5.0]:   https://github.com/rokucommunity/ropm/compare/v0.4.1...v0.5.0
### Added
 - `ropm copy` command that speeds up local development by skipping the registry check (i.e. internal `npm install` call)
### Fixed
 - prevent prefixing calls to variable functions
 - prevent prefixing function calls found on objects (i.e. `person.doSomething()`)



## [0.4.2] - 2020-09-25
[0.4.2]:   https://github.com/rokucommunity/ropm/compare/v0.4.1...v0.4.2
### Fixed
 - Prevent prefixing special function `onKeyEvent`



## [0.4.1] - 2020-09-25
[0.4.1]:   https://github.com/rokucommunity/ropm/compare/v0.4.0...v0.4.1
### Fixed
 - bug that was using the unsanitized npm alias instead of the ropm package name in certain install situations for direct dependencies.



## [0.4.0] - 2020-09-24
[0.4.0]:   https://github.com/rokucommunity/ropm/compare/v0.3.0...v0.4.0
### Added
 - `ropm.noprefix` package.json option to prevent certain modules from having a prefix applied.
 - reject installing packages that have the `ropm.noprefix` setting present in `package.json`: this setting is only for use in client applications.
### Fixed
 - dependency component references were not being renamed according to their resolved prefix.



## [0.3.0] - 2020-09-23
[0.3.0]: https://github.com/rokucommunity/ropm/compare/v0.2.0...v0.3.0
### Added
 - `ropm.packageRootDir` for use by package authors to define where their package code resides. This deviates from the previous functionalith where both were handled by `rootDir`, now `rootDir` is exclusively for ropm INSTALL location.
### Changed
 - do not copy `roku_module` folders from ropm modules during `ropm install`
### Fixed
 - bug where npm would throw `npm ERR! extraneous` errors when installing file protocol packages, causing the install to bomb. Now we just ignore that error because it's not important.



## [0.2.0] - 2020-08-28
[0.2.0]: https://github.com/rokucommunity/ropm/compare/v0.1.1...v0.2.0
### Added
 - "uninstall" command which removes a list of packages from both `roku_modules` and `node_modules`
 - function/component prefixing and file path renaming during install.
### Fixed
 - bug in "clean" command that wasn't cleaning projects with custom `ropm.rootDir` paths.
 - bug with prerelease versions not installing properly



## [0.1.1] - 2020-08-06
[0.1.1]: https://github.com/rokucommunity/ropm/compare/v0.1.0...v0.1.1
### Added
 -  "clean" command which removes all ropm files from a project (but leaves the package.json intact)
### Changed
 - remove unnecessary files from published `ropm` npm package
 - the `"ropm"` keyword is now required in ropm module's package.json, and any package without it will be ignored by ropm
### Fixed
 - missing shebang at top of cli script causing problems running ropm from the terminal
 - fix running `ropm install` without any arguments



## [0.1.0] - 2020-08-05
[0.1.0]:   https://github.com/rokucommunity/ropm/compare/v0.0.1...v0.1.0
### Added
 - cli command 'init'
 - cli command 'install' which allows you to install packages with the same syntax as [npm install](https://docs.npmjs.com/cli/install)
 - basic documentation



## 0.0.1
### Added
 - initial placeholder release
