# Instaliio APK Downloads

Public APK downloads and checksums for Instaliio. No application source code.

## Current Pure Native Release APK

**Instaliio 1.0.4+5 (Pure Native Android DPC Signed Release)** - High performance native build (`versionCode 5`) with APK v2 signature scheme.

- [Download Pure Native Signed Release APK](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/Instaliio-Customer-Release.apk)

### Complete Features & Fixes (`1.0.4+5`):
- **App Release Version**: `1.0.4+5` (`versionCode: 5`)
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
- **APK File HEX SHA-256**: `5dc58691e8965c4f008dbb9244ed8935b37923fcb04b49b869f67cda05cc43a5`
- **APK File Base64 URL-Safe (No Padding)**: `XcWGkeiWXE8AjbuSRO2JNbN5I_ywS0m4afZ82gXMQ6U`
- **Signing Certificate SHA-256 (`PROVISIONING_DEVICE_ADMIN_SIGNATURE_CHECKSUM`)**: `yWNhp9yj0RwBPlWi1ikI8ouWjFCx1uVBusy8i62By8A` (`c96361a7dca3d11c013e55a2d62908f28b968c50b1d6e541baccbc8bad81cbc0`)
