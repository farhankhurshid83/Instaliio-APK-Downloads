# Instaliio APK Downloads

Public APK downloads and checksums for Instaliio. No application source code.

## Current Pure Native Release APK

**Instaliio 1.0.4+5 (Pure Native Android DPC Signed Release)** - High performance native build (`versionCode 5`) with APK v2 signature scheme.

- [Download Pure Native Signed Release APK](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/Instaliio-Customer-Release.apk)

### Complete Features & Fixes (`1.0.4+5`):
- **App Release Version**: `1.0.4+5` (`versionCode: 5`)
- **Hardening, Connectivity & Alert Reliability**:
  - Updated FRP Google Account ID (`farhankhurshid0000@gmail.com`) and locked Developer Options / network reset settings, plus real-time `ContentObserver` tamper reporting for `DEVELOPMENT_SETTINGS_ENABLED` / `ADB_ENABLED`.
  - Silenced false `alert_tamper` sirens on routine Wi-Fi/cellular disconnect/reconnect, fixed Pakistan (`Asia/Karachi`, `+05:00`) countdown parsing & pre-due (`alert_pre_due`) background alerts within the final 24h, and fixed `LockActivity` Emergency/Code keypad cancellation & balance display.
  - Added full Schedule & Settings tabs, QR pairing scan handler, instant Lock/Unlock command execution before background location lookup, non-blocking reminder schedule sync (`migrations/182` & `migrations/173` fallback), 24h-cooldown battery exemption prompt + Settings indicator, and duplicate FCM push sync coalescing.
- **Fixed Remote Web Handset Release**:
  - Restored missing RPC publishable key configuration (`rpcConfiguration` / `ensureRpcConfigured`) so verified backend release acknowledgements (`emi_acknowledge_device_release`) succeed immediately.
  - Triggers immediate cleanup upon receiving `RELEASE_DEVICE` in heartbeat, FCM push (`RELEASE_DEVICE` / `LOCK` / `UNLOCK` / `SYNC_STATUS`), Wi-Fi reconnect, or `Check Online Unlock` / `Check Status`.
  - Added async polling & OEM-safe Device Owner/Admin retirement (`LOCK_TASK_MODE_NONE`, `clearFactoryResetProtectionPolicy`, `clearDeviceOwnerApp`, `removeActiveAdmin`, `ACTION_DELETE` uninstall prompt).
  - Auto-exits `LockActivity` when unlocked/released and adds a manual `Check Online Unlock` button directly on the lock screen.
- **APK v2 Signature Scheme**: Verified by `apksigner` for Android Enterprise 6-tap QR setup compatibility.
- **Direct Shop Owner Call & Emergency Dialer**: Confirmation dialog for shop calls and in-app emergency keypad.
- **In-App Wi-Fi Settings Panel**: Network panel whitelisted in LockTask mode.
- **Offline Unlock / Master Codes + Urdu Voice Alerts**.

### Checksums (`Instaliio-Customer-Release.apk`):
- **APK File HEX SHA-256**: `a018060cfb354fd807984b38edbde6b17f4b8055a633f2bde5b01bc3d2fa6772`
- **APK File Base64 URL-Safe (No Padding)**: `oBgGDPs1T9gHmEs47b3msX9LgFWmM_K95bAbw9L6Z3I`
- **Signing Certificate SHA-256 (`PROVISIONING_DEVICE_ADMIN_SIGNATURE_CHECKSUM`)**: `yWNhp9yj0RwBPlWi1ikI8ouWjFCx1uVBusy8i62By8A` (`c96361a7dca3d11c013e55a2d62908f28b968c50b1d6e541baccbc8bad81cbc0`)
