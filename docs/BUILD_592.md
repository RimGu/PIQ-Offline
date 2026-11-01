# Build 592 checks

- App: **PIQ Offline**, version **5.0.592-offline**.
- Android package: `com.piq.north.offline.next`.
- APK size: **51,579,545 bytes**.
- SHA-256: `4bf45e6884152b553f99aaa54503d6d6347d6575b6640797ab9de53886ed3fef`.

Build 592 changes the Settings button to **Give feedback on GitHub** and directs the Settings button and feedback dialog to this repository’s Issues page.

The build, signing-certificate continuity, app name, package and version checks passed. A focused emulator check confirmed the renamed Settings row and its outgoing browser link. The uploaded APK was downloaded and its checksum matched. No issue was posted during testing.

The database and backup helper classes are unchanged from the earlier tested build. Earlier Android regression checks covered database/motion-file round trips, saved notes, units, overwrite protection, rollback, document-picker backup save/read-back and restore, and closing/reopening the app. Those broad tests were not repeated for this label/link update.

Earlier builds were used successfully on a Galaxy S22 running Android 16. This remains a community test build: physical tracker behavior and all phone/storage-provider combinations are not fully verified.

[Back to PIQ Offline](../README.md)
