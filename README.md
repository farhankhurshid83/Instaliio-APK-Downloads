# Instaliio APK Downloads

Public APK downloads and checksums for Instaliio. No application source code.

## Current release-mode APK

**Instaliio 1.0.3+4 (DPC Hardened Release)** - split-ABI optimized Android release build.

- [Download Primary ARM64 APK (27.1MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-release.apk)
- [Download ARMv7 32-bit APK (22.8MB)](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/raw/main/instaliio-1.0.3-4-armv7-release.apk)
- [Release Tag](https://github.com/farhankhurshid83/Instaliio-APK-Downloads/releases/tag/v1.0.3-build.4-flutter-release)

### Complete Fixes & Features:
- **Visible App Launcher Icon**: Re-enabled app launcher icon in home menu app drawer (`category.LAUNCHER`).
- **Eliminated Home Launcher Selection Prompt**: Disabled `LockHomeAlias` by default in unlocked state so setup & pairing never prompt "Select a Home app / Choose launcher".
- **Manual 6-Digit PIN Pairing Session Fix**: Allowed manual 6-digit PIN pairing to save customer details, shop details, and installment schedule cleanly without throwing Device Owner check exceptions.
- **Automatic Uninstallation Prompt on Release**: Triggers Android's native uninstaller prompt (`Intent.ACTION_DELETE`) automatically when handset payment release completes.
- **Direct Shop Owner Call**: Confirmation dialog prompt before making a direct phone call without opening system dialer pad.
- **In-App Custom Emergency Keypad**: Custom in-app dialer dialog (0-9, *, #, Clear, Call) for emergency numbers without leaving lock mode.
- **In-App Wi-Fi Settings Panel**: Internet connectivity panel (`Settings.Panel.ACTION_INTERNET_CONNECTIVITY`) whitelisted in LockTask for seamless network access.
- **Bypassed Flutter Location Popup**: Disabled Flutter UI permission onboarding popup dialog since Device Owner auto-grants location permission natively.
- **Clean Location Notification**: Streamlined ongoing notification without misleading "Stop sharing" button.
- **Mobile Lag/Hanging Fix**: Cached `addPersistentPreferredActivity` so system HOME launcher registration runs once without background loop overhead.
- **Background Lock Fix**: Enforced `LockActivity` to immediately launch to front when status is `locked` regardless of background state.
- **Auto-Grant Permissions**: Programmatic auto-grant for ALL permissions during setup (`ACCESS_FINE_LOCATION`, `ACCESS_BACKGROUND_LOCATION`, `READ_PHONE_STATE`, `CAMERA`, `CALL_PHONE`, `POST_NOTIFICATIONS`).
- **Android Native DPC Hardening**: FRP Lock (`admin@elitepensolutions.com`), Anti-Tamper (`DISALLOW_FACTORY_RESET`, `DISALLOW_SAFE_BOOT`), Immediate Direct Boot lock.

### SHA-256 Checksums:
- `instaliio-1.0.3-4-release.apk` (ARM64): `094479bfe421d7357b67b71a71763e4a4a4c531e6a3ca9af79c836ae28c0e142`
- `instaliio-1.0.3-4-armv7-release.apk` (ARMv7): `7220a2f2ff525ddfc0e3fc845892625b984dfd33cde16c350cd1fa28183b2397`
