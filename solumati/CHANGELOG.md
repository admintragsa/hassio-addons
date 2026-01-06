# Changelog

## 2.1.1-dev-c04940c (2026-01-06)

### 🐛 Bug Fixes
- rename README.MD to README.md and prevent run.sh startup crashes ([`4fc77546`](https://github.com/FaserF/hassio-addons/commit/4fc775469d5aec6dd85ac55e71ffff56388b7228))

### 📦 Dependencies
- 🚀 release(solumati): version bump [skip-tests] ([`c04940c7`](https://github.com/FaserF/hassio-addons/commit/c04940c72004db78682d3624cbcf4e4e32fd9e1c))
- 📝 release(solumati): update changelog [skip-tests] ([`d03d3888`](https://github.com/FaserF/hassio-addons/commit/d03d3888dd1104f8a3230ab59be67964330fbb68))
- 📝 release(solumati): update changelog [skip-tests] ([`0fe7ebd2`](https://github.com/FaserF/hassio-addons/commit/0fe7ebd2bd2ae642a5cda3d150a38b57241dceeb))
- Bump all addon versions ([`7a5426ba`](https://github.com/FaserF/hassio-addons/commit/7a5426bac78e1dbbbf0de477757cbe4562594434))

### 📝 Documentation
- improved READMEs ([`083b3025`](https://github.com/FaserF/hassio-addons/commit/083b30254f65656f616671ec8aa6649cbe085b8e))

### 🎨 Style
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`e870d4e5`](https://github.com/FaserF/hassio-addons/commit/e870d4e56a174e37a240046f85efebff8ed4ed3e))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`396a11c7`](https://github.com/FaserF/hassio-addons/commit/396a11c76679d079d29134d5d8c0f94bf9446b42))
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`bfd1ae67`](https://github.com/FaserF/hassio-addons/commit/bfd1ae6710949be9eeba082897c769a655e02707))

### 🚀 Other
- fixed release ([`02960f1e`](https://github.com/FaserF/hassio-addons/commit/02960f1e6e27cc7a73fce93b6df463ea81bea23a))
- more CI fixes ([`ee2d55fe`](https://github.com/FaserF/hassio-addons/commit/ee2d55fe409ee33f9f01450827adeeeafbc54956))
- more CI & addon fixes ([`9cbf6c0b`](https://github.com/FaserF/hassio-addons/commit/9cbf6c0be6b86bbbb7f673991cc995c5d06c358d))
- CI fixes ([`c455d4be`](https://github.com/FaserF/hassio-addons/commit/c455d4be27532d8b2734ef087b11d4aedfaba826))
- fix ShieldFile Start & Addons Version Banner ([`62e9b6c3`](https://github.com/FaserF/hassio-addons/commit/62e9b6c3e86a061bf45302838b8846441098245c))
- small fixes ([`9e56b831`](https://github.com/FaserF/hassio-addons/commit/9e56b8317d07945c10621348570563212feab56f))
- small fix ([`4de506d9`](https://github.com/FaserF/hassio-addons/commit/4de506d97842d06151ae7fbb437d62669a70eb48))
- Docs improvements ([`9ba3343c`](https://github.com/FaserF/hassio-addons/commit/9ba3343c174fc850b55a9d73117eb57476b9d5cb))
- small addon fixes ([`f3f3e0f5`](https://github.com/FaserF/hassio-addons/commit/f3f3e0f56b1c3fb6e8a44e396592b6177dd9c769))
- fix Addon startup ([`7a83fd1c`](https://github.com/FaserF/hassio-addons/commit/7a83fd1cf7e004cd117e2372f51880fde076f4dc))
- fixed addon startup issues ([`29ed9ca8`](https://github.com/FaserF/hassio-addons/commit/29ed9ca8cc9312be4fe346d2674cb333c0a59859))


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

## 1.5.11

- General addon improvements

## 1.5.9

- Automatically updated Solumati to version v2025.12.3b1

## 1.5.8

- Improved build script robustness: now checks for `vite.config.ts` or
  `vite.config.js` automatically.
- Enhanced API URL replacement to handle different syntax variations.

## 1.5.7

- Fixed connection refused error by correcting build script to target `vite.config.ts`.
- Fixed API URL replacement in frontend config.

## 1.5.6

- Automatically updated Solumati to version v2025.12.3b1

## 1.5.5

- Fixed build error by targeting correct `vite.config.js` filename.

## 1.5.4

- Switched to local build (removed pre-built image dependency)

## 1.5.3

- Improved Ingress support with relative paths and dynamic port handling

## 1.5.2

- Automatically updated Solumati to version vv2025.12.3b0

## 1.5.1

- Updated Solumati to vv2025.12.3b0

## 1.5.0

- Updated Solumati to v2025.12.2-b6
- new dev option to use main branch

## 1.4.4

- Updated Solumati to v2025.12.2-b5

## 1.4.3

- Updated Solumati to v2025.12.2-b4
- **NEW**: Enable Marketing Page Option

## 1.4.1

- **NEW**: Factory Reset option (⚠️ Danger Zone) - Completely wipes all data (database, images, settings) - 5-second delay before reset to allow cancellation - Must be manually disabled after reset
- **REMOVED**: OAuth/project_name options (these are configured in Admin Panel,
  not env vars)
- Updated documentation with factory reset warnings
- Updated Solumati to v2025.12.2-b3

## 1.4.0

- **NEW**: Home Assistant Ingress support (secure sidebar access)
- **NEW**: Configurable options in HA UI: - `app_base_url` - Auto-detected from Ingress or manually set - `project_name` - Custom app name - `github_client_id` - GitHub OAuth - `google_client_id` - Google OAuth - `microsoft_client_id` - Microsoft OAuth
- Improved startup logging with environment info
- Updated documentation
- update Solumati to v2025.12.2-b2

## 1.3.14

- updated Solumati to v2025.12.1-b11

## 1.3.12

- updated Solumati to v2025.12.1-b10

## 1.3.10

- updated Solumati to v2025.12.1-b9

## 1.3.8

- updated Solumati to v2025.12.1-b8

## 1.3.6

- updated Solumati to v2025.12.1-b7

## 1.3.4

- updated Solumati to v2025.12.1-b6

## 1.3.2

- updated Solumati to v2025.12.1-b5

## 1.3.1

- updated Solumati to v2025.12.1-b4

## 1.2.0

- New features
- Bug fixes

## 1.1.0

- New features
- Bug fixes

## 1.0.0

- Initial release
