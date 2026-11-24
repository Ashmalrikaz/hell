SHELL MINECRAFT – unofficial fan-made fuel and vehicle app concept

Files:
- index.html: responsive, block-inspired fuel dashboard with trip-cost calculator, addable/removable stations, admin text editor, startup screen, and local encrypted passcode vault
- sw.js: offline cache
- manifest.webmanifest: installable PWA settings
- icon.svg: app icon

To test: open index.html in a browser. For installable offline PWA support on iPad/Android, host this folder on an HTTPS website, open it once online, then use Add to Home Screen. Service workers do not work from a file:// address.

This is an unofficial fan-made concept, not affiliated with or endorsed by Shell, Mojang, or Microsoft. Fuel prices, wallet, points, and the five in-app station names are sample information; station locations are not verified real branches, and no country, live map, or device location is used. The trip-cost calculator estimates fuel use from distance, vehicle consumption, and the existing sample prices; it is not a live quote. Settings & Security includes editable dashboard headings and descriptions; fixed branding and sample-data notices are intentionally not editable. Set a unique, hard-to-guess passphrase of at least 12 characters. Saved dashboard data is encrypted in this browser using Web Crypto (600,000-round PBKDF2-SHA256 and AES-GCM), with random salt and IV values. Encrypted backups can be moved by USB and imported on another device using the exporting passcode; data does not sync automatically. This does not enforce a two-device limit. The app temporarily locks after repeated failed attempts and relocks after inactivity. This is local browser encryption, not a real account or operating-system authentication; browser storage and lockout controls can be altered by someone with access to the device. The passcode is never stored directly, and forgotten encrypted data cannot be recovered. Keep backups and passcodes safe. Do not store highly sensitive information. Vehicle photos load from Unsplash and require an internet connection. App data is stored in this browser only.
