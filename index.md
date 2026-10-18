---
title: SVR Player
---

**SVR Player** is a VR video player for Meta Quest. It plays flat, 3D (SBS / OU), 180° and 360° videos, with subtitles and multiple audio tracks.

**SVR Link** is a free companion app for your PC (Windows now, Linux and macOS later). It lets you watch videos stored on your PC in SVR Player over your home Wi-Fi, without copying files to the headset.

## Download SVR Link

| System | Download |
| --- | --- |
| Windows 10 / 11 (64-bit) | [SVRLink-windows-x64.zip](https://github.com/OWNER/REPO/releases/latest/download/SVRLink-windows-x64.zip) |
| Linux (64-bit) | Coming soon |
| macOS | Coming soon |

All versions and release notes: [Releases](https://github.com/OWNER/REPO/releases). The PC and the headset must be on the same local network.

## How to use SVR Link (Windows)

1. Unzip the archive to any folder and run `svrlink.exe`. Keep `ffmpeg.exe` and `ffprobe.exe` next to it (they make video previews).
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
3. When Windows Firewall asks, allow access on **private networks**. SVR Player finds your PC via UDP port 8065 and plays videos via TCP port 8064.
4. Add the folders with your videos in SVR Link.
5. In SVR Player on the headset, open the **SVRLink** tab and enter the PIN shown in SVR Link.

If the headset cannot find your PC, check that both are on the same Wi-Fi network (not a guest network) and that your router does not isolate wireless clients ("AP isolation").

## Privacy

SVR Player and SVR Link do not collect personal data. See the [Privacy Policy](privacy.html).

## Contact

elfenliedgames@gmail.com
