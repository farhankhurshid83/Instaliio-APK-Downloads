# Instaliio APK Downloads

Public APK downloads and checksums for Instaliio. No application source code.

## Current release-mode APK

**Instaliio 1.0.3+4 (DPC Hardened Release)** - split-ABI optimized Android release build.

- [Download Primary ARM64 APK (27.1MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-release.apk)
- [Download ARMv7 32-bit APK (22.8MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-armv7-release.apk)
- [Release Tag](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/releases/tag/v1.0.3-build.4-flutter-release)

### Fixes & Enhancements:
- Android Native DPC Hardening & FRP Lock protection (`admin@elitepensolutions.com`).
- Anti-Tamper & OS Keyguard Lockdown features (`DISALLOW_FACTORY_RESET`, `DISALLOW_SAFE_BOOT`, `DISALLOW_DEBUGGING_FEATURES`, `DISALLOW_USB_FILE_TRANSFER`, `setUninstallBlocked`).
- Hidden native app icon from home launcher menu.
- Persistent preferred Kiosk Home launcher (`addPersistentPreferredActivity`) when locked.
- Immediate Direct Boot lock on device restart (power off -> power on).
- Permanent Safe Mode lockdown (`DISALLOW_SAFE_BOOT` in protected mode).
- Native Urdu Kiosk Lock Screen (`LockActivity.kt`) with Urdu text, Emergency call dialer, and shop payment QR display under `startLockTask()`.
- Re-enabled 6-Digit Pairing Flow with anti-spoofing `widevine_id` and `hardware_serial` fingerprint payload to Supabase Edge Function `/functions/v1/emi-pair`.

### SHA-256 Checksums:
- `instaliio-1.0.3-4-release.apk` (ARM64): `bee4f6c107a441535e40e917d675d11661d406ad83dbc7d0d355f44fb182edab`
- `instaliio-1.0.3-4-armv7-release.apk` (ARMv7): `9508158375eee8c9ca1719584c082342b2a549bdab8732baaf41d8f8d6cb398f`
