# Changelog

## 2.1.1-dev-fafe8e9 (2026-01-06)

### 🐛 Bug Fixes
- rename README.MD to README.md and prevent run.sh startup crashes ([`4fc77546`](https://github.com/FaserF/hassio-addons/commit/4fc775469d5aec6dd85ac55e71ffff56388b7228))

### 📦 Dependencies
- 🚀 release(ShieldFile): version bump [skip-tests] ([`fafe8e99`](https://github.com/FaserF/hassio-addons/commit/fafe8e99314687654225f186aba0428b9843ebd2))
- 📝 release(ShieldFile): update changelog [skip-tests] ([`ed38a822`](https://github.com/FaserF/hassio-addons/commit/ed38a822a1ef069600acf1c87bc3d071dde52fcc))
- 📝 release(ShieldFile): update changelog [skip-tests] ([`9fbe018e`](https://github.com/FaserF/hassio-addons/commit/9fbe018ef9bb99d6833e72821f4de1710af5f3b6))
- 📝 release(ShieldFile): update changelog [skip-tests] ([`d070e612`](https://github.com/FaserF/hassio-addons/commit/d070e6127b574d1094c0d8cea003fa847fb54c32))

### 📝 Documentation
- improved READMEs ([`083b3025`](https://github.com/FaserF/hassio-addons/commit/083b30254f65656f616671ec8aa6649cbe085b8e))

### 🎨 Style
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`e870d4e5`](https://github.com/FaserF/hassio-addons/commit/e870d4e56a174e37a240046f85efebff8ed4ed3e))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`396a11c7`](https://github.com/FaserF/hassio-addons/commit/396a11c76679d079d29134d5d8c0f94bf9446b42))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`b74f128e`](https://github.com/FaserF/hassio-addons/commit/b74f128e8f81e47b58067a1a134345be9dcaf894))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`02edd1c1`](https://github.com/FaserF/hassio-addons/commit/02edd1c1dcbea38d1a372aee4b7dab1ad15b4352))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`bfd1ae67`](https://github.com/FaserF/hassio-addons/commit/bfd1ae6710949be9eeba082897c769a655e02707))

### 🚀 Other
- more CI fixes ([`ee2d55fe`](https://github.com/FaserF/hassio-addons/commit/ee2d55fe409ee33f9f01450827adeeeafbc54956))
- more CI & addon fixes ([`9cbf6c0b`](https://github.com/FaserF/hassio-addons/commit/9cbf6c0be6b86bbbb7f673991cc995c5d06c358d))
- CI fixes ([`c455d4be`](https://github.com/FaserF/hassio-addons/commit/c455d4be27532d8b2734ef087b11d4aedfaba826))
- CI fixes ([`75002337`](https://github.com/FaserF/hassio-addons/commit/75002337a94782df0f3c177568209be9a8af936c))
- fixed & improved ShieldFile and Wordpress Addons ([`d1a39825`](https://github.com/FaserF/hassio-addons/commit/d1a398253b038b9265b5fec1f1f981936445a80e))
- fix ShieldFile Start & Addons Version Banner ([`62e9b6c3`](https://github.com/FaserF/hassio-addons/commit/62e9b6c3e86a061bf45302838b8846441098245c))
- small fixes ([`9e56b831`](https://github.com/FaserF/hassio-addons/commit/9e56b8317d07945c10621348570563212feab56f))
- general Addon & Test fixes ([`1a9f2ddd`](https://github.com/FaserF/hassio-addons/commit/1a9f2ddd2ec900a5092144c2d99e49088bd3c8f2))
- small fix ([`4de506d9`](https://github.com/FaserF/hassio-addons/commit/4de506d97842d06151ae7fbb437d62669a70eb48))


## 2.1.0 (2026-01-06)

### 📦 Dependencies
- Update run.sh ([`b3fc648`](https://github.com/FaserF/hassio-addons/commit/b3fc648923c63183c25fd720abd47c88112bc5b3))

### 📌 Release Note
- Manual release via Orchestrator


## 2.0.0 (2026-01-03)

🎉 **Happy New Year 2026!** 🎉

### 🎉 Major Release - Unified Addon Update

All addons have been unified, updated, and many bugs have been fixed. Many addons have been partially or completely rewritten to improve stability, performance, and maintainability.

#### Important Information

- **Edge Branch (Beta)**: A new `edge` branch is now available for those who want to test the latest features and improvements before they are released to the stable channel.
- **Unsupported Branch**: A new `unsupported` branch has been created for addons that no longer receive direct manual support. These addons are still maintained but may have limited support compared to the main addons.
- **Bug Reports**: If you encounter any new issues, please report them on GitHub as usual. Your feedback helps us improve the addons.

This release represents a significant effort to standardize and improve all addons in the repository.

---

### 📦 Dependencies

- Update orchestrator-release.yaml ([`4774494`](https://github.com/FaserF/hassio-addons/commit/477449414ddf817f9297c2ac38ade8009b69ae12))

### 📋 Major Release - Changes

- **Bug Reports**: If you encounter any new issues, please report them on GitHub as usual. Your feedback helps us improve the addons. (Manual)
- **Unsupported Branch**: A new `unsupported` branch has been created for addons that no longer receive direct manual support. These addons are still maintained but may have limited support compared to the main addons. (Manual)
- **Edge Branch (Beta)**: A new `edge` branch is now available for those who want to test the latest features and improvements before they are released to the stable channel. (Manual)

### 📌 Release Note

- Manual release via Orchestrator

## 1.0.15 (2026-01-03)

- Bump version to 1.0.15

## 1.0.14

- Added support for multiple users via list format in configuration.
- **Breaking Change**: The `username` and `password` options have been replaced by the `users` list.
- Improved documentation with multi-user examples.

## 1.0.13

- Fixed `filebrowser users update` syntax error ("accepts 1 arg, received 2").
- Now correctly uses `--password` flag for updates.

## 1.0.12

- Changed Dockerfile `ENTRYPOINT` to `["/run.sh"]` to completely override S6 initialization.

## 1.0.11

- Switched Base Image to standard `ghcr.io/home-assistant/amd64-base:alpine` to
  resolve S6 overlay conflicts.
- This aligns the execution environment with other working addons (like Solumati).

## 1.0.10

- Added `ENTRYPOINT []` to Dockerfile to guarantee S6 overlay is disabled.

## 1.0.9

- Refactored startup to use direct `CMD` execution instead of S6 services to
  definitively resolve PID 1 errors.
- **Note**: This requires a manual `git push` to take effect.

## 1.0.8

- Added debug logging to verify execution of new script version.

## 1.0.7

- Re-release to ensure manual environment loading fix is propagated.

## 1.0.6

- Implemented manual environment loading to fix PID 1 error while maintaining
  Supervisor API access.

## 1.0.5

- Removed `with-contenv` from shebang to permanently resolve the
  "s6-overlay-suexec: fatal: can only run as pid 1" error.

## 1.0.4

- Refactored startup to use S6 legacy services (services.d) properly,
  fixing PID 1 error.

## 1.0.3

- Fixed s6-overlay-suexec "can only run as pid 1" error by adding `init: false`

## 1.0.1 & 1.0.2

- **Fix**: Critical startup fix. Refactored Container structure (CMD vs S6
  services.d) to resolve s6 loop error.

## 1.0.0

- Initial release
