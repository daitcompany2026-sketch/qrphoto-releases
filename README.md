# QRPhoto Receiver — Downloads

QRPhoto copies photos and videos from an iPhone to your own Mac or Windows PC over the same
Wi-Fi. No account, no sign-in, no cloud server: the QR code only pairs the phone with the
computer in front of you.

This repository hosts download files only. There is no source code here.

## Mac receiver

|  |  |
| --- | --- |
| Version | 1.0 (build 1) |
| File | `QRPhoto-Mac-Receiver.zip` (1.92 MB) |
| Requires | macOS 14 Sonoma or later, Apple silicon or Intel |
| Release page | https://github.com/daitcompany2026-sketch/qrphoto-releases/releases/tag/v1.0.0 |
| Direct download | https://github.com/daitcompany2026-sketch/qrphoto-releases/releases/download/v1.0.0/QRPhoto-Mac-Receiver.zip |
| SHA-256 | `a4560b5771e03427e538b9f6266f6b0cf515f82ecd0274c39b0f01b20526d306` |

The zip contains `PhotoBackupReceiver.app`. The bundle keeps the project's earlier internal
name; the app itself opens and is listed as **QRPhoto**.

### Install

1. Download `QRPhoto-Mac-Receiver.zip` and double-click it. It unzips to
   `PhotoBackupReceiver.app`.
2. Drag the app to your Applications folder (or run it from the unzipped folder).
3. Open the app and allow incoming connections if macOS asks. The build is code-signed but
   not notarized, so a copy downloaded from the internet may be held by Gatekeeper on first
   launch: Control-click (or right-click) the app, choose **Open**, then **Open** again.
4. Choose the folder that should receive your photos. The receiver shows a QR code and stays
   listening.

### Send from the iPhone

1. Open QRPhoto on the iPhone connected to the same Wi-Fi (a personal hotspot works too).
2. Tap **QR 찍기** and scan the code on the Mac.
3. Pick photos or videos and send. The first 100 items are free; passes remove the limit.

## Windows receiver

The Windows receiver is not published in this repository yet. When it is, it will appear on
the release page above.

## Documents

- Privacy policy: https://slow-sight-b79.notion.site/QRPhoto-Privacy-Policy-418ecdd6d1fe8153bd90ea02511436d4
- Terms of service: https://slow-sight-b79.notion.site/QRPhoto-Terms-of-Service-418ecdd6d1fe8163a9d4c7fecf57525b

## Contact

DAIT — dait.company2026@gmail.com
