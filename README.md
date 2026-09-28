# Yoru 夜

A calm planner for your Mac: plans, time, habits and notes in one place, with
a moon rabbit who keeps you company. It's free, there's no account, and
everything stays on your Mac, encrypted.

This repository holds Yoru's installers, and nothing else.

## Download

Which Mac do you have? Apple menu → About This Mac → Chip:

- **Apple M1, M2, M3, M4 or later:
  [download Yoru for Apple silicon](https://github.com/Rabadakku/yoru-releases/releases/latest/download/Yoru-arm64.dmg)**
- **Intel:
  [download Yoru for Intel](https://github.com/Rabadakku/yoru-releases/releases/latest/download/Yoru-x64.dmg)**

Both are the newest version. What's in it, and every version before:
[releases](https://github.com/Rabadakku/yoru-releases/releases).

## Install

1. Open the `.dmg` and drag Yoru into Applications.
2. Open Yoru. macOS says it can't check it, because Yoru isn't signed with an
   Apple developer certificate yet: click **Done**.
3. Open System Settings → Privacy & Security, scroll down to "Yoru was
   blocked…", click **Open Anyway**, and confirm. You only do this once.

If macOS says Yoru "is damaged and can't be opened", run this in Terminal,
then open it again:

    xattr -dr com.apple.quarantine /Applications/Yoru.app

## Updates

Yoru tells you when there's a new version, in its status bar and in Settings.
Click **Update**: it downloads the new Yoru, checks it's exactly the one
published here, and **Restart to update** puts it in place and opens it. Your
data stays. macOS then asks once about "Yoru Safe Storage", the key to your
vault: enter your Mac's password and click **Always Allow**.

Before 2.2.0, Yoru couldn't update itself: quit it, then drag the new one into
Applications, replacing the old one. From then on it updates itself.

## Help and ideas

In Yoru, use Help → Report a Bug or Help → Suggest an Idea. Or
[open an issue](https://github.com/Rabadakku/yoru-releases/issues) here.
