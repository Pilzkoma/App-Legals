# Datenschutzerklärung — GolfTracker

**Stand:** 6. Mai 2026

Diese Datenschutzerklärung beschreibt, welche Daten die App **GolfTracker** verarbeitet, wie sie gespeichert werden und welche Rechte du als Nutzer hast.

## Verantwortlich für die Datenverarbeitung

Lasse Pilz
E-Mail: pilzkoma@gmail.com

## 1. Welche Daten werden verarbeitet?

GolfTracker speichert ausschließlich die Daten, die du selbst in der App eingibst:

- **Spielerprofile:** Name, optionales Profilfoto oder Emoji-Avatar, Handicap, Geschlecht
- **Runden-Daten:** Gespielte Plätze, Schläge pro Loch, Putts, Fairways, Greens in Regulation, Strafschläge, Notizen pro Loch
- **App-Einstellungen:** Sprache, Maßeinheit, Pro-Mode, Haptik
- **Optionale Foto-Inhalte:** Selbst aufgenommene oder ausgewählte Profilfotos, exportierte Scorecards (nur lokal in deiner Foto-Mediathek)

GolfTracker erhebt **keine** Tracking-Daten, sammelt **keine** Werbe- oder Analyse-IDs und nutzt **keine** Drittanbieter-SDKs zur Datenanalyse.

## 2. Wo werden deine Daten gespeichert?

### 2.1 Lokal auf deinem Gerät
Alle Daten werden zunächst auf deinem iPhone bzw. iPad in der lokalen App-Datenbank (SwiftData) gespeichert. Sie verlassen dein Gerät nicht, sofern du eine der folgenden Funktionen nicht aktiv nutzt.

### 2.2 In deiner privaten iCloud (CloudKit)
Wenn du in iCloud angemeldet bist und CloudKit-Sync nutzt, werden deine Spielerdaten und Runden in deine **persönliche, private iCloud-Datenbank** synchronisiert. Diese Daten sind ausschließlich für dich zugänglich. Apple stellt die Infrastruktur bereit; weder der App-Anbieter noch andere Nutzer haben Zugriff darauf.

### 2.3 Lokales Mehrspieler-Netzwerk (MultipeerConnectivity)
Bei einer aktiv gestarteten Mehrspieler-Runde überträgt GolfTracker per **Bluetooth oder lokalem WLAN** an das andere iPhone in deiner unmittelbaren Umgebung folgende Daten:
- Dein gewählter Spielername (sichtbar als Geräte-Anzeigename)
- Schlag- und Loch-Updates während der laufenden Runde

Die Übertragung erfolgt **nur**, solange eine Mehrspieler-Sitzung aktiv ist und du dich aktiv mit einem Gerät in der Nähe verbunden hast. Es findet keine Verbindung zu Servern statt; die Daten werden Peer-to-Peer ausgetauscht und auf keinem zentralen System gespeichert.

## 3. Berechtigungen

GolfTracker fragt nur die Berechtigungen ab, die für die jeweilige Funktion notwendig sind:

| Berechtigung | Wofür |
|---|---|
| Fotomediathek (Lesen) | Profilbild für einen Spieler auswählen |
| Fotomediathek (Schreiben) | Exportierte Scorecard speichern |
| Kamera | Profilbild direkt aufnehmen (optional) |
| Lokales Netzwerk | Mehrspieler-Verbindung im selben WLAN finden |
| Bluetooth | Mehrspieler-Verbindung ohne WLAN aufbauen |

Du kannst jede Berechtigung jederzeit in den iOS-Systemeinstellungen widerrufen.

## 4. Datenweitergabe

GolfTracker gibt **keine** personenbezogenen Daten an Dritte weiter. Der einzige Datenfluss außerhalb deines Geräts ist:
- Die Synchronisation in deine eigene iCloud-Datenbank (siehe 2.2)
- Die Peer-zu-Peer-Übertragung an ein anderes Gerät, das du aktiv koppelst (siehe 2.3)

## 5. API-Aufrufe

Beim Import von Golfplätzen lädt die App eine öffentliche, statische JSON-Datei von GitHub (`raw.githubusercontent.com`). Dabei werden weder personenbezogene noch identifizierende Daten an GitHub übermittelt — es ist ein einfacher HTTPS-GET-Aufruf ohne Authentifizierung.

## 6. Speicherdauer und Löschung

- **Lokale Daten** bleiben so lange gespeichert, wie du sie behalten möchtest. Über *Einstellungen → Statistiken zurücksetzen* oder *Alles zurücksetzen* kannst du Daten gezielt löschen.
- **iCloud-Daten** kannst du jederzeit über *Einstellungen → Alles zurücksetzen* aus deiner privaten iCloud-Datenbank entfernen. Alternativ kannst du in den iOS-Systemeinstellungen unter *Apple ID → iCloud → Apps mit iCloud → GolfTracker* die App-Daten komplett deaktivieren oder löschen.
- Beim Deinstallieren der App werden alle lokal gespeicherten Daten entfernt. iCloud-Daten musst du separat löschen, falls gewünscht.

## 7. Deine Rechte

Du hast jederzeit das Recht auf:
- **Auskunft** über die zu deiner Person gespeicherten Daten — diese siehst du vollständig in der App
- **Berichtigung** unrichtiger Daten — über die Bearbeitungsfunktionen der App
- **Löschung** deiner Daten — über die Reset-Funktionen oder das Deinstallieren der App
- **Datenübertragbarkeit** — auf Anfrage exportieren wir deine Runden-Daten als JSON

Da GolfTracker keine personenbezogenen Daten an einen zentralen Server sendet, betreffen die meisten dieser Rechte ohnehin nur deine lokale App- und iCloud-Speicherung, die du selbst kontrollierst.

## 8. Änderungen dieser Erklärung

Falls sich Funktionen oder Datenflüsse der App ändern, wird diese Erklärung entsprechend aktualisiert. Die jeweils aktuelle Version findest du unter dem in der App hinterlegten Link sowie in der App-Einstellung *Datenschutzerklärung*.

## 9. Kontakt

Bei Fragen zum Datenschutz erreichst du uns unter:

**E-Mail:** pilzkoma@gmail.com
