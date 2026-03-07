# strawberry-autobuild-mac



This repository provides unofficial macOS builds of Strawberry Music Player.

**Downloads:** You can download the latest unofficial builds from the [Releases]([https://github.com/Leohige/strawberry-autobuild-mac/releases](https://github.com/gus74vv/strawberry-autobuild-mac/releases)) page.

> **Looking for Windows builds?** Check out [@stm7128/strawberry-autobuild-windows](https://github.com/stm7128/strawberry-autobuild-windows) for unofficial Windows builds.

Official builds for macOS are not currently available directly from the main project for all users. However, instructions for building from source can be found in the [official repository](https://github.com/strawberrymusicplayer/strawberry).

## Available Builds

This repository provides the following types of macOS builds. Builds are automatically generated daily (and on pushes to the main branch of this repository) from the latest code of the [official Strawberry repository](https://github.com/strawberrymusicplayer/strawberry).

| macOS Version | Architecture | Build Type | Notes |
|---------------|--------------|------------|-------|

| macOS 15 (Sequoia) | arm64 (Apple Silicon) | Release | Recommended for Apple Silicon Macs (M1/M2/M3) |

## Important Notes

- **Unsigned Builds:** These builds are **NOT signed or notarized** by Apple. macOS will block them by default. To open:
  1. Right-click the DMG file and select "Open", or
  2. Run `xattr -cr /path/to/strawberry.dmg` in Terminal before opening
  3. After mounting, if the app is still blocked, run `xattr -cr /Applications/Strawberry.app`

- **Retention Policy:** Only the last 30 days of builds are kept to manage storage. Older releases are automatically deleted.

## Issues and Support

- **For bugs, issues, or feature requests** related to Strawberry's functionality, please submit them on the [official Strawberry Issues page](https://github.com/strawberrymusicplayer/strawberry/issues). The developers at Strawberry may be able to assist with issues via GitHub.
  
  *Examples: Music playback stutters, a specific file format doesn't work, a feature request for a new audio output.*

- **If you encounter issues specifically with the build process**, the DMG files, or the availability of builds provided by this repository, please [open an issue here](https://github.com/Leohige/strawberry-autobuild-mac/issues).
  
  *Examples: The DMG fails to open, a downloaded file is corrupt, a scheduled build has failed.*

**This repository does not offer official support for Strawberry Music Player itself.**

## License

Strawberry Music Player is licensed under the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html). These unofficial builds are also provided under the terms of the GPLv3.

## Support Official Development

Thank you for using this unofficial build of Strawberry Music Player. If you enjoy the software, please consider supporting the official development of Strawberry Music Player through the following options. Supporting the official developer directly helps ensure the continued development and maintenance of Strawberry.

- [Patreon](https://www.patreon.com/jonaskvinge) - Supporters often receive access to official builds; check their page for current benefits and tiers.
- [GitHub Sponsors](https://github.com/sponsors/jonaski)
- [Ko-fi](https://ko-fi.com/jonaskvinge) - Official builds may also be available to supporters here; please see their page for details.
- [PayPal](https://paypal.me/jonaskvinge)



