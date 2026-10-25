# Blackcap

A little island for your MacBook's notch: your music, a focus timer, a file shelf, your clipboard, a camera mirror and a teleprompter, right under the camera.

## Download

**[Download Blackcap](https://github.com/vimall22/blackcap/releases/latest/download/Blackcap.dmg)**. The link always gives you the newest version.

You need:
- a MacBook with a notch;
- macOS 14 (Sonoma) or later;
- the Spotify app, for the music features.

## Install (once, about two minutes)

1. Open **Blackcap.dmg** from your Downloads.
2. In the window that opens, drag **Blackcap** onto the **Applications** folder.
3. Open your Applications folder and double-click **Blackcap**.
4. macOS says *"Apple could not verify 'Blackcap' is free of malware"*. That's because Blackcap isn't notarised by Apple, which needs a paid developer account. Click **Done**.
5. Open **System Settings → Privacy & Security** and scroll down to *"Blackcap was blocked"*. Click **Open Anyway**, then confirm with your password or Touch ID. Click **Open** once more.

You only do this once. Updates install without it.

If you opened Blackcap straight from the disk image, it offers to move itself into Applications. Say yes: it needs to live there to update itself. Afterwards you can delete the disk image.

## Permissions

Blackcap asks the first time you use each feature:

| Permission | What it's for |
|---|---|
| Control Spotify | Showing and controlling what's playing |
| Camera | The camera mirror, only while it's open. Photos are saved only when you click the camera button. |
| Microphone | The teleprompter listens to how loud you are, so it can pause when you stop talking. Nothing is recorded. |
| Spotify's sound | Beat-following (off until you turn it on) moves the light with the music. Nothing is recorded. |

## Using it

- **Open it:** hover over the notch.
- **The menu bar icon:** Settings, Launch at Login, Check for Updates and Quit.
- **Settings:** every feature has a switch, with how much battery it costs beside it.

## Updates

Blackcap checks for a new version once a day. When there is one, the notch tells you. To install it:
1. Open the notch and click **Update**.
2. Read what's new, then click **Install Update**.

It restarts in a few seconds, keeping your settings and permissions. You can also click **Check for Updates…** in the menu bar.

## Privacy

Blackcap collects nothing. It goes online for three things:
- the album art for what's playing, from Spotify;
- synced lyrics from [LRCLIB](https://lrclib.net), which gets the song's title, artist, album and length;
- one update check a day, here on GitHub.

Your clipboard history stays in memory and is never saved.

## Uninstall

1. Turn off **Launch at Login** in the menu bar icon.
2. Quit Blackcap.
3. Drag **Blackcap** from Applications to the Bin.

Photos from the camera mirror are in `Pictures/Blackcap`.

---

Made by Vimall for friends. Something not working? Message me. Blackcap isn't affiliated with Apple or Spotify.
