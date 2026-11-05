# Instaliio APK Downloads

Public APK downloads and checksums for Instaliio. No application source code.

## Current release-mode APK

**Instaliio 1.0.3+4 (DPC Hardened Release)** - split-ABI optimized Android release build.

- [Download Primary ARM64 APK (27.1MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-release.apk)
- [Download ARMv7 32-bit APK (22.8MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-armv7-release.apk)
- [Release Tag](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/releases/tag/v1.0.3-build.4-flutter-release)

### Features & Auto-Permissions:
- Automatic Programmatic Grant for ALL runtime permissions (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`, `ACCESS_BACKGROUND_LOCATION`, `READ_PHONE_STATE`, `CAMERA`, `POST_NOTIFICATIONS`) during Device Owner setup — **Zero manual permission prompts required**.
- Native Factory Reset Protection (FRP Lock) on Android 11+ (`admin@elitepensolutions.com`).
- Anti-Tamper & OS Keyguard Lockdown features (`DISALLOW_FACTORY_RESET`, `DISALLOW_SAFE_BOOT`, `DISALLOW_DEBUGGING_FEATURES`, `DISALLOW_USB_FILE_TRANSFER`, `setUninstallBlocked`).
- Hidden native app icon from home launcher menu.
- Persistent preferred Kiosk Home launcher (`addPersistentPreferredActivity`) when locked.
- Immediate Direct Boot lock on device restart (power off -> power on).
- Permanent Safe Mode lockdown (`DISALLOW_SAFE_BOOT`).
- Native Urdu Kiosk Lock Screen (`LockActivity.kt`) with Urdu text, Emergency call dialer, and shop payment QR display under `startLockTask()`.
- Re-enabled 6-Digit Pairing Flow with anti-spoofing `widevine_id` and `hardware_serial` fingerprint payload to Supabase Edge Function `/functions/v1/emi-pair`.
- Resolved Flutter deprecation warnings (`TickerMode` clean).

### SHA-256 Checksums:
- `instaliio-1.0.3-4-release.apk` (ARM64): `9e73cd27da910b4b08fba52d6bfb73d56e24fed6019b837e1aa80131bf1bbbc2`
- `instaliio-1.0.3-4-armv7-release.apk` (ARMv7): `a9e5738ea9b75309dee2bf260df42fe636ffaf4082360c87558ea5982ed83914`
