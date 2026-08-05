# Rion Studio Privacy Notice

Version and effective date: 2026-08-02

## 1. Scope and provider

This Notice describes data handled by the Rion Studio desktop app provided by the Rion Studio project. No individual support or contact channel is offered. Rion Studio has no project-operated cloud account, advertising, or analytics telemetry service.

## 2. Data stored on your device

The app stores role names, launch URLs, notes, cover images, window sizes, workspaces, macros, app preferences, browser settings, and status timestamps under the operating system's application data directory. Each role has an isolated browser profile that may contain cookies, cache, browsing history, local and session storage, IndexedDB data, and authentication tokens.

Rion Studio does not intentionally ask for or maintain a separate password database. Passwords entered into a third-party page are handled by that page and its browser context. A saved browser session may nevertheless permit account access and must be protected as sensitive data.

## 3. Why the app handles this data

Local data is used to restore roles, browser sessions, browser windows, workspaces, settings, and macros that you request. Rion Studio does not inspect or record whether a role is authenticated, and the project does not receive this local data merely because you use the app.

## 4. Network communications and third parties

- Target websites and identity providers receive normal browser requests and handle data under their own policies.
- Packaged builds check GitHub Releases for updates. GitHub can receive an IP address, app version, platform details, and ordinary request metadata.
- When you open browser font customization, visible Google Font samples load preview CSS and subset font files from Google Fonts. Google can receive an IP address, user agent, and ordinary request metadata. Applying a font still uses Rion Studio's verified local cache; game pages do not load these previews.
- System WebViews use the operating system's network settings. Rion Studio does not add or persist an app-specific network route.

## 5. Portable export and import

Portable JSON exports can include role names, launch URLs, notes, embedded cover images, window layouts, macros, and preferences. They exclude browser profile data, cookies, and saved login sessions. Export files are not encrypted; anyone who can read the file can read its contents. Import reads the file you select and creates new local records.

## 6. Retention, deletion, and control

Data remains on the device until you delete it, delete a role, clear application data, or uninstall the app and remove its user-data directory. Deleting a role removes its metadata and role browser directory. Portable exports remain wherever you save or copy them and must be deleted separately. Legal acceptance records remain device-local and are not included in portable exports.

Because the project does not receive the app's local records, access, correction, export, and deletion are performed through the app and operating-system file controls. Mandatory privacy rights available under applicable law are not limited by this Notice.

## 7. Security and limitations

Rion Studio uses isolated role directories, a capability-scoped Tauri IPC bridge, and the operating system's WKWebView or WebView2 runtime, but no desktop software can guarantee absolute security. Protect the operating-system account, disk, backups, exports, network settings, and physical device. Do not share a role directory with someone who should not be able to use its session.

## 8. Children and changes

Rion Studio is not designed to collect children's data for the project. A minor should use it only with guardian permission when required. Material changes to the data practices or this Notice require a version update and renewed in-app acknowledgment.
