# Orbit

**Your Android, at home on your Mac.**

Orbit connects your Android phone and your Mac so they work like one. Read and answer messages, pick up calls, copy on one and paste on the other, and move tabs and files between them — without reaching for your phone.

## Download

| Device | Download |
|---|---|
| **Mac** (disk image) | [Orbit-macOS.dmg](https://github.com/Ansh1902396/orbit-releases/releases/latest/download/Orbit-macOS.dmg) |
| **Mac** (zip, alternative) | [Orbit-macOS.zip](https://github.com/Ansh1902396/orbit-releases/releases/latest/download/Orbit-macOS.zip) |
| **Android** | [Orbit-Android.apk](https://github.com/Ansh1902396/orbit-releases/releases/latest/download/Orbit-Android.apk) |
| Checksums | [SHA256SUMS.txt](https://github.com/Ansh1902396/orbit-releases/releases/latest/download/SHA256SUMS.txt) |

Release notes for every version are on the [Releases page](https://github.com/Ansh1902396/orbit-releases/releases).

## What it does

- **Notifications, with reply** — your phone's notifications appear on your Mac. Reply to messages right from the banner.
- **Calls on your Mac** — incoming calls ring on your Mac and you can answer or decline them there. Click any phone number on your Mac to dial it from your phone.
- **Shared clipboard** — copy on one device, paste on the other. A clipboard history keeps your recent items close at hand.
- **Keep browsing** — send the page you're reading from your phone to your Mac, or from your Mac to your phone, and carry on where you left off.
- **Drag and drop files** — drop a file onto Orbit to send it to your phone, and share files from your phone straight to your Mac.

## Install

### On your Mac

1. Download **Orbit-macOS.dmg** and open it.
2. Drag **Orbit** into the **Applications** folder.
3. Open Orbit from Applications. The first time, macOS will say it can't verify the app — this is expected, because this early version isn't notarized by Apple yet.
   - **macOS 15 or later:** open **System Settings › Privacy & Security**, scroll down and click **Open Anyway** next to the message about Orbit, then confirm.
   - **macOS 14:** right-click (or Control-click) Orbit in Applications, choose **Open**, then click **Open** again.
4. Orbit lives in your menu bar.

### On your Android phone

1. On your phone, download **Orbit-Android.apk**.
2. When asked, allow your browser to **Install unknown apps** (you can turn this off again afterwards).
3. Open the downloaded file and tap **Install**.
4. Open Orbit and allow the permissions it asks for.
5. If Android won't let you turn on notification access for Orbit (Android 13 and later can block this for apps installed outside the Play Store), go to **Settings › Apps › Orbit**, tap the **⋮** menu, choose **Allow restricted settings**, and try again.

### Connect them

Make sure your phone and Mac are on the **same Wi-Fi network**, open Orbit on both, and check that the code shown on your phone matches the one on your Mac. Confirm on both, and you're done — they'll reconnect on their own from now on.

## Requirements

- **Mac:** macOS 14 Sonoma or later, on a Mac with Apple silicon (M1 or newer)
- **Phone:** Android 10 or later

## Privacy

- **No account.** There's nothing to sign up for.
- **No cloud.** Your phone and Mac talk directly to each other over your own network. Nothing passes through our servers — there aren't any.
- **Encrypted end to end.** Everything sent between your devices is encrypted, and only devices you've paired can connect.

## Checking your download

Each release includes a `SHA256SUMS.txt` file. To confirm a download wasn't altered, compare its fingerprint with the one listed there:

- **Mac:** open Terminal and run `shasum -a 256 ~/Downloads/Orbit-macOS.dmg`
- **Android / other:** any SHA-256 checksum tool works.
