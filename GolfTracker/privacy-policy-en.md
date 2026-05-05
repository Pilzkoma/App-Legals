# Privacy Policy — GolfTracker

**Last updated:** May 6, 2026

This privacy policy describes what data the **GolfTracker** app processes, how it is stored, and what rights you have as a user.

## Controller

Lasse Pilz
Email: pilzkoma@gmail.com

## 1. What data is processed?

GolfTracker only stores data that you yourself enter into the app:

- **Player profiles:** name, optional profile photo or emoji avatar, handicap, gender
- **Round data:** courses played, strokes per hole, putts, fairways hit, greens in regulation, penalty strokes, per-hole notes
- **App settings:** language, distance unit, Pro Mode, haptics
- **Optional photo content:** profile photos you take or pick yourself, exported scorecards (saved locally to your Photos library only)

GolfTracker does **not** collect tracking data, advertising or analytics IDs, and uses **no** third-party SDKs for data analysis.

## 2. Where is your data stored?

### 2.1 Locally on your device
All data is first stored on your iPhone or iPad in the local app database (SwiftData). It does not leave your device unless you actively use one of the features below.

### 2.2 In your private iCloud (CloudKit)
If you are signed in to iCloud and use CloudKit sync, your player and round data is synchronized to your **personal, private iCloud database**. This data is accessible only to you. Apple provides the infrastructure; neither the app provider nor any other user can access it.

### 2.3 Local multiplayer (MultipeerConnectivity)
When you actively start a multiplayer round, GolfTracker transmits the following data to the other iPhone in your immediate vicinity over **Bluetooth or local Wi-Fi**:
- Your chosen player name (visible as the device display name)
- Stroke and hole updates during the active round

Transmission only occurs while a multiplayer session is active and you have actively connected to a nearby device. There is no connection to any server; data is exchanged peer-to-peer and not stored on any central system.

## 3. Permissions

GolfTracker only requests the permissions necessary for the corresponding feature:

| Permission | Purpose |
|---|---|
| Photo Library (write) | Save the exported scorecard to your Photos |
| Camera | Take a profile photo for a player (optional) |
| Local Network | Discover multiplayer peers on the same Wi-Fi |
| Bluetooth | Establish multiplayer connection without Wi-Fi |

You can revoke any permission at any time in iOS Settings.

## 4. Data sharing

GolfTracker does **not** share any personal data with third parties. The only data flows leaving your device are:
- Synchronization to your own iCloud database (see 2.2)
- Peer-to-peer transmission to another device you actively pair with (see 2.3)

## 5. API calls

When importing golf courses, the app fetches a public, static JSON file from GitHub (`raw.githubusercontent.com`). No personally identifiable data is transmitted to GitHub during this fetch — it is a simple unauthenticated HTTPS GET request.

## 6. Retention and deletion

- **Local data** stays as long as you want it. Use *Settings → Reset all statistics* or *Reset everything* to selectively delete data.
- **iCloud data** can be removed from your private iCloud database at any time via *Settings → Reset everything*. Alternatively, in iOS Settings under *Apple ID → iCloud → Apps Using iCloud → GolfTracker* you can disable or delete the app's data entirely.
- Uninstalling the app removes all locally stored data. iCloud data must be deleted separately if desired.

## 7. Your rights

You are entitled at any time to:
- **Access** the data stored about you — fully visible inside the app
- **Correction** of incorrect data — via the app's editing functions
- **Deletion** of your data — via the reset functions or by uninstalling the app
- **Data portability** — on request, we will export your round data as JSON

Because GolfTracker does not transmit any personal data to a central server, most of these rights only concern your local app and iCloud storage, which you control yourself.

## 8. Changes to this policy

If app features or data flows change, this policy will be updated accordingly. The current version is always available at the URL referenced in the app and in the *Privacy Policy* setting.

## 9. Contact

For privacy-related questions, contact:

**Email:** pilzkoma@gmail.com
