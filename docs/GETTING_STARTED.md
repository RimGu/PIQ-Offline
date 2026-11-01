# Getting started with PIQ Offline

PIQ Offline is an unofficial Android app modification for the Duotone / North PIQ kitesurf sensor. It uses a local profile and stores your downloaded sessions on your phone.

## 1. Download and install

Open the [Android APK download](https://raw.githubusercontent.com/RimGu/PIQ-Offline/main/downloads/PIQ-Offline-592.apk) on your phone. The file is named `PIQ-Offline-592.apk`, about 52 MB; the installed app is named **PIQ Offline**.

Open it from your browser’s downloads or your phone’s **Files / My Files → Downloads**, then tap **Install** or **Update**. Android may ask you to allow installation from that browser/file manager. No computer, coding tools or GitHub account is needed for the public download.

**If you already use Offline 2 / PIQ Offline, update it without uninstalling or clearing data.** Keep the original PIQ app and the first test app installed. The new app has separate storage and does not automatically import their history.

If installation fails, check that you downloaded the APK rather than the source ZIP or a web page. If Android says signatures conflict, stop and report the message; do not uninstall a working app to get past it.

## 2. Connect your sensor

Charge and turn on the sensor. Close other PIQ apps while connecting, and prevent another phone from competing for the same sensor.

Open PIQ Offline and tap the sensor icon at the top right. Pair from inside the app and allow the Bluetooth/nearby-device or location permissions it requests. The original discovery code may also need Location switched on.

Download a recording, open it and check its date and measurements. Try a saved note and reopen the session. Original tracker cleanup is enabled again, so transferred recordings may be removed from the sensor. Keep backups of your downloaded collection.

If an ownership or firmware warning appears, keep the exact message and report it instead of resetting the sensor or trying an unsupported firmware update.

## 3. Choose a backup file

During setup, or in the **BACKUPS** section of **Settings**, choose a location for your backup ZIP. Installed providers such as Drive or OneDrive may appear. The selected ZIP will be replaced with the latest backup; the actual working database stays in private app storage.

You can also open **Offline backup settings → SAVE BACKUP ZIP**. Wait for the saved/read-back confirmation. That confirms the provider’s bytes can be read; check the provider app separately for completion of any cloud upload.

Automatic backups wait for recordings and idle processing. They run while the app process is alive and resume pending changes when you use the app again. Bluetooth can remain on for backups. Keep the app open until a manual save finishes.

Previous verified copies stay in local history for 30 days and at least three previous versions when available. Removing app storage removes that local history too. Store an independent copy off the phone. ZIPs contain private data and are not encrypted.

## Restoring instead of starting fresh

If you have a PIQ Offline backup, restore it **before adding new sessions**. In **Settings**, scroll to **BACKUPS** and open **Offline backup settings → RESTORE BACKUP ZIP**. Turn Bluetooth off and choose the ZIP. The collection must be empty; restoring does not merge or overwrite an existing collection.

After success, tap **Close app**, then open PIQ Offline again. Check your sessions, notes, units and profile picture. Never clear a working collection merely to try restore.

A backup from another app cannot be imported just by renaming it. Recordings stored only in the original app or old cloud account are not automatically recovered. Leave those installations intact.

## Need help?

[Report a problem or ask a question](https://github.com/RimGu/PIQ-Offline/issues/new/choose). GitHub may ask you to sign in to post; downloading the public APK does not need an account.

Include your phone model, Android version, PIQ Offline version and the last step that worked. Avoid posting backup ZIPs or personal recordings publicly.

[Back to PIQ Offline](../README.md)
