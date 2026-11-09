# Prepd for Mac

Prepd is a meeting note-taker. It transcribes on your Mac and writes notes with your own
Claude account. This page only hosts the installer and updates.

**[Download Prepd for Mac](https://github.com/Ehzerah/prepd-releases/releases/latest/download/Prepd-mac.dmg)**

Needs a Mac with Apple silicon (M1 or newer) and macOS 15 or later.

## Install

1. Open `Prepd-mac.dmg` and drag **Prepd** into **Applications**. Run it from Applications,
   not from the disk image, or it can't update itself.
2. The first time you open it, macOS says it can't check the developer. Open
   **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to
   Prepd, then confirm.
3. Allow microphone and screen & system audio recording when Prepd asks. It needs them to
   hear both sides of a call.
4. In Prepd's **Settings**: sign in to Claude under AI, and under Transcription click the
   download button for the Whisper model (550 MB, once).

## Updates

Prepd checks for a new version when you open it and every 30 minutes, downloads it in the
background and installs it, never while a meeting is being recorded. After an update, a
"What's new" tab lists the changes. Release notes for every version are under
[Releases](https://github.com/Ehzerah/prepd-releases/releases).
