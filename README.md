# GeoQuest

GeoQuest ist eine Lern-App für Flaggen, Hauptstädte und die Weltkarte. Sie funktioniert vollständig
offline, braucht keine Berechtigungen, kein Konto und sammelt keine Daten.

Dieses Repository enthält nur die fertigen App-Dateien (APK) und die Versionshinweise.

## Installation mit Obtainium (empfohlen)

Mit [Obtainium](https://github.com/ImranR98/Obtainium) bekommst du neue Versionen automatisch
angeboten.

1. Obtainium installieren: die neueste APK von
   [github.com/ImranR98/Obtainium/releases](https://github.com/ImranR98/Obtainium/releases)
   herunterladen und öffnen. Android fragt dabei, ob die Installation aus dieser Quelle erlaubt
   werden soll – zulassen.
2. In Obtainium auf **App hinzufügen** tippen und als Quell-URL eintragen:

   ```
   https://github.com/Space010/GeoQuest-Releases
   ```

   Weitere Angaben sind nicht nötig. Mit **Hinzufügen** bestätigen.
3. **Installieren** antippen. Beim ersten Mal fragt Android erneut nach der Erlaubnis für Obtainium.

Danach prüft Obtainium regelmäßig auf neue Versionen und meldet sie. Ein Update behält deinen
Lernfortschritt.

## Installation ohne Obtainium

Unter [Releases](https://github.com/Space010/GeoQuest-Releases/releases) die APK der neuesten Version
herunterladen und öffnen. Updates musst du dann selbst auf demselben Weg installieren.

## Voraussetzungen

Android 9 oder neuer.

## Lernfortschritt sichern

Der Fortschritt liegt nur auf deinem Handy. Beim Deinstallieren geht er verloren. Unter
**Einstellungen → Daten → Exportieren** speicherst du eine Sicherung als Datei, die du später
wieder importieren kannst – zum Beispiel vor einem Handywechsel.

## Echtheit prüfen (optional)

Alle Versionen sind mit demselben Schlüssel signiert; Android installiert Updates nur, wenn die
Signatur passt. Fingerabdruck des Zertifikats (SHA-256):

```
F5:B6:D1:8F:64:F4:30:D1:0A:E5:E0:A0:BE:84:92:AD:C5:77:83:D8:CC:7D:96:A1:44:F5:7B:C4:34:37:56:45
```

Versionen bis 0.2.0 trugen einen früheren Schlüssel; der Wechsel ist in jeder neuen Version
hinterlegt, deshalb lassen sie sich ohne Datenverlust aktualisieren. Zu jeder APK gibt es außerdem
eine `.sha256`-Datei mit der Prüfsumme.
