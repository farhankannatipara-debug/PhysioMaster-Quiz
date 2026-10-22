# PhysioMaster Quiz — Android Studio project

This is an Android Studio project wrapper around the PhysioMaster Quiz front-end prototype.

## Included
- Native Android launcher Activity hosting the local app in WebView.
- BPT year categories, Complete BPT, MPT, DHA and International Licensing sections.
- Sample quizzes with explanations.
- Local progress, coins/referral-code demo, notes catalog and local admin question editor.
- App id: `com.physiomaster.quiz`; version 1.0.0; min Android API 23.

## Build an APK (Android Studio)
1. Download and extract `PhysioMaster_Android_Project.zip` on a computer.
2. Install the current stable Android Studio and a compatible JDK (Android Studio's bundled JDK is recommended).
3. In Android Studio choose **Open** and select the extracted `PhysioMaster_Android_Project` folder.
4. Allow Gradle sync and install the Android SDK platform requested by the project (API 35).
5. To test: choose a device/emulator and press **Run**.
6. To make a test APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
7. The debug APK is usually generated at `app/build/outputs/apk/debug/app-debug.apk`.

## Prepare for Google Play
1. Replace all sample/incomplete notes with your complete original or licensed content; review medical accuracy and copyright.
2. Implement a real backend for account authentication, synced progress, secure admin roles, question/notes management, referral verification, anti-abuse checks, and leaderboards.
3. Implement payment using the current Google Play Billing requirements for digital content sold inside the Play-distributed app. This prototype does not take payments.
4. Add a privacy policy, accurate Data safety declarations, support contact, content rating, store listing text/screenshots, app icon and feature graphic.
5. Test on real devices, accessibility, offline/poor network conditions, crash handling, backup, and security.
6. Create a signed release Android App Bundle (AAB) in Android Studio via **Build → Generate Signed Bundle / APK → Android App Bundle**. Keep the signing key private and backed up.
7. Create a Google Play Console developer account, complete verification, create the app listing, upload the AAB, complete required policy forms and testing track requirements, then submit for review. Google Play requirements can change; check the current Play Console guidance.

## Important limitations
- This is an early prototype, not a production-ready app and not a signed APK/AAB.
- No real payment, secure admin access, server database, live multiplayer challenges, cross-device sync, or verified referral rewards exist yet.
- Progress and added questions are stored locally in the browser/WebView on that device and may be lost if app data is cleared.
- The local admin preview is not protected. Do not use it for public users as an actual admin system.
- Coin values are demo-only and are not redeemable for cash.
- Review clinical content against the applicable curriculum and current authoritative guidance before publication.
