---
title: Support
---

# iDual Scanner Support

iDual Scanner ist eine iPhone und iPad App zum Scannen von Barcodes und zum Übertragen der Scan Ergebnisse an einen Zielrechner im lokalen Netzwerk.

## Appstore
Die App für iOS kann hier geladen werden:
[iDual Scanner](https://appstore.de)

## Schnellstart

1. App öffnen und Kamera Zugriff erlauben
2. Optional: In den Einstellungen Empfänger konfigurieren
3. Barcode scannen
4. Senden antippen, oder Auto Senden aktivieren, falls verfügbar

## Receiver Apps

Receiver Apps, Beispiele und Updates:  
[iDual Scanner Receiver Apps auf GitHub](https://github.com/idual/iDual-Scanner)

## Häufige Fragen

### Warum wird ein Hinweis zum lokalen Netzwerk angezeigt

iDual Scanner nutzt das lokale Netzwerk, um Empfänger zu finden (Bonjour und mDNS) und um Barcodes an einen Zielrechner zu übertragen.

### Warum findet die Empfänger Suche keinen Rechner

Bitte prüfen:

- iPhone oder iPad und Zielrechner sind im selben WLAN (kein Gastnetz)
- Bonjour ist auf dem Zielrechner aktiv
- Firewall erlaubt lokale Netzwerkverbindungen
- Der Receiver läuft und lauscht auf dem konfigurierten Port

### Warum klappt das Senden nicht

Bitte prüfen:

- Zielrechner (IP oder Hostname) korrekt
- Port korrekt
- Pfad korrekt (z. B. /scan)
- Receiver ist erreichbar (gleiches WLAN, Firewall)

### Welche Daten werden übertragen

Es werden die gescannten Codes, ein Zeitstempel und eine Geräte ID übertragen. Details stehen in der Datenschutzerklärung.

## Fehler melden

Am einfachsten über GitHub Issues:  
<https://github.com/idual/iDual-Scanner/issues>

Bitte angeben:

- iPhone oder iPad Modell
- iOS Version
- WLAN Umgebung (z. B. Heimnetz, Hotspot)
- Receiver Plattform (macOS, Windows)
- kurzer Ablauf, wie der Fehler entsteht
- optional Screenshot oder Log Auszug

## Kontakt und Impressum

Kontakt und Impressum: <http://idual.de/impressum.html>
