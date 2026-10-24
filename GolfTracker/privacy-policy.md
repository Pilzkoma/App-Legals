# Datenschutzerklärung — AllUnderPar

**Stand:** 24. Oktober 2026

Diese Datenschutzerklärung beschreibt, welche Daten die App **AllUnderPar – Golf Scorecard** (im Folgenden „die App“) verarbeitet, wo sie gespeichert werden und welche Rechte du hast.

## Verantwortlich

Lasse Pilz
E-Mail: pilzkoma@gmail.com

## 1. Welche Daten verarbeitet die App?

Die App verarbeitet die Daten, die du selbst eingibst, und – nur mit gekoppelter Apple Watch und deiner Zustimmung – Trainingsdaten in Apple Health (siehe 2.5):

- **Spielerprofile:** Name, optionales Profilfoto oder Emoji-Avatar, Handicap, Geschlecht
- **Runden-Daten:** gespielte Plätze, Schläge pro Loch, Putts, Fairways, Greens in Regulation, Notizen pro Loch
- **App-Einstellungen:** Sprache, Maßeinheit, Darstellung, Pro-Modus, Haptik
- **Fotos:** selbst aufgenommene oder ausgewählte Profilfotos; exportierte Scorecards landen nur in deiner eigenen Foto-Mediathek

Die App nutzt **kein Tracking**, **keine Werbe- oder Analyse-IDs** und **keine Drittanbieter-SDKs**. Sie verarbeitet **keine Standortdaten**.

## 2. Wo werden deine Daten gespeichert?

### 2.1 Lokal auf deinem Gerät
Alle Daten liegen in der lokalen App-Datenbank auf deinem iPhone. Sie verlassen dein Gerät nur über die folgenden Funktionen.

### 2.2 Gekoppelte Apple Watch
Nutzt du die Watch-App, überträgt das iPhone während einer Runde den Spielstand (Spielernamen, Emoji-Avatar, Schläge, Punkte, im Pro-Modus Putts, Fairway, GIR) an deine Uhr; die Uhr sendet dort eingegebene Schläge zurück. Die Übertragung läuft ausschließlich über Apples WatchConnectivity zwischen deinen eigenen Geräten, ohne Server.

### 2.3 Deine private iCloud (CloudKit)
Bist du in iCloud angemeldet, wird jede abgeschlossene Runde (inkl. Spielernamen, Handicap und Scores) in deine **persönliche, private iCloud-Datenbank** gesichert und auf deinen anderen Geräten wiederhergestellt. Nur du hast Zugriff; Apple stellt die Infrastruktur bereit, der Anbieter hat keinen Zugriff.

### 2.4 Mehrspieler in der Nähe (MultipeerConnectivity)
Bei einer aktiv gestarteten Mehrspieler-Runde tauscht die App per Bluetooth oder lokalem WLAN direkt mit iPhones in deiner Nähe aus:

- deinen Spielernamen (sichtbar als Geräte-Anzeigename)
- Schlag- und Loch-Updates während der Runde
- im Turniermodus am Rundenende die vollständigen Scorecards zum Vergleich

Das geschieht nur, solange du aktiv verbunden bist, Peer-to-Peer ohne Server.

### 2.5 Apple Health
Ist eine Apple Watch gekoppelt und stimmst du zu, startet die App beim Rundenstart auf deiner Watch ein Training „Golf“. Das hält die Watch-App während der Runde aktiv. Am Rundenende wird das Training in Apple Health gespeichert; brichst du die Runde ab, wird es verworfen. Dafür misst die Watch während der Runde Herzfrequenz, aktive Energie und Gehstrecke.

Diese Gesundheitsdaten werden ausschließlich auf deinen Geräten bzw. in Apple Health verarbeitet. Sie werden nicht in den iCloud-Daten der App gespeichert, nie an den Anbieter oder Dritte übermittelt und nie für Werbung genutzt. Rechtsgrundlage ist deine ausdrückliche Einwilligung (Art. 9 Abs. 2 lit. a DSGVO), die du jederzeit in der Health-App unter *Profil → Apps → AllUnderPar* widerrufen kannst. Ohne Einwilligung funktioniert die App weiter; die Watch-App öffnet sich dann nur nicht automatisch.

## 3. Berechtigungen

| Berechtigung | Wofür |
|---|---|
| Kamera | Profilbild aufnehmen (optional) |
| Fotomediathek (nur Sichern) | Scorecard als Bild in deiner Mediathek speichern |
| Lokales Netzwerk | Mehrspieler-Verbindung im selben WLAN |
| Bluetooth | Mehrspieler-Verbindung ohne WLAN |
| Apple Health (Training sichern, Herzfrequenz/Energie/Strecke lesen) | Runde als Golf-Training auf der Watch aufzeichnen |

