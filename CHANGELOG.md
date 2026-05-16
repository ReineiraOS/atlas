## 1.0.0 (2026-05-16)

### Features

* add /claude-design skill + scroll anchors on all block sections ([4d73a17](https://github.com/ReineiraOS/reineira-atlas/commit/4d73a174bbd8e20233c874bf1508e3a2f39e1f16)), closes [#problem](https://github.com/ReineiraOS/reineira-atlas/issues/problem) [#market](https://github.com/ReineiraOS/reineira-atlas/issues/market)
* add bootstrap pipeline for one-command venture setup ([c694dbb](https://github.com/ReineiraOS/reineira-atlas/commit/c694dbb49ae0a9468ccb57a026f6d8398d9884b8))
* add Cursor IDE support alongside Claude Code ([a03c76a](https://github.com/ReineiraOS/reineira-atlas/commit/a03c76a3f3538d6ba0acef2f3433333ee5def9fa))
* add landing module template and scaffold-landing skill ([b89c5eb](https://github.com/ReineiraOS/reineira-atlas/commit/b89c5eb261b41300895ee1aae99498c53e942cf8))
* initialize reineira-atlas startup operating system ([bd9991b](https://github.com/ReineiraOS/reineira-atlas/commit/bd9991b18453627d7e9c0165a42b0232757b18ae))
* **landing:** canonical Privara-UI clone template — token-driven, 1:1 per venture ([41506e6](https://github.com/ReineiraOS/reineira-atlas/commit/41506e675465af31d1af3f63049c6e948f840d2a))
* **landing:** editorial-only direction + wow-effects ([349d854](https://github.com/ReineiraOS/reineira-atlas/commit/349d8544ff2c7f1f4647c4d5bacc0413d26ca2b8))
* **landing:** wire Hero and BaseHeader to site content config ([9bb1e78](https://github.com/ReineiraOS/reineira-atlas/commit/9bb1e78585930167f361db347f0972151ab0db72))
* **scaffold-landing:** dynamic page-structure decision procedure ([4482ab4](https://github.com/ReineiraOS/reineira-atlas/commit/4482ab4c160fe48a400ecaebf328cc346c1e6563))

### Bug Fixes

* **ci:** add package-lock.json for deterministic CI installs ([ddf9ebb](https://github.com/ReineiraOS/reineira-atlas/commit/ddf9ebb8b216cb67909c7992009d8043d4c9dee7))
* clarify artifact output — all venture files go into venture project, not atlas ([0478093](https://github.com/ReineiraOS/reineira-atlas/commit/047809369eb63b6dfa4581013970a67f2e41bbd2))
* **landing:** extract SectionList client wrapper for Context.Provider ([be4c62a](https://github.com/ReineiraOS/reineira-atlas/commit/be4c62a3524680196eb1e26819f692f8a86a2277))
* rename brief.md to brief.template.md, gitignore user brief ([3ef1906](https://github.com/ReineiraOS/reineira-atlas/commit/3ef1906c1b9f317d846c8656fa0cc4293f2d3c18))
* rename reineira-modules to platform-modules monorepo ([bdcbe90](https://github.com/ReineiraOS/reineira-atlas/commit/bdcbe90a27c0b0fe1d707d3ebc3eaca1b160aea9))
* update platform-modules stack refs and add bootstrap journey ([05ecfa5](https://github.com/ReineiraOS/reineira-atlas/commit/05ecfa548559ff3f0f30510d2b6caf5450ef7f9d))

## [0.3.0](https://github.com/ReineiraOS/reineira-atlas/compare/v0.2.0...v0.3.0) (2026-04-24)

### Features

* add /claude-design skill + scroll anchors on all block sections ([c73730c](https://github.com/ReineiraOS/reineira-atlas/commit/c73730c28fadd7d416554d236d8220f3d120b916)), closes [#problem](https://github.com/ReineiraOS/reineira-atlas/issues/problem) [#market](https://github.com/ReineiraOS/reineira-atlas/issues/market)
* add landing module template and scaffold-landing skill ([1a4be48](https://github.com/ReineiraOS/reineira-atlas/commit/1a4be48e161335f58373d6d6d7a62d3591040260))
* **landing:** canonical Privara-UI clone template — token-driven, 1:1 per venture ([04c3f3e](https://github.com/ReineiraOS/reineira-atlas/commit/04c3f3e113538f4b8fb25ac0bed4066aef430eba))
* **landing:** editorial-only direction + wow-effects ([8fd0d72](https://github.com/ReineiraOS/reineira-atlas/commit/8fd0d7204a70952a66610c84a675c28c9957deb6))
* **landing:** wire Hero and BaseHeader to site content config ([efaa935](https://github.com/ReineiraOS/reineira-atlas/commit/efaa935b9cadcb6f9f60b757ceb8ee20ddc8257c))
* **scaffold-landing:** dynamic page-structure decision procedure ([4b685d8](https://github.com/ReineiraOS/reineira-atlas/commit/4b685d85991ea020ade75fde176cde191e8c1711))

### Bug Fixes

* **landing:** extract SectionList client wrapper for Context.Provider ([58ccc03](https://github.com/ReineiraOS/reineira-atlas/commit/58ccc033a10db6562ce117df22a4c11f9ade0234))

## [0.2.0](https://github.com/ReineiraOS/reineira-atlas/compare/v0.1.1...v0.2.0) (2026-04-10)

### Features

* add Cursor IDE support alongside Claude Code ([58147f1](https://github.com/ReineiraOS/reineira-atlas/commit/58147f1d84e56d77b98aefa7aaf053b420da521a))

## [0.1.1](https://github.com/ReineiraOS/reineira-atlas/compare/v0.1.0...v0.1.1) (2026-04-05)

### Bug Fixes

* **ci:** add package-lock.json for deterministic CI installs ([c7c2530](https://github.com/ReineiraOS/reineira-atlas/commit/c7c2530024e4edb0a2ad775bfc139226d958a16d))

# Changelog

All notable changes to this project will be documented in this file.

This project uses [Semantic Versioning](https://semver.org/) and
[Conventional Commits](https://www.conventionalcommits.org/).

## [0.1.0] — 2026-03-20

### Added

- Initial release — startup operating system for ReineiraOS ventures
- 12 AI agents (protocol, product, strategy, growth, legal, ops)
- 12 slash command skills
- 11 doc templates (strategy, product, growth, intelligence, legal, execution)
- Builder brief template with protocol context
- Platform versioning via `reineira.json`

### Platform

- Compatible with ReineiraOS platform 0.1
