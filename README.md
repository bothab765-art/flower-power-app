# Flower Power Android App

Package: `za.co.flowerpower.plett`
Target Android: API 36
Minimum Android: API 26

## What this is
This is the native Android wrapper for the Flower Power business app. The working HTML app is bundled locally in `app/src/main/assets`, so it launches from the Flower Power icon like a normal Android application and does not need to be extracted by the phone.

## Build via GitHub Actions
1. Put this project in a private GitHub repository.
2. Open the Actions tab and run **Build Flower Power Android**.
3. Download the `Flower-Power-Android` artifact.
4. `app-debug.apk` can be installed directly on an Android phone for testing.
5. Before Google Play production, configure a secure release/upload signing key and build a signed `.aab`.

## Google Play
Google Play requires new phone apps submitted after 31 August 2026 to target Android 16 / API 36. This project does.
New personal Play Console accounts created after 13 November 2023 normally require a closed test with at least 12 opted-in testers for 14 continuous days before production access.
