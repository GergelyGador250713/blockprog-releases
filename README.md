# BlockProg

Deadlines, DataLab Tasks and the learning log in one desktop app, for the ADS&AI block at BUas.

This repository only holds the installers. Get the newest one from
[**Releases**](https://github.com/GergelyGador250713/blockprog-releases/releases/latest).

## Install

- **Windows:** download `BlockProg_<version>_x64-setup.exe` and run it. The installer isn't signed, so Windows may
  say "Windows protected your PC": choose **More info**, then **Run anyway**.
- **macOS:** download the `.dmg` (`aarch64` is for Macs with Apple silicon, `x64` for Intel ones), open it and drag
  BlockProg to Applications. The app isn't signed by Apple, so the first time macOS refuses to open it: go to
  **System Settings › Privacy & Security** and choose **Open Anyway** next to BlockProg. If macOS says BlockProg "is
  damaged", run this once in Terminal: `xattr -dr com.apple.quarantine /Applications/BlockProg.app`

## Updates

BlockProg looks for a new version when it starts and once a day. When one is ready it says so: choose
**Restart to update**. You can also check yourself in **Settings › App › Updates**.

## Your data

Everything stays on your computer: your tasks, settings and drafts in BlockProg's own app-data folder, and your
Brightspace calendar link and YouTrack token in your system's keychain (Credential Manager on Windows, Keychain on
a Mac). Settings › App › Backup saves it all to a file, without the link and the token.
