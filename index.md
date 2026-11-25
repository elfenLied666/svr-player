---
title: SVR Player
---

**SVR Player** is a VR video player for Meta Quest. It plays flat, 3D (SBS / OU), 180° and 360° videos, with subtitles and multiple audio tracks.

## Download SVR Player

[Download on Meta Horizon Store](https://www.meta.com/experiences/1407967885740014/)

**SVR Link** is a free companion app for your PC (Windows, Linux, and macOS). It lets you watch videos stored on your PC in SVR Player over your home Wi-Fi, without copying files to the headset.

## Download SVR Link

| System | Download |
| --- | --- |
| Windows 10 / 11 (64-bit) | [SVRLink-windows-x64.zip](https://github.com/elfenLied666/svr-player/releases/latest/download/SVRLink-windows-x64.zip) |
| Linux (64-bit) | [SVRLink-linux-x64.zip](https://github.com/elfenLied666/svr-player/releases/download/v0.1.0/SVRLink-linux-x64.zip) |
| macOS | [SVRLink-macos.zip](https://github.com/elfenLied666/svr-player/releases/download/v0.1.0/SVRLink-macos.zip) |

All versions and release notes: [Releases](https://github.com/elfenLied666/svr-player/releases). The PC and the headset must be on the same local network.

## How to use SVR Link (Windows)

1. Unzip the archive to any folder and run `svrlink.exe`. Keep `ffmpeg.exe` and `ffprobe.exe` next to it (they make video previews).
2. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
3. When Windows Firewall asks, allow access on **private networks**. SVR Player finds your PC via UDP port 8065 and plays videos via TCP port 8064.
4. Add the folders with your videos in SVR Link.
5. In SVR Player on the headset, open the **SVRLink** tab and enter the PIN shown in SVR Link.

## How to use SVR Link (Linux)

1. Unzip `SVRLink-linux-x64.zip` to any folder. If needed, mark the binary as executable (`chmod +x svrlink`) and run `./svrlink`.
2. For video previews, install `ffmpeg` from your package manager (e.g. `sudo apt install ffmpeg`) or keep `ffmpeg` and `ffprobe` next to `svrlink`. (Without them, playback still works, just without thumbnails.)
3. If you use a firewall (such as `ufw`), allow **UDP port 8065** (discovery) and **TCP port 8064** (streaming) on your local network.
4. Add the folders with your videos in SVR Link.
5. In SVR Player on the headset, open the **SVRLink** tab and enter the PIN shown in SVR Link.

## How to use SVR Link (macOS)

1. Unzip `SVRLink-macos.zip` and open the app (you can move it to **Applications**).
2. If macOS blocks the launch ("unidentified developer"), right-click the app → **Open** → **Open** (or go to **System Settings → Privacy & Security → Open Anyway**).
3. If macOS asks for **Local Network** permission or Firewall access, click **Allow** (SVR Player uses UDP port 8065 and TCP port 8064).
4. For video previews, install `ffmpeg` (for example via Homebrew: `brew install ffmpeg`). Without it, playback still works, just without thumbnails.
5. Add the folders with your videos in SVR Link, then open the **SVRLink** tab in SVR Player on the headset and enter the PIN.

If the headset cannot find your PC, check that both are on the same Wi-Fi network (not a guest network) and that your router does not isolate wireless clients ("AP isolation").

## Support

If you enjoy SVR Player and SVR Link, you can support development on [Ko-fi](https://ko-fi.com/thaisqwen).

## Privacy

SVR Player and SVR Link do not collect personal data. See the [Privacy Policy](privacy.html).

## Contact

elfenliedgames@gmail.com
