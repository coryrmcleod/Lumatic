# Lumatic

Android lighting app test builds. Download the APK from this repository's Releases page.

Lumatic supports RGB and white-temperature controls, rooms and fixtures, presets, routines, photo scenes, music effects, and location-based daylight settings. Version 0.1.9 includes the Solar Bot launcher icon and in-app logo.

## Compatibility

- Android 8.0 (API 26) or newer. Google Matter setup requires API 27 or newer, compatible hardware and Google Play services.
- Direct light control currently supports compatible WiZ bulbs on the same local network, with their permitted local-control configuration. WiZ secure-only local control is unsupported; Lumatic does not downgrade security.
- Google-owned Matter setup is separate from Lumatic's local-network controls. Commissioning alone does not add a controllable light to Lumatic. Matter compatibility has not been verified on physical hardware.
- Lightinginside/Smart Life/Tuya control and proprietary Bluetooth provisioning are not available in this build.

## Before testing

This is a debug-signed test build, not a production release. Back up your local setup before updating. Android may request permission to install an APK downloaded through your browser; installation remains your choice.

Phone-run routines and fades are best effort. Android sleep, battery restrictions, network availability and permissions can delay execution; this is not an always-on lighting controller. Alarm access does not guarantee timely network delivery. Music effects require an explicitly started foreground microphone session.

Local setup works without an account. Provisional invites do not grant or enforce shared device access. Backup imports require review, device revalidation and explicit automation re-enabling. No household data or credentials are included in this repository.

Check the release's SHA256SUMS.txt to verify your download. No source-code license is granted by this download repository.