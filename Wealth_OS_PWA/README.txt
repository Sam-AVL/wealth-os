WEALTH OS — PRIVATE OFFLINE PWA

PROMISE
- No sign-up or account required.
- No subscription or paid service required to use the app itself. Hosting may be free on a suitable static HTTPS host; third-party hosts can change their terms.
- No cloud sync and no automatic transfer between devices.
- Planner data is stored in this browser/device using localStorage.
- Backup and restore are manual JSON file actions. A backup file contains financial information; keep it private.

FILES
- index.html: wealth planner and local data storage.
- manifest.json: install identity and appearance.
- sw.js: offline app-shell caching.
- icon-192.png / icon-512.png: app icons.

INSTALL / HOST
1. Upload the CONTENTS of this folder to a static HTTPS host. A free static host can work; hosting provider terms and availability may change.
2. Visit the HTTPS URL once while online and wait for it to finish loading.
3. On Android Chrome, use the browser menu and choose Install app / Add to Home screen. On desktop Chrome or Edge, use the install option if offered.
4. Reopen the app and test it with Wi-Fi and mobile data turned off.
5. In Track, use Download backup to export data. Restore backup replaces current local data after confirmation. To move data to another device, transfer the backup manually and restore it there. This is not sync.

PRIVACY AND SECURITY LIMITS
- No login, subscription, cloud account, or sync feature is included.
- Data stays in the browser storage on the device where it was entered. Clearing browser data, uninstalling, or device loss may remove it. Export backups regularly.
- Anyone with access to your unlocked device/browser profile or an exported backup may be able to access your financial information. This app does not provide encrypted backup files or a server-side account recovery option.
- The app requires HTTPS (or localhost) for service-worker offline support. Installability varies by browser and operating system.
- This package is designed for local-first use, but no app can be guaranteed 100% secure. Test all screens and backup/restore on your target devices before relying on it.
