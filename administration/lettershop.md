---
description: Wie man Lettershops einrichtet
---

# Lettershop

## Menüpunkt "Lettershop"

Im Menüpunkt Lettershop befinden sich alle Parameter für die Einrichtung eines Letterhhshops

| Feldbezeichnung                                       | Erklärung                                                                                           | mehr                                                                                                                                                              |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lettershop                                            | interne Bezeichnung                                                                                 |                                                                                                                                                                   |
| verwendete-URL                                        | Über welche URL ist das System erreichbar                                                           | benötigt weitere Konfiguration - siehe [eigene-domain.md](../fortgeschrittene-themen/eigene-domain.md "mention")                                                  |
| Portal-Bezeichnung                                    | Branding für das Portal                                                                             | erscheint in der Titelleiste sowie oben in der Navigation                                                                                                         |
| Produktname (für Treiber Setup)                       |                                                                                                     |                                                                                                                                                                   |
| Bezeichnung Abrechnung                                |                                                                                                     |                                                                                                                                                                   |
| URL Kontakt                                           |                                                                                                     |                                                                                                                                                                   |
| URL Datenschutz                                       |                                                                                                     |                                                                                                                                                                   |
| URL Impressum                                         |                                                                                                     |                                                                                                                                                                   |
| Infotext im Treiber zum Transaktionsdruck             |                                                                                                     |                                                                                                                                                                   |
| Zeige gelöschte Aufträge im Treiber                   |                                                                                                     |                                                                                                                                                                   |
| UI Theme                                              |                                                                                                     |                                                                                                                                                                   |
| E-Mail Adresse                                        |                                                                                                     |                                                                                                                                                                   |
| Straße, Hausnummer                                    |                                                                                                     |                                                                                                                                                                   |
| Postleitzahl                                          |                                                                                                     |                                                                                                                                                                   |
| Ort                                                   |                                                                                                     |                                                                                                                                                                   |
| Vorname                                               |                                                                                                     |                                                                                                                                                                   |
| Nachname                                              |                                                                                                     |                                                                                                                                                                   |
| Telefon                                               |                                                                                                     |                                                                                                                                                                   |
| Lettershop Administrator                              | Benutzenrame für Lettershop Administrator                                                           |                                                                                                                                                                   |
| Passwort                                              | Passwort festlegen                                                                                  |                                                                                                                                                                   |
| Passwort bestätigen                                   | Wiederholung des Passwortes                                                                         |                                                                                                                                                                   |
| Passwort bei nächster Anmeldung ändern                |                                                                                                     |                                                                                                                                                                   |
| Lettershop sperren                                    | wenn Aktiv: Alle Zugänge des Lettershops und deren Kunden  sperren                                  |                                                                                                                                                                   |
| Adress-Syntax überprüfen                              | Die Adresse einer Sendung wird syntaktisch auf Korrekten Aufbau überprüft                           | siehe [#adresse-syntax](../themen/adressen.md#adresse-syntax "mention")                                                                                           |
| Adress-Syntax Check Übersteuerbar                     | Ist eine gültige Adresse zwingend notwendig oder kann diese Meldung vom Benutzer übersteuert werden |                                                                                                                                                                   |
| Adressen überprüfen                                   | Adressprüfung mittels Dienst durchführen um Korrektheit zu prüfen.                                  | <p>Wenn die Adresse gefunden wurde wird das Land ergänzt. <br>siehe <a data-mention href="../themen/adressen.md#adressueberpruefung">#adressueberpruefung</a></p> |
| Adresscheck nicht verwenden\*                         | ?                                                                                                   |                                                                                                                                                                   |
| DE wenn kein Land erkannt                             | Fallback auf Deutschland, wenn kein Land im Adressbereich vorhanden                                 |                                                                                                                                                                   |
| Postscript statt PDF ausgeben                         | Übermittlung der Druckdaten in Postscript statt PDF                                                 |                                                                                                                                                                   |
| E-Mail bei Freigabe                                   | Sendet eine Status-Email bei täglicher Freigabe an Lettershop Administrator                         |                                                                                                                                                                   |
| Statistik anzeigen für Benutzer                       |                                                                                                     |                                                                                                                                                                   |
| Zeit für tägliche Status-Email                        |                                                                                                     | Format  `HH:MM`                                                                                                                                                   |
| Zeit für tägliche Abrechnungsübertragung              |                                                                                                     | Format  `HH:MM`                                                                                                                                                   |
| Vorlage für Lettershop                                |                                                                                                     |                                                                                                                                                                   |
| Kuverts verwenden                                     |                                                                                                     |                                                                                                                                                                   |
| Nutzungsbedingungen anzeigen                          |                                                                                                     |                                                                                                                                                                   |
| Benutzer Nutzungsbedingungen erneut bestätigen lassen | Setzt das Merkmal "Nutzungsbedingungen bestätigt" bei allen Benutzern zurück                        |                                                                                                                                                                   |
| Nutzungsbedingungen (HTML/PDF)                        | Das Dokument für die angezeigten Nutzungsbedingungen                                                |                                                                                                                                                                   |
| Minimale Passwortlänge                                |                                                                                                     |                                                                                                                                                                   |
| Ausgangsserver für Kunden erlauben                    |                                                                                                     |                                                                                                                                                                   |
| AdHoc Anhänge erlauben                                | Benutzer dürfen lokale PDFs als Anhang anfügen                                                      | siehe [anhaenge.md](../themen/anhaenge.md "mention")                                                                                                              |
| Freigaben OHNE zusätzliche Bestätigung                |                                                                                                     |                                                                                                                                                                   |
| Beim Freigeben direkt übertragen                      |                                                                                                     |                                                                                                                                                                   |
| Ausgabe in Einzeldateien                              | Steuert ob die Druckströme gebündelt oder                                                           |                                                                                                                                                                   |
| XML Dateien bei Ausgabe erzeugen                      |                                                                                                     |                                                                                                                                                                   |
| Aufbau Dateiname Ausgabe                              |                                                                                                     | siehe [#platzhalter-fuer-dateinamen](lettershop.md#platzhalter-fuer-dateinamen "mention")                                                                         |
| Ausgabeformat immer auf DIN A4 skalieren              |                                                                                                     |                                                                                                                                                                   |
| Postalische Zustellung                                | (De)-aktiviert Kanäle für postalische Zustellung                                                    |                                                                                                                                                                   |
| E-Mail Zustellung                                     |                                                                                                     | siehe [#e-mail](../themen/digitaler-versand.md#e-mail "mention")                                                                                                  |
| Foxdox Zustellung                                     |                                                                                                     | siehe [#foxdox-postbox](../themen/digitaler-versand.md#foxdox-postbox "mention")                                                                                  |
| Preise pro Vorlage/Tarif                              | Eine spezielle Einstellung für Lettershop RIECO                                                     |                                                                                                                                                                   |
| Preiseinstellungen anzeigen                           |                                                                                                     |                                                                                                                                                                   |
| Artikelnummern                                        | Eine spezielle Einstellung für Lettershop PD.M                                                      |                                                                                                                                                                   |
| Bei Druckauftrag mit Fehler, nach 24h Email an User   | sendet eine um 24 Stunden verzögerte Email an den Druckbenutzer nach fehlerhaftem Druckauftrag      |                                                                                                                                                                   |
| Sendungsarchiv aktivieren                             |                                                                                                     |                                                                                                                                                                   |
| Kostenstellen aktivieren                              |                                                                                                     |                                                                                                                                                                   |
| Timer für Freigaben                                   |                                                                                                     |                                                                                                                                                                   |
| Timer für Status "gedruckt"                           |                                                                                                     |                                                                                                                                                                   |
| Timer für Status "kuvertiert"                         |                                                                                                     |                                                                                                                                                                   |
| Button Adresse anzeigen in Vorlagen                   |                                                                                                     |                                                                                                                                                                   |
| Postdienstleister anzeigen in Vorlagen                |                                                                                                     |                                                                                                                                                                   |
| Aufbewahrungszeit anzeigen in Vorlagen                |                                                                                                     |                                                                                                                                                                   |

### Preise

| Bezeichnung                     | Erklärung                   | Mehr                               |
| ------------------------------- | --------------------------- | ---------------------------------- |
| Preis Farbdruck                 | Preis je Farbdruck in Euro  |                                    |
| Preis SW-Druck                  | Preis je SW Druck in Euro   |                                    |
| Preis "automatisch kuvertieren" |                             |                                    |
| Preis "manuell kuvertieren"     |                             |                                    |
| Preis Standard Papier           |                             |                                    |
| Preis foxdox                    |                             | nur wenn "Foxdox Zustellung" aktiv |
| Preis E-Mail                    |                             | nur wenn "E-Mail Zustellung" aktiv |

### Einschränkungen beim Druck

siehe [#einschraenkungen-beim-druck](../benutzer-and-kunden/rollen-and-rechte/druckbenutzer.md#einschraenkungen-beim-druck "mention")

### Werktage

Die Checkboxen unter Werktage definieren die Werktage für den Lettershop.

Die Standardeinstellung ist  `Montag - Freitag`&#x20;

## Platzhalter für Dateinamen

Dateinamen und Gruppierung können individuell angepasst werden.\
Die dazu verwendeten Platzhalter werden in geschweiften Klammern und im  Format `{PLATTZHALTER_NAME}` verwendet.&#x20;

Beispiel:  `{SENDINGID}.pdf` wird bei der Ausgabe der Sendung `4711` zu `4711.pdf`

{% hint style="info" %}
<mark style="color:blue;">Es ist möglich die Sendungen in Unterordner gruppieren zu lassen, indem man das Trennzeichen /  verwendet, z.B {COLOR}/{SENDINGID}.pdf  erzeugt später Unterordner basierend auf der Druckfarbe in denen die jeweiligen Dateien nach Sendungsnummer benannt sind.</mark>\

{% endhint %}

<mark style="color:blue;"></mark>

| Platzhalter   | Beschreibung                     | Werte                |
| ------------- | -------------------------------- | -------------------- |
| SENDINGID     | Sendungsnummer / ID des Systems  |                      |
| SERVICE       |                                  |                      |
| RATE          |                                  |                      |
| _PLEX_        | Art der Ausgabe                  | `simplex` , `duplex` |
| COLOR         | Farbtyp des Drucks               | `sw` , `color`       |
| _CUSTOMER_    | ID des Kunden                    |                      |
| ACCOUNT       | Benutzer-ID des Druck Benutzers  |                      |
| _COUNT_       | Anzahl der Seiten                |                      |
| TEMPLATE      | ID der Druckvorlage              |                      |
| JOBID         | ID des Druckjobs                 |                      |
| _DESTINATION_ |                                  |                      |
| ENVELOPETYPE  | ID des zu verwendenden Kuvertyps | `default`            |
