# Privacy Policy — Hearth

**Effective date:** 16 April 2026
**Developer:** Seventh Chronicle Ltd

## Summary

Hearth does not collect, transmit, or share any personal data. All data stays on your device.

## Data storage

The app stores configuration data locally on your device to provide launcher functionality:

- Home screen layout (app positions, pages, folders)
- Dock configuration
- Widget placements
- Custom icon and label overrides
- App preferences and settings

This data is stored in a local database on your device and is never transmitted to any server.

## Data collection

**We do not collect any data.** Specifically:

- No analytics or telemetry
- No crash reporting to external services
- No advertising identifiers
- No usage statistics
- No personal information

## Network access

The app does not request internet permission and makes no network connections. It operates entirely offline.

## Permissions

The app requests only the permissions necessary for core launcher functionality:

| Permission | Purpose |
|---|---|
| Query installed apps | Display apps in the app drawer |
| Vibrate | Haptic feedback during drag-and-drop |
| Bind app widgets | Host widgets on the home screen |
| Notification listener | Show notification badge counts on app icons |
| Set wallpaper | Wallpaper management |
| Expand status bar | Quick settings gesture |
| Device Administrator (lock screen) | Power the optional double-tap-to-lock gesture |

No data-collection permissions (contacts, location, camera, microphone, storage) are requested.

### Notification listener details

If you grant notification listener access, the app reads only the **package name** and **count** of active notifications in order to display badge numbers on app icons. It does not read notification titles, text, content, or any payload. Badge counts are held in memory only and are never written to disk or transmitted off the device. You can revoke access at any time via Android system settings.

### Device Administrator details

Hearth can optionally register as a Device Administrator to support the **double-tap-to-lock-screen** gesture. When activated, the app uses this permission for one purpose only: calling Android's `DevicePolicyManager.lockNow()` to lock the screen. No other Device Administrator capabilities are used — Hearth cannot and does not erase data, change your password, control the camera or keyguard, or apply any other device policy.

Device Administrator activation is **opt-in**: you must explicitly enable it in Settings, and the app never prompts for it on its own. You can revoke it at any time from Hearth's settings or from Android's system settings. When Device Administrator is not activated, the lock-screen gesture is simply unavailable; all other launcher features work normally.

## Backup and restore

The app offers a local backup/restore feature. Backup files are created and stored by you on your device via the system file picker. No backup data is transmitted to any server.

## Purchases

If you choose to purchase the premium upgrade, the purchase is processed entirely by **Google Play Billing**. We do not receive or store your payment card details; Google Play handles the transaction and sends us only the purchase token needed to validate your entitlement. Google's handling of purchase data is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

## Third-party services

Apart from Google Play Billing described above, the app does not integrate any third-party services, SDKs, or libraries that collect data.

## Children's privacy

The app does not collect any data from anyone, including children under 13.

## Changes to this policy

If this policy changes, the updated version will be posted at this URL with a new effective date.

## Contact

If you have questions about this privacy policy, contact us at: privacy@seventhchronicle.co.uk
