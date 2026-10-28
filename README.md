
# Cleaner Keys

**Clean your keyboard. Not your documents.**

Cleaner Keys is a tiny macOS app that temporarily locks your keyboard so you can wipe it down without typing random characters. One click to start cleaning, one click to stop when you're done.

[**Download for macOS**](https://github.com/YongVuthivathnakk/Cleaner-Keys-Releases/releases/latest/download/CleanerKeys.dmg)

Windows version: coming soon.

Website: [https://cleaner-keys-next-app.vercel.app](https://cleaner-keys-next-app.vercel.app/)

---

## Features

- **One-click lock.** Start cleaning, wipe away, click Done.
- **Never records keystrokes.** While locked, key presses are simply ignored. Nothing is saved, logged, or sent anywhere.
- **Tiny and native.** Built with Swift and SwiftUI. No account, no network access, no background services.
- **Quits cleanly.** Closing the window or pressing Cmd+Q always releases your keyboard.

## Requirements

- A Mac with Apple silicon (M1 or later)
- macOS 14 or later

Intel Macs are not supported in this release.

## Install

1. Download `CleanerKeys.dmg` using the button above, or from the [latest release](https://github.com/YongVuthivathnakk/Cleaner-Keys-Releases/releases/latest).
2. Open the downloaded file.
3. Drag **Cleaner Keys** onto the **Applications** folder.
4. Open **Cleaner Keys** from Applications.

### If macOS says the app can't be opened

> Remove this section once the app is signed and notarized.

This build is not notarized by Apple, so macOS may block it the first time:

1. Try to open the app once, then dismiss the message.
2. Open **System Settings > Privacy & Security**.
3. Scroll down and click **Open Anyway** next to the app's name.
4. Confirm with your password.

You only need to do this once.

## Allow Accessibility access (one time)

macOS requires your permission before any app can ignore key presses. Cleaner Keys needs it to work.

1. Click **Start cleaning**. If permission is missing, a dialog appears.
2. Click **Open**. System Settings opens to **Privacy & Security > Accessibility**, and a small floating panel appears with the app icon.
3. Drag the icon from that panel into the list in System Settings, or click **+** and choose the app from Applications.
4. Switch the toggle **on**.
5. Quit Cleaner Keys and open it again, then click **Start cleaning**.

## Privacy

- Cleaner Keys does **not** record, store, or transmit anything you type.
- It has no network code and collects no analytics or personal data.
- The only permission it asks for is Accessibility, which macOS requires for any app that needs to intercept key presses.

## Verify your download (optional)

Each release lists a SHA-256 checksum in its notes. To check your file, run this in Terminal:

```
shasum -a 256 ~/Downloads/CleanerKeys.dmg
```

The result should match the checksum on the [release page](https://github.com/YongVuthivathnakk/Cleaner-Keys-Releases/releases/latest).

## Troubleshooting

**The app is switched on in Accessibility but still asks for permission.**
Select it in the list, click **-** to remove it, then add it again. Quit and reopen the app afterwards.

**I moved or updated the app and it asks for permission again.**
macOS ties permission to the specific app file. Remove the old entry from the Accessibility list and add the new copy.

**My keyboard is stuck locked.**
Use the trackpad to click **Done**, or quit the app from the Dock (right-click its icon, then **Quit**). Quitting always unlocks the keyboard. The power and Touch ID button cannot be blocked by any app.

**The download link doesn't work.**
Open the [Releases page](https://github.com/YongVuthivathnakk/Cleaner-Keys-Releases/releases) and download `CleanerKeys.dmg` from the Assets list.

## Uninstall

1. Quit Cleaner Keys.
2. Drag it from Applications to the Trash.
3. Optional: in **System Settings > Privacy & Security > Accessibility**, select it and click **-**.

## Support

Questions or bugs? [Open an issue](https://github.com/YongVuthivathnakk/Cleaner-Keys-Releases/issues) in this repository or email [your@email.com](mailto:your@email.com).

## License

Provided as is, without warranty of any kind. © 2026 Yong Vuthivathnakk. All rights reserved.