Zum Auswählen eines Profilfotos ist keine Berechtigung nötig: Die App erhält über die iOS-Systemauswahl nur das eine Bild, das du auswählst. Standortzugriff fragt die App nicht an. Alle Berechtigungen kannst du in den iOS-Einstellungen widerrufen.

## 4. Netzwerk-Aufrufe und Empfänger

**Platzdaten (GitHub):** Beim Import oder Aktualisieren von Golfplätzen lädt die App eine öffentliche JSON-Datei von `raw.githubusercontent.com` (GitHub Inc., USA). Dabei wird technisch bedingt deine **IP-Adresse** sowie eine allgemeine Geräte-/App-Kennung (User-Agent) an GitHub übermittelt. Weitere Daten werden nicht gesendet. Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an der Bereitstellung der Platzdaten). Die Übermittlung in die USA stützt sich auf das EU-US Data Privacy Framework, unter dem GitHub zertifiziert ist.

**Platz-Anfrage per E-Mail:** Fragst du über „Platz anfragen“ bzw. „Datenkorrektur“ einen Platz an, öffnet die App deine Mail-App mit einer vorausgefüllten Nachricht. Erst wenn du sie selbst absendest, erhalten wir deine E-Mail-Adresse und deinen Nachrichtentext. Sie werden nur zur Bearbeitung deiner Anfrage verwendet und danach gelöscht. Der Empfang erfolgt über Google (Gmail). Rechtsgrundlage: Art. 6 Abs. 1 lit. b bzw. f DSGVO.

**Apple:** Die App wird über den App Store vertrieben. Hast du in iOS der Weitergabe von Analyse- und Absturzdaten an Entwickler zugestimmt, stellt Apple uns anonymisierte Absturzberichte und Nutzungsstatistiken bereit. Darauf hat die App selbst keinen Einfluss; es gilt die Datenschutzerklärung von Apple.

Darüber hinaus stellt die App keine Netzwerkverbindungen her und gibt keine personenbezogenen Daten an Dritte weiter.

## 5. Rechtsgrundlagen

- Speicherung deiner Eingaben auf deinem Gerät, in deiner iCloud und auf deiner Watch: Art. 6 Abs. 1 lit. b DSGVO (Bereitstellung der von dir genutzten App-Funktionen)
- Mehrspieler-Austausch: Art. 6 Abs. 1 lit. b DSGVO, ausgelöst durch deine aktive Verbindung
- Platzdaten-Abruf: Art. 6 Abs. 1 lit. f DSGVO
- Gesundheitsdaten (Apple Health): ausdrückliche Einwilligung, Art. 9 Abs. 2 lit. a DSGVO

## 6. Speicherdauer und Löschung

- **Lokale Daten** bleiben gespeichert, bis du sie löschst: einzelne Runden in der Historie, *Einstellungen → Alle Statistiken zurücksetzen* oder *Alles zurücksetzen (inkl. Spieler & Plätze)*. Beim Löschen der App werden alle lokalen Daten entfernt.
- **iCloud-Daten** werden beim Löschen einer Runde, bei *Alle Statistiken zurücksetzen* und bei *Alles zurücksetzen (inkl. Spieler & Plätze)* ebenfalls entfernt. Zusätzlich kannst du sie in den iOS-Einstellungen unter *[Dein Name] → iCloud → Apps mit iCloud* verwalten.
- **E-Mail-Anfragen** werden nach Abschluss der Bearbeitung gelöscht.

## 7. Deine Rechte

Du hast das Recht auf Auskunft (Art. 15), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung (Art. 18), Datenübertragbarkeit (Art. 20) und Widerspruch gegen Verarbeitungen auf Grundlage berechtigter Interessen (Art. 21 DSGVO). Da deine Runden- und Spielerdaten ausschließlich auf deinen Geräten und in deiner eigenen iCloud liegen, kannst du die meisten dieser Rechte direkt in der App ausüben. Für alles andere genügt eine E-Mail.

Du hast außerdem das Recht, dich bei einer **Datenschutz-Aufsichtsbehörde** zu beschweren (Art. 77 DSGVO), etwa bei der Behörde deines Wohnorts.

## 8. Hinweis zum Handicap

Das von AllUnderPar berechnete Handicap ist ein In-App-Handicap. Es ist kein offizielles DGV-Handicap und ersetzt nicht die Führung deines Stammblatts durch deinen Heimatclub. Für gewertete Runden gilt ausschließlich der von deinem Club geführte Handicap-Index.

## 9. Änderungen

Ändern sich Funktionen oder Datenflüsse der App, wird diese Erklärung angepasst. Die aktuelle Version ist in der App unter *Einstellungen → Datenschutzerklärung* verlinkt.

## 10. Kontakt

pilzkoma@gmail.com
