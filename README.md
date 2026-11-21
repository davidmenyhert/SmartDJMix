# SmartDJ Mix — GitHub Pages Privacy Policy

Official privacy-policy website for **SmartDJ Mix**, a two-deck DJ mixing app for Android phones and tablets.

**Privacy Policy URL (after GitHub Pages is enabled):**  
https://davidmenyhert.github.io/SmartDJMix/

## Publish on GitHub

This repository already exists at https://github.com/davidmenyhert/SmartDJMix/.

1. Upload `index.html` to the **root** of the `SmartDJMix` repository on the `main` branch.
2. Replace the existing `README.md` with this file (or edit it to include the same instructions).
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **`main`** and **`/(root)`**, then save.
6. Open https://davidmenyhert.github.io/SmartDJMix/ and verify that the policy appears.
7. In **Google Play Console → Policy and programs → App content → Privacy policy** (menu labels may vary), use that public URL.

The page is a static HTML file: it does not require a server, a backend, or a privacy-policy generator.

## What the policy covers

- Locally imported MP3 files, playlists, and saved app preferences.
- USB audio interfaces, Bluetooth output selection, and headphone monitoring.
- Optional Android audio-input permission and user-initiated local recording, where available.
- DJ SILENT/system sound and notification-interruption settings.
- Internet use, third-party file providers, and data retention.
- Contact details and future updates.

## Important checks before publishing

The policy is drafted for the SmartDJ Mix features described as of **November 21, 2026**, based on the source archive reviewed. Verify that its statements match the **actual Google Play release (AAB)**, particularly permissions, analytics, advertising, accounts, recording, and network services. The reviewed source did **not** show a Google AdMob or analytics SDK; do not reuse TrumPet's AdMob disclosures unless the released SmartDJ Mix app actually includes such services.

If streaming-provider authentication, advertising, analytics, cloud uploads, or other data processing is added later, update `index.html` and its effective date **before** releasing those features. Ensure the Play Console **Data safety** answers match the real production build.

Do **not** upload the Flutter/Android signing keystore (`.jks`), `key.properties`, API secrets, or private symbol/mapping files to this public policy repository.

> Note: Google Play also requires a privacy-policy link or equivalent access **inside the app** when applicable. This GitHub Pages site provides the public website; it does not automatically add a Privacy Policy menu item inside SmartDJ Mix.
