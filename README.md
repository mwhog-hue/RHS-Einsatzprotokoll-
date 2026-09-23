# Einsatzprotokoll Personensuche – Rettungshundestaffel

Eigenständige Offline-Anwendung zur Dokumentation von Personensuchen (Einsatz und Übung).

## Nutzung

- **Im Browser öffnen:** `https://<benutzername>.github.io/<repository>/`
- Die Anwendung besteht aus einer einzigen Datei (`index.html`) und benötigt keine weiteren Dateien.
- Der automatische Wetterabruf benötigt Internet. Alle übrigen Funktionen arbeiten offline, sobald die Seite geladen ist.

## Datenschutz

- Einsatzdaten werden **ausschließlich lokal auf dem jeweiligen Gerät** gespeichert.
- Dieses Repository enthält keine Einsatz- oder Personendaten.

## Datenaustausch (immer bewusst ausgelöst)

| Richtung | Inhalt |
|---|---|
| Einsatzprotokoll ↔ BARRY | Team-Stammdaten („RHS Exchange v2“) |
| RH-Flächensuchassistent → Einsatzprotokoll | Einsatzübergabe |
| RH-Mantrailing-Assistent → Einsatzprotokoll | Einsatzübergabe |
| RH-Trümmersuchassistent → Einsatzprotokoll | Einsatzübergabe |

Bereits übernommene Dateien werden wiedererkannt. Vor einer erneuten Übernahme fragt die App nach.

## Update auf eine neue Version

`index.html` ersetzen. Weitere Schritte sind nicht nötig.
