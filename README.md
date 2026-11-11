# Prepd for Mac and Windows

Prepd is a meeting note-taker. It transcribes on your own computer and writes notes with your
own Claude account. This page only hosts the installers and updates.

**[Download for Mac](https://github.com/Ehzerah/prepd-releases/releases/latest/download/Prepd-mac.dmg)**
· **[Download for Windows](https://github.com/Ehzerah/prepd-releases/releases/latest/download/Prepd-windows-setup.exe)**

- Mac: Apple silicon (M1 or newer) and macOS 15 or later.
- Windows: Windows 11, 64-bit. Windows 10 may work but hasn't been tested.

## Install on a Mac

1. Open `Prepd-mac.dmg` and drag **Prepd** into **Applications**. Run it from Applications,
   not from the disk image, or it can't update itself.
2. The first time you open it, macOS says it can't check the developer. Open
   **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to
   Prepd, then confirm.
3. Allow microphone and screen & system audio recording when Prepd asks. It needs them to
   hear both sides of a call.
4. In Prepd's **Settings**: sign in to Claude under AI, and under Transcription click the
   download button for the Whisper model (550 MB, once).

## Install on Windows

1. Run `Prepd-windows-setup.exe`. Windows may say it "protected your PC", because the
   installer isn't signed by a known publisher: click **More info**, then **Run anyway**.
   It installs for your user only, so it doesn't ask for an administrator password.
2. Open **Prepd** from the Start menu. If Windows asks, allow microphone access.
3. In Prepd's **Settings**: sign in to Claude under AI, and under Transcription click the
   download button for the Whisper model (550 MB, once).

## Updates

Prepd checks for a new version when you open it and every 30 minutes, downloads it in the
background and installs it, never while a meeting is being recorded. On Windows a small
progress window appears and Prepd reopens by itself. After an update, a "What's new" tab
lists the changes. Release notes for every version are under
[Releases](https://github.com/Ehzerah/prepd-releases/releases).
