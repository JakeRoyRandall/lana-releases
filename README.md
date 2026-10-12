# Lana for Android

Lana is your agent onchain: a voice agent for onchain money on Solana. This repository holds her Android downloads and nothing else. Android only.

## Download

| | Lana, the real app | Lana Demo, pretend money |
|---|---|---|
| **Clock In submission** (frozen) | [lana-clock-in.apk](https://github.com/JakeRoyRandall/lana-releases/releases/download/clock-in/lana-clock-in.apk) | [lana-demo-clock-in.apk](https://github.com/JakeRoyRandall/lana-releases/releases/download/clock-in/lana-demo-clock-in.apk) |
| **Latest** (rolling) | [lana.apk](https://github.com/JakeRoyRandall/lana-releases/releases/download/latest/lana.apk) | [lana-demo.apk](https://github.com/JakeRoyRandall/lana-releases/releases/download/latest/lana-demo.apk) |

Four files: two apps, each as the submitted build and as the latest build.

- **The hackathon submission** is the first row: the builds handed in to the Solana Mobile Clock In hackathon (closes 4:59 pm PT, 12 October 2026). Those files are frozen at submission and never change afterwards.
- **Latest** is the second row. These files are replaced as new features land.
- **Lana** (`com.saylana.app`) is the real app. You sign in, talk to her and add money. Real-money swaps and sends are closed in these builds.
- **Lana Demo** (`com.saylana.demo`) is a separate app with pretend money. It needs no account, no sign-in and no wallet, and every balance and transaction in it is simulated. Voice and live swap quotes are not connected in the Demo: tap **DEMO · fake funds**, then **Type instead** or one of the preset flows.

## Install

Open the `.apk` on your Android phone (Android 7 or newer). Android asks once to allow installs from your browser or Files app. The two apps can sit on the phone together: they have different package names and the same signing key.

## Verify

The release notes of [`clock-in`](https://github.com/JakeRoyRandall/lana-releases/releases/tag/clock-in) and [`latest`](https://github.com/JakeRoyRandall/lana-releases/releases/tag/latest) give each file's SHA-256, version code and the commit it was built from. GitHub also shows the SHA-256 beside each file.
