# Privacy Policy — GolfTracker

**Last updated:** 31 August 2026

This privacy policy describes what data the **GolfTracker** app processes, how it is stored, and what rights you have as a user.

## Data controller

Lasse Pilz
Email: pilzkoma@gmail.com

## 1. What data is processed?

GolfTracker stores only the data you enter yourself:

- **Player profiles:** name, optional profile photo or emoji avatar, handicap, gender
- **Round data:** courses played, strokes per hole, putts, fairways, greens in regulation, notes per hole
- **App settings:** language, units, appearance, Pro Mode, haptics
- **Optional photo content:** profile photos you take or choose, and exported scorecards (saved only locally to your photo library)

GolfTracker collects **no** tracking data, gathers **no** advertising or analytics identifiers, and uses **no** third-party SDKs for data analysis.

**GolfTracker does not process location data.** The app never requests access to your location and does not evaluate any positional data.

## 2. Where is your data stored?

### 2.1 Locally on your device
All data is stored first on your iPhone or iPad in the app's local database (SwiftData). It does not leave your device unless you actively use one of the features below.

### 2.2 On a paired Apple Watch
If you use the GolfTracker app on a paired Apple Watch, your iPhone sends the current state of an in-progress round to the watch — player names, emoji avatar, strokes, scores, and (in Pro Mode) putts, fairway and greens in regulation. In return, the watch sends strokes you enter there back to the iPhone.

This exchange runs solely over Apple's on-device WatchConnectivity interface, between your iPhone and your own watch. No server is involved, and the data does not leave your own devices.

### 2.3 In your private iCloud (CloudKit)
If you are signed in to iCloud and use CloudKit sync, your player data and rounds are synchronised into your **personal, private iCloud database**. This data is accessible only to you. Apple provides the infrastructure; neither the app provider nor other users have access to it.

### 2.4 Local multiplayer network (MultipeerConnectivity)
During an actively started multiplayer round, GolfTracker transmits the following to the other iPhone in your immediate vicinity, via **Bluetooth or the local Wi-Fi network**:

- Your chosen player name (visible as the device display name)
- Stroke and hole updates during the round in progress
- In tournament mode, additionally the full scorecard of both devices at the end of the round, so the cards can be compared

Transmission happens **only** while a multiplayer session is active and you have actively connected to a nearby device. No connection to any server takes place; the data is exchanged peer-to-peer and is not stored on any central system.

## 3. Permissions

GolfTracker requests only the permissions required for the feature in question:

| Permission | Used for |
|---|---|
| Camera | Taking a profile photo directly (optional) |
| Photo library (saving) | Saving an exported scorecard to your library |
| Local network | Finding a multiplayer connection on the same Wi-Fi network |
| Bluetooth | Establishing a multiplayer connection without Wi-Fi |

**Choosing** an existing photo as a profile picture requires no permission at all: the app uses the iOS system picker and receives only the single image you select — not access to your library.

**GolfTracker does not request location access.**

You can revoke any granted permission at any time in the iOS system settings.

## 4. Data sharing

GolfTracker shares **no** personal data with third parties. The only flows of data off your iPhone are:

- Transmission to your own paired Apple Watch (see 2.2)
- Synchronisation into your own iCloud database (see 2.3)
- Peer-to-peer transmission to another device you actively pair with (see 2.4)

## 5. Network requests

When importing golf courses, and when later updating courses you have already imported, the app downloads a public, static JSON file from GitHub (`raw.githubusercontent.com`). No personal or identifying data is transmitted to GitHub in the process — it is a simple HTTPS GET request without authentication.

Beyond this, GolfTracker makes no network connections.

## 6. Retention and deletion

- **Local data** is kept for as long as you want to keep it. You can delete data selectively via *Settings → Reset statistics* or *Reset everything*.
- **iCloud data** can be removed from your private iCloud database at any time via *Settings → Reset everything*. Alternatively, you can disable or delete the app's data entirely in the iOS system settings under *Apple ID → iCloud → Apps using iCloud → GolfTracker*.
- Uninstalling the app removes all locally stored data. iCloud data must be deleted separately if desired.

## 7. Your rights

You have the right at any time to:

- **Access** the data stored about you — you can see all of it in the app
- **Rectification** of inaccurate data — via the app's editing functions
- **Erasure** of your data — via the reset functions or by uninstalling the app
- **Data portability** — your round data is never transmitted to us at any point. It resides solely on your device and, if you use iCloud sync, in your own private iCloud database. There is therefore no dataset held by us that we could hand over — you are already in possession of your data

Since GolfTracker sends no personal data to any central server, most of these rights concern only your local app storage and your iCloud storage, both of which you control yourself.

## 8. Changes to this policy

If the app's features or data flows change, this policy will be updated accordingly. The current version is always available at the link stored in the app, as well as via the app setting *Privacy Policy*.

## 9. A note on the handicap

The handicap GolfTracker calculates is an in-app handicap. It is not an official DGV handicap and does not replace the record your home club keeps for you. For counting rounds, only the handicap index maintained by your club applies.

## 10. Contact

For questions about data protection, you can reach us at:

**Email:** pilzkoma@gmail.com
