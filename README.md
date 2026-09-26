# Einsatzprotokoll Personensuche – Rettungshundestaffel

Eigenständige Offline-Anwendung zur Dokumentation von Personensuchen (Einsatz und Übung).

## Nutzung

- **Im Browser öffnen:** `https://<benutzername>.github.io/<repository>/`
- Die Anwendung besteht aus einer einzigen Datei (`index.html`) und benötigt keine weiteren Dateien.
- Der automatische Wetterabruf benötigt Internet. Alle übrigen Funktionen arbeiten offline, sobald die Seite geladen ist.

## Datenschutz

- Einsatzdaten werden **ausschließlich lokal auf dem jeweiligen Gerät** gespeichert.
- Dieses Repository enthält keine Einsatz- oder Personendaten.

## CalTopo

CalTopo wird nicht in die Anwendung eingebettet, sondern über den Knopf „🗺️ CalTopo“ in einem eigenen Browser-Tab geöffnet (am PC am besten als zweites Fenster neben dem Protokoll). Im Reiter „Anlagen“ kann je Einsatz der Link zur CalTopo-Karte hinterlegt werden; zugelassen sind nur https-Adressen von caltopo.com bzw. sartopo.com.

## Datenaustausch (immer bewusst ausgelöst)

| Richtung | Inhalt |
|---|---|
| Einsatzprotokoll ↔ BARRY | Team-Stammdaten („RHS Exchange v2“) |
| RH-Flächensuchassistent → Einsatzprotokoll | Einsatzübergabe |
| RH-Mantrailing-Assistent → Einsatzprotokoll | Einsatzübergabe |
| RH-Trümmersuchassistent → Einsatzprotokoll | Einsatzübergabe |
| Gaia GPS → Einsatzprotokoll | Tracks als GPX/KML (Reiter „Anlagen“) |
| CalTopo → Einsatzprotokoll | Tracks als GeoJSON-Export aus „Map Items → Export“ (Reiter „Anlagen“) |
| Einsatzprotokoll → Gaia GPS / CalTopo | Einsatzpunkte und Tracks als GPX |

Bereits übernommene Dateien werden wiedererkannt. Vor einer erneuten Übernahme fragt die App nach.

## Update auf eine neue Version

`index.html` ersetzen. Weitere Schritte sind nicht nötig.
