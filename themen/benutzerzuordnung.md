# Benutzerzuordnung

Über das Feld "Zuordnungsattribut" - siehe [#zuordnungsattribut](../benutzer-and-kunden/benutzer.md#zuordnungsattribut "mention") , besteht die Möglichkeit der Zuordnung von internen Benutzernamen zu den Benutzern im Outputmanager über Meta-Daten von Druckdokumenten.\
\
Die Benutzernamen können über folgende Werte extrahiert  werden:

|               |                            |                            |
| ------------- | -------------------------- | -------------------------- |
| Word Dokument | Meta Feld "Autor"          | z.B. "Autor: m.mustermann" |
| SAP           | Benutzername im Dateinamen | siehe SAP Dateiname unten  |
|               |                            |                            |

### SAP Dateiname

Die Extraktion von Benutzernamen von SAP Dokumenten erfolgt über den Dateinamen wie folgt:

Dateiname: `MUSTMANN/HCP0000079384_1:Lohnsteuerbescheinigung für Mitarbeiter`

Der Wert "**`MUSTMANN`**"  entspricht hierbei dem SAP Benutzernamen.

Wenn ein Benutzer im Outputmanger das Zuordnungsattribut "MUSTMANN" in seinem Profil angegeben hat, so kann das Dokument zugewiesen werden, auch wenn der Benutzername abweicht.

