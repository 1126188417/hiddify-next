# Changelog

## [0.12.0.dev] - 2023-12-01

### New Features and Improvements

- Added soffchen to recommended geo assets

### Bug Fixes

- Refactored significant portions of the app
- Fixed incorrect profile parsing when missing headers
- Fixed geo assets bug where assets were deactivated
- Updated sing-box to version 1.7.0
- Fixed Chinese typography bug (thanks to [betaxab](https://github.com/betaxab))
- Fixed localization mistakes in Russian. [PR#189](https://github.com/hiddify/hiddify-next/pull/189) by [jomertix](https://github.com/jomertix)

## [0.11.1] - 2023-11-19

### Bug Fixes

- Fixed Android manifest bug.

## [0.11.0] - 2023-11-19

### New Features and Improvements

- Changed Responsive UI Behavior
  - Now app is responsive on all platforms with appropriate routing setup.
- Added Simplified Service Modes
  - Choose between VPN(Tun), System Proxy and Proxy only modes. (System Proxy available on desktop)
- Added Share Functionality
  - Share configuration as json(export to clipboard) or share subscription link as QR code.
- Redesigned System Tray on Desktop
  - Options have been simplified and a new mode selector and navigation options are added.
- Added Privilege Checks for VPN(TUN) on Desktop
- Added Auto Connect on Start
  - On desktop, app will try to connect to the last used profile on startup. (if last session was not explicitly disconnected by the user)
- Added AppCast Update Checker
  - Checking for new versions of the app will use a more reliable approach on all platforms.
- Added Geo Asset Settings
  - Update geo assets and use recommended providers
- Added **winget** Release
  - Now you're able to install and update Hiddify Next on Windows using [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/).
- Added Turkish Translations. [PR#173](https://github.com/hiddify/hiddify-next/pull/173) by [Hasan Karlı](https://github.com/hasankarli)
- Changed in-app Toasts
- Updated Core Sing-box Version to 1.7.0
- Improved Network Reliability While Adding/Updating Subscriptions
- Improved QR Code Scanner

### Bug Fixes

- Removed **execute config as is** option which caused crashes and confusion for users.
- Fixed android service revoke and restart.
- Fixed github release update checker.
- Fixed translator script. [PR#108](https://github.com/hiddify/hiddify-next/pull/108) by [Hirad Rasoolinejad](https://github.com/Hiiirad)
- Fixed localization mistakes in Chinese. [PR#113](https://github.com/hiddify/hiddify-next/pull/113) and [PR#123](https://github.com/hiddify/hiddify-next/pull/123) by [Nyar233](https://github.com/Nyar233)
- Fixed localization mistakes in Chinese Readme. [PR#137](https://github.com/hiddify/hiddify-next/pull/137) by [wldjdjsks](https://github.com/huajizhige)
- Fixed localization mistakes in Chinese. [PR#138](https://github.com/hiddify/hiddify-next/pull/138) and [PR#165](https://github.com/hiddify/hiddify-next/pull/165) by [wldjdjsks](https://github.com/huajizhige)
- Fixed localization mistakes in Russian. [PR#155](https://github.com/hiddify/hiddify-next/pull/155), [PR#162](https://github.com/hiddify/hiddify-next/pull/162) and [PR#169](https://github.com/hiddify/hiddify-next/pull/169) by [solokot](https://github.com/solokot)
- Fixed linux build libs command. [PR#161](https://github.com/hiddify/hiddify-next/pull/161) by [Aloxaf](https://github.com/Aloxaf)
- Fixed localization mistakes in Russian. [PR#164](https://github.com/hiddify/hiddify-next/pull/164) and [PR#168](https://github.com/hiddify/hiddify-next/pull/168) by [jomertix](https://github.com/jomertix)
- Fixed localization mistakes in Chinese. [PR#179](https://github.com/hiddify/hiddify-next/pull/179) by [betaxab](https://github.com/betaxab)
- Fixed localization mistakes in Chinese Readme. [PR#172](https://github.com/hiddify/hiddify-next/pull/172) by [Locas](https://github.com/Locas56227)

## [0.10.0] - 2023-10-27

### New Features and Improvements

- Added Basic region-based routing rules
  - Based on your selected region (Iran, China or Russia), local ip and domains are bypassed.
- Redesigned Logs page
  - Now you're able to pause stream and clear logs. Also logs are delivered more consistently, with less resource consumption.
- Added tag of selected outbound of selectors to proxies page
  - Selected outbound tag of selectors like URLTests are now shown in other selectors as well.
- Added color to delay number in proxies page
- Memory limit option
  - Limit sing-box core memory usage.
- Revamped theme preferences settings
- Added initial iOS implementation. [PR#98](https://github.com/hiddify/hiddify-next/pull/98) by [GFWFighter](https://github.com/GFWFighter)
- Added Russian region
- Added Terms and Conditions and Privacy policy to about page

### Bug Fixes

- Removed reconnection on auto profile updates
- Fixed filtering logs by level
- Fixed localization mistakes in Russian. [PR#95](https://github.com/hiddify/hiddify-next/pull/95) by [solokot](https://github.com/solokot)
- Fixed localization mistakes in Russian. [PR#74](https://github.com/hiddify/hiddify-next/pull/74) by [Elshad Guseynov](https://github.com/lifeindarkside)

[0.12.0.dev]: https://github.com/hiddify/hiddify-next/releases/tag/v0.12.0.dev
[0.11.1]: https://github.com/hiddify/hiddify-next/releases/tag/v0.11.1
[0.11.0]: https://github.com/hiddify/hiddify-next/releases/tag/v0.11.0
[0.10.0]: https://github.com/hiddify/hiddify-next/releases/tag/v0.10.0
