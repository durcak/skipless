# Skipless

Skipless is a Safari extension that makes YouTube videos start right away,
without ads.

**[Get Skipless on the App Store](https://apps.apple.com/app/id6827079651)**
for iPhone and iPad (iOS and iPadOS 18 or later). It's free.

The Mac version is in App Review. Until it's out, try the test build:
**[Download Skipless.zip](https://github.com/durcak/skipless/releases/latest/download/Skipless.zip)**
(macOS 15 Sequoia or later, Apple silicon and Intel)

## Set up on iPhone and iPad

1. Install Skipless from the App Store and open it once.
2. In Settings > Apps > Safari > Extensions > Skipless, turn on
   **Allow Extension** and set youtube.com to **Allow**.
3. Open youtube.com in Safari and play a video. It should start right away,
   without an ad.

Skipless works in Safari only; the YouTube app doesn't run Safari extensions.
To pause Skipless, tap the page menu next to the address, then Skipless, and
turn off **Block ads on youtube.com**.

## Install the Mac test build

This test build isn't from the App Store and isn't checked by Apple, so it
takes a few extra steps.

1. Unzip the download and move Skipless.app to your Applications folder.
2. Open Skipless.app. macOS blocks it ("Apple could not verify..."). Click
   Done.
3. Open System Settings > Privacy & Security, scroll down and click
   **Open Anyway** next to Skipless, then confirm with your password. The
   Skipless window opens; keep it open for the next steps.
4. In Safari, choose Safari > Settings > Advanced and tick
   **Show features for web developers**.
5. In Safari > Settings > Developer, tick **Allow unsigned extensions** and
   enter your password.
6. In Safari > Settings > Extensions, tick **Skipless**.
7. Open youtube.com, click the Skipless icon in the Safari toolbar and choose
   **Always Allow on This Website**.
8. Turn off any other ad blocker for YouTube, then play a video. It should
   start right away, without an ad.

Safari turns *Allow unsigned extensions* off every time it quits. After you
restart Safari, repeat step 5, and step 6 if Skipless is no longer ticked.

To pause Skipless, click its icon and turn off **Block ads on youtube.com**.
To uninstall it, move Skipless.app to the Trash.

## Feedback

Found a video with an ad, or one that starts slowly?
[Open an issue](https://github.com/durcak/skipless/issues) and include your
device and its macOS or iOS version.

## Privacy

Skipless collects no data. Read the [privacy policy](privacy.md).

Skipless is not affiliated with YouTube or Google.
