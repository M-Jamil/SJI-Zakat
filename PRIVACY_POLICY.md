# Privacy Policy — SJI Zakat Management

**App Name:** SJI Zakat Management — KPM Islamic Zakat Calculation & Charity Distribution  
**Package ID:** `com.sji.sjizakat`  
**Platforms:** Android · iOS · macOS · Windows  
**Effective Date:** 2025-07-01  
**Last Updated:** 2026-10-06

---

## 1. Overview

SJI Zakat Management is a fully offline Islamic Zakat calculator and charity distribution tracker. The app does **not** collect, transmit, or share any personal data with the developer or any third party. All data you enter remains exclusively on your own device.

---

## 2. Data We Collect

**We do not collect any data.**

The app does not include analytics, crash reporting, advertising SDKs, or any form of remote data collection. No data is ever sent to the developer, to third-party services, or to any server.

---

## 3. Data You Enter and Where It Is Stored

When you use the app, you may enter financial and personal information such as:

- Gold and silver holdings and valuations
- Bank account balances
- Loan amounts (given and taken)
- Prize bonds and stock share values
- Investment property details
- Charity organisation names and donation records
- Preferred currency and app settings

All of this information is stored **locally on your device only**, in a SQLite database (`sjizakat.db`). The storage location depends on your platform:

| Platform | Database location |
|----------|-------------------|
| Android  | `/data/data/com.sji.sjizakat/databases/sjizakat.db` (private app storage) |
| iOS      | `<app>/Documents/sjizakat.db` |
| macOS    | `~/Library/Application Support/com.sji.sjizakat/sjizakat.db` |
| Windows  | `%APPDATA%\com.sji.sjizakat\sjizakat.db` |

This data is **never uploaded, synced, or accessible to anyone other than you**.

---

## 4. Backup & Restore

The app provides an optional backup feature that packages your local database into a `.zip` archive. This backup file is created entirely on your device. You choose where to save or share it (e.g. Files app, iCloud Drive, Google Drive, email).

- The developer **never** receives your backup file.
- The backup file contains all data you have entered in the app.
- You are solely responsible for the security of any backup file you create and store outside the app.

---

## 5. Internet Access

**The app does not use the internet.**

SJI Zakat Management requires no network connection and does not make any network requests. There is no user account system, no cloud sync, and no remote API. All calculations and data processing happen entirely on your device.

---

## 6. Device Permissions

The app requests only the permissions strictly necessary for its core features:

| Permission | Purpose |
|-----------|---------|
| **File / document access** (iOS, macOS) | Read and write backup `.zip` files to the location you choose |
| **File picker access** (all platforms) | Let you select a backup file to restore |
| **Storage / Files** (Android, Windows) | Save and open backup files |

No microphone, camera, contacts, location, or any other sensitive permission is requested or used.

---

## 7. Third-Party Services

SJI Zakat Management does **not** integrate any third-party SDKs for advertising, analytics, crash reporting, social sign-in, or any other purpose. The app's dependencies are:

| Package | Purpose |
|---------|---------|
| `sqflite` / `sqflite_common_ffi` | Local SQLite database (on-device only) |
| `path_provider` | Determine on-device storage path |
| `file_picker` | Open a backup file from the device |
| `share_plus` | Invoke the OS share sheet for the backup file |
| `archive` | Create and read ZIP backup archives |
| `provider` | In-memory app state management |
| `intl` | Date and number formatting |
| `fl_chart` | Render charts within the app |
| `flutter_slidable` | Swipe gestures on list items |

None of these packages send data to external servers.

---

## 8. Children's Privacy

SJI Zakat Management is a financial utility application. It does not knowingly collect any data from users of any age, including children under 13 (COPPA) or under 16 (GDPR/PECR). Because no data is collected at all, no special parental consent process is required or applicable.

---

## 9. Your Rights

Because the app stores data solely on your device and the developer has no access to it, the typical data-subject rights (access, rectification, erasure, portability) are exercised directly by you:

- **Access / export** — use the Backup & Restore feature to export your full dataset as a `.zip` file at any time.
- **Deletion** — clear the app's data via your device's app settings, or uninstall the app, to permanently delete all stored data.
- **Portability** — your backup `.zip` contains the raw SQLite database, which can be opened with any standard SQLite client.

---

## 10. Data Security

Since no data leaves your device, the security of your data is determined by the security of your device (screen lock, encryption, access controls). We strongly recommend:

- Keeping your device OS and the app up to date.
- Storing backup files in a secure location (e.g. an encrypted cloud drive with a strong password).
- Not sharing backup files over unencrypted channels.

---

## 11. Changes to This Policy

If the app's data practices change in a future version (for example, if optional cloud backup is added), this policy will be updated and a new effective date will be set. The updated policy will be made available on the app's store listing and in this repository before the new version is published.

---

## 12. Contact


If you have any questions or concerns about this Privacy Policy or the privacy practices of SJI Tajweed Quran, please contact us:

**Developer / Legal entity:** SJI Tech 
**App:** SJI Zakat Management 
**Package ID:** `com.sji.sjizakat`  
**Google Play listing:** https://play.google.com/store/apps/details?id=com.sji.sjizakat  


---

*SJI Zakat Management — All your Zakat data stays on your device, always.*
