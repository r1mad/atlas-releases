# Atlas

Atlas is a macOS menu bar utility app: system monitor, window and app switching,
clipboard, Dynamic Island–style notch, screenshots and other everyday tools.

This repository only hosts release downloads. Atlas checks it for updates.

## Install

1. Download `Atlas.dmg` from the [latest release](https://github.com/r1mad/atlas-releases/releases/latest).
2. Open the DMG and drag **Atlas** into **Applications**.
3. Atlas is not signed with an Apple Developer ID, so macOS blocks the first launch:
   - Right-click (or Control-click) Atlas in Applications and choose **Open**, then **Open** again, **or**
   - try to open it once, then go to **System Settings → Privacy & Security** and click **Open Anyway**.

Requires macOS 14 or later (Apple silicon and Intel).

## Permissions it may ask for

Atlas asks only when you turn on a feature that needs it:

- **Accessibility** – window management, switcher, keyboard shortcuts
- **Screen Recording** – screenshots, window previews, screen recording
- **Automation (Finder etc.)** – actions that control other apps
- **Camera** – only for features that use it, which are off by default
- **Calendar** – calendar in the notch, if enabled
- **Notifications**

You can revoke any of these in System Settings → Privacy & Security.

## Privacy

- Personal settings (addresses, device and account choices, feeds) stay on your Mac
  and are never included in settings export or backups. Tokens and keys are stored
  in the macOS Keychain.
- Optional features such as the away alert and bot updates are **off by default**.
- The update check reads the public GitHub API
  (`api.github.com/repos/r1mad/atlas-releases/releases/latest`) without any token.
  You can turn automatic checks off in Settings. Updates open this release page;
  nothing is installed automatically.
- No analytics or telemetry.

## License

Atlas is a GPL-3.0 fork of [Vorssaint](https://github.com/vorssaint/vorssaint-utils). Source code is available on request.
