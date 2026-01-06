# Changelog

## 0.4.1-dev-38f32f4 (2026-01-06)

### 📦 Dependencies
- 🚀 release(whatsapp): version bump [skip-tests] ([`38f32f44`](https://github.com/FaserF/hassio-addons/commit/38f32f44a70627cbb9cda2e3b5dcae99eea7c029))
- 📝 release(whatsapp): update changelog [skip-tests] ([`24806517`](https://github.com/FaserF/hassio-addons/commit/24806517c94fcf721f32d475a27f62a33e0a8070))
- 📝 release(whatsapp): update changelog [skip-tests] ([`cdaba38c`](https://github.com/FaserF/hassio-addons/commit/cdaba38cc38638ca63f1be9563e35e31091317c1))
- Bump all addon versions ([`7a5426ba`](https://github.com/FaserF/hassio-addons/commit/7a5426bac78e1dbbbf0de477757cbe4562594434))
- bump all addons to dev version [skip-tests] ([`212568b0`](https://github.com/FaserF/hassio-addons/commit/212568b0343b757b6cd3ab18513949aa41f5d511))

### 🔧 Configuration
- revert master branch to stable versions (removed -dev suffixes) ([`4f35d8ad`](https://github.com/FaserF/hassio-addons/commit/4f35d8ad59ba6f04a4360ace09024eb7bbb459cd))

### 📝 Documentation
- improved READMEs ([`083b3025`](https://github.com/FaserF/hassio-addons/commit/083b30254f65656f616671ec8aa6649cbe085b8e))

### 🎨 Style
- auto-fix (shfmt,black,isort,prettier,markdownlint) ([`e870d4e5`](https://github.com/FaserF/hassio-addons/commit/e870d4e56a174e37a240046f85efebff8ed4ed3e))

### 🚀 Other
- more CI fixes ([`ee2d55fe`](https://github.com/FaserF/hassio-addons/commit/ee2d55fe409ee33f9f01450827adeeeafbc54956))
- small fixes ([`9e56b831`](https://github.com/FaserF/hassio-addons/commit/9e56b8317d07945c10621348570563212feab56f))
- small fixes ([`ddb72087`](https://github.com/FaserF/hassio-addons/commit/ddb720879b08bbab10f0e271bc61ab12e1d67389))
- more CI fixes ([`032a62cd`](https://github.com/FaserF/hassio-addons/commit/032a62cdaa45ecd61b19ea51897230c4179f3e9f))
- Workflow fixes ([`9ce140ba`](https://github.com/FaserF/hassio-addons/commit/9ce140ba5717a2b0b8e6414e326966090d691e35))
- small fixes ([`aa24d6e1`](https://github.com/FaserF/hassio-addons/commit/aa24d6e11af9ce4c631505f4dfa490330a48598c))
- Watchdog fixes ([`defec20c`](https://github.com/FaserF/hassio-addons/commit/defec20cc30e2499935f8946abd6d0dd8a4928e0))
- Docs improvements ([`9ba3343c`](https://github.com/FaserF/hassio-addons/commit/9ba3343c174fc850b55a9d73117eb57476b9d5cb))
- small addon fixes ([`f3f3e0f5`](https://github.com/FaserF/hassio-addons/commit/f3f3e0f56b1c3fb6e8a44e396592b6177dd9c769))
- fix Addon startup ([`7a83fd1c`](https://github.com/FaserF/hassio-addons/commit/7a83fd1cf7e004cd117e2372f51880fde076f4dc))
- fixed addon startup issues ([`29ed9ca8`](https://github.com/FaserF/hassio-addons/commit/29ed9ca8cc9312be4fe346d2674cb333c0a59859))


## 0.4.0 (2026-01-06)

### 📦 Dependencies
- Update run.sh ([`b3fc648`](https://github.com/FaserF/hassio-addons/commit/b3fc648923c63183c25fd720abd47c88112bc5b3))

### 📌 Release Note
- Manual release via Orchestrator


## 0.3.0 (2026-01-03)

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

- 📝 release(apache2-minimal): update changelog [skip-tests] ([`476e2f5`](https://github.com/FaserF/hassio-addons/commit/476e2f5ff7c65d67eb19d251f2d3fa778cc15f2f))

### 📋 Major Release - Changes

- **Bug Reports**: If you encounter any new issues, please report them on GitHub as usual. Your feedback helps us improve the addons. (Manual)
- **Unsupported Branch**: A new `unsupported` branch has been created for addons that no longer receive direct manual support. These addons are still maintained but may have limited support compared to the main addons. (Manual)
- **Edge Branch (Beta)**: A new `edge` branch is now available for those who want to test the latest features and improvements before they are released to the stable channel. (Manual)

### 📌 Release Note

- Manual release via Orchestrator

## 0.2.0

- 🛠️ **Fix**: Ingress Dashboard now works correctly (trailing slash URL fix)
- 🛠️ **Fix**: Browser fingerprint consistency (macOS/Chrome)
- ⬆️ **Upgrade**: Baileys to 6.7.21 (latest v6)
- ✨ **New**: Debug logging in browser console for Ingress fetch calls

## 0.1.0

- ✨ **New**: Secured API with Token Authentication (Ingress & Integration)
- ✨ **New**: Ingress Dashboard with Status, API Token and Live QR Code
- ✨ **New**: Smart Discovery (Auto-detects Addon Hostname)
- ✨ **New**: Reset Session option in Integration
- 🛠️ **Fix**: Ingress Compatibility (Wildcard Routing, Relative Paths)
- 🛠️ **Fix**: Build & Startup Issues (Node 24, S6 Overlay)

## 0.0.2

- Upgrade to Node.js 24 (Alpine Edge)
- Convert backend to ESM (ES Modules)
- Full S6 Service Supervision (Platinum Standard)
- Change default port to 8066
- Fix Translation Errors
- Add Icons

## 0.0.1

- Initial Release (Baileys Backend)
