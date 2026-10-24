# Privacy Policy — AllUnderPar

**Last updated:** October 24, 2026

This privacy policy explains which data the app **AllUnderPar – Golf Scorecard** ("the app") processes, where it is stored, and what rights you have.

## Controller

Lasse Pilz
E-mail: pilzkoma@gmail.com

## 1. What data does the app process?

The app processes the data you enter yourself and – only with a paired Apple Watch and your consent – workout data in Apple Health (see 2.5):

- **Player profiles:** name, optional profile photo or emoji avatar, handicap, gender
- **Round data:** courses played, strokes per hole, putts, fairways, greens in regulation, hole notes
- **App settings:** language, distance unit, appearance, Pro Mode, haptics
- **Photos:** profile photos you take or pick; exported scorecards are saved only to your own photo library

The app uses **no tracking**, **no advertising or analytics IDs** and **no third-party SDKs**. It does **not** process location data.

## 2. Where is your data stored?

### 2.1 On your device
All data lives in the app's local database on your iPhone. It only leaves your device through the features below.

### 2.2 Paired Apple Watch
If you use the Watch app, your iPhone sends the live round (player names, emoji avatars, strokes, points and, in Pro Mode, putts, fairway and GIR) to your watch, and the watch sends strokes entered there back. This runs exclusively over Apple's WatchConnectivity between your own devices, without any server.

### 2.3 Your private iCloud (CloudKit)
If you are signed in to iCloud, every finished round (including player names, handicaps and scores) is backed up to your **personal, private iCloud database** and restored on your other devices. Only you can access it; Apple provides the infrastructure, the developer has no access.

### 2.4 Nearby multiplayer (MultipeerConnectivity)
During a multiplayer round you actively start, the app exchanges directly with nearby iPhones via Bluetooth or local Wi-Fi:

- your player name (visible as the device display name)
- stroke and hole updates during the round
- in tournament mode, the complete scorecards at the end of the round for comparison

This only happens while you are actively connected, peer-to-peer without any server.

### 2.5 Apple Health
If an Apple Watch is paired and you agree, the app starts a "Golf" workout on your watch when a round begins. This keeps the Watch app active during the round. At the end of the round the workout is saved to Apple Health; if you abandon the round, it is discarded. For this, the watch measures heart rate, active energy and walking distance during the round.

This health data is processed only on your devices and in Apple Health. It is not stored in the app's iCloud data, never sent to the developer or third parties, and never used for advertising. The legal basis is your explicit consent (Art. 9(2)(a) GDPR), which you can withdraw at any time in the Health app under *Profile → Apps → AllUnderPar*. Without consent the app keeps working; the Watch app just won't open automatically.

## 3. Permissions

| Permission | Purpose |
|---|---|
| Camera | Take a profile photo (optional) |
| Photo library (add only) | Save the scorecard as an image to your library |
| Local network | Multiplayer connection on the same Wi-Fi |
| Bluetooth | Multiplayer connection without Wi-Fi |
| Apple Health (save workouts, read heart rate/energy/distance) | Record the round as a golf workout on the watch |

Picking a profile photo needs no permission: through the iOS system picker the app only receives the one image you choose. The app never requests location access. You can revoke any permission in iOS Settings.

## 4. Network requests and recipients

**Course data (GitHub):** When you import or update golf courses, the app downloads a public JSON file from `raw.githubusercontent.com` (GitHub Inc., USA). For technical reasons your **IP address** and a generic device/app identifier (user agent) are transmitted to GitHub. No other data is sent. Legal basis: Art. 6(1)(f) GDPR (legitimate interest in providing course data). The transfer to the USA is based on the EU-U.S. Data Privacy Framework, under which GitHub is certified.

**Course requests by e-mail:** If you request a course or a data correction, the app opens your mail app with a pre-filled message. Only when you send it yourself do we receive your e-mail address and message. They are used solely to handle your request and deleted afterwards. Mail is received via Google (Gmail). Legal basis: Art. 6(1)(b) or (f) GDPR.

**Apple:** The app is distributed through the App Store. If you have agreed in iOS to share analytics and crash data with developers, Apple provides us with anonymized crash reports and usage statistics. The app itself has no influence on this; Apple's privacy policy applies.

Beyond this, the app makes no network connections and shares no personal data with third parties.

## 5. Legal bases

- Storing your entries on your device, in your iCloud and on your watch: Art. 6(1)(b) GDPR (providing the app features you use)
- Multiplayer exchange: Art. 6(1)(b) GDPR, triggered by your active connection
- Course data download: Art. 6(1)(f) GDPR
- Health data (Apple Health): explicit consent, Art. 9(2)(a) GDPR

## 6. Retention and deletion

- **Local data** is kept until you delete it: single rounds in the history, *Settings → Reset all statistics* or *Reset everything (incl. players & courses)*. Deleting the app removes all local data.
- **iCloud data** is also removed when you delete a round, *Reset all statistics* or *Reset everything (incl. players & courses)*. You can additionally manage it in iOS Settings under *[Your Name] → iCloud → Apps Using iCloud*.
- **E-mail requests** are deleted once handled.

## 7. Your rights

You have the right of access (Art. 15), rectification (Art. 16), erasure (Art. 17), restriction (Art. 18), data portability (Art. 20) and to object to processing based on legitimate interests (Art. 21 GDPR). Since your round and player data lives only on your devices and in your own iCloud, you can exercise most of these rights directly in the app. For anything else, an e-mail is enough.

You also have the right to lodge a complaint with a **data protection supervisory authority** (Art. 77 GDPR), for example the one where you live.

## 8. Handicap notice

The handicap AllUnderPar calculates is an in-app handicap. It is not an official DGV handicap and does not replace the record your home club keeps for you. For counting rounds, only the handicap index maintained by your club applies.

## 9. Changes

If the app's features or data flows change, this policy will be updated. The current version is linked in the app under *Settings → Privacy Policy*.

## 10. Contact

pilzkoma@gmail.com
