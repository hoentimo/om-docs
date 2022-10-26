---
description: >-
  Im folgenden wird die Einrichtung / Administration einer Druckvorlage
  beschrieben.
---

# Allgemein

## Voraussetzungen

* Der Kunde muss vollständig eingerichtet sein - siehe [kunden.md](../benutzer-and-kunden/kunden.md "mention")
* Der zugehörige **Lettershop** muss **vollständig** eingrichtet sein - inklusive [**Postdienstleister**](../administration/postdienstleister.md), **Kuvertiersteuerung** und **Servicezeiten**
* Jede Druckvorlage ist **genau einem Kunden** zugewiesen
* Das zu erkennende Dokument muss in einem **maschinenlesbaren PDF** Dokument im **DIN A4** Format vorliegen
* Jeder Vorgang muss über ein **eindeutiges** Merkmal identifizierbar sein. Nur so kann das System die entsprechende Vorlage erkennen
*
* Jeder Vorgang muss genau einen gültigen Adressblock im korrekten Bereich für Adressen besitzen. Siehe [#position-adressbereich](../themen/adressen.md#position-adressbereich "mention")

## Allgemeine Parameter



|                                           |                                  |                                                                                                    |
| ----------------------------------------- | -------------------------------- | -------------------------------------------------------------------------------------------------- |
| Name                                      | Name/Bezeichnung der Vorlage     | z.B. `Mahnlauf`                                                                                    |
| Postdienstleister                         |                                  | siehe [postdienstleister.md](../administration/postdienstleister.md "mention")                     |
| Kuvertiersteuerung                        |                                  | siehe [kuvertiersteuerung.md](../fortgeschrittene-themen/kuvertiersteuerung.md "mention")          |
| Papier                                    |                                  |                                                                                                    |
| Farbe                                     | Farbtyp der Vorlage              |                                                                                                    |
| Kuvert                                    | Kuvertyp                         |                                                                                                    |
| Geschäftspapier eindrucken                |                                  | siehe [geschaeftspapier.md](../themen/geschaeftspapier.md "mention")                               |
| abweichendes Geschäftspapier für 1. Seite |                                  | siehe [#abweichende-erste-seite](../themen/geschaeftspapier.md#abweichende-erste-seite "mention")  |
| Anhänge                                   | fester Anhang je Vorgang         | es können mehrere Anhänge gewählt werden. Siehe [anhaenge.md](../themen/anhaenge.md "mention")     |
| Gruppe für Druckaufträge                  |                                  |                                                                                                    |
| Kostenstelle                              | optionale Kostenstelle           | siehe [kostenstellen.md](../administration/kostenstellen.md "mention")                             |
| Sendungen konsolidieren                   |                                  |                                                                                                    |
| Adressen konsolidieren                    |                                  |                                                                                                    |
| Duplex                                    |                                  |                                                                                                    |
| optimiertes Duplex                        |                                  |                                                                                                    |
| Aufträge sammeln zu Paket                 |                                  |                                                                                                    |
| Priorität                                 |                                  | 0 = niedrig , 100 = hoch                                                                           |
| Beschreibung                              | ein optionaler Beschreibungstext |                                                                                                    |
|                                           |                                  |                                                                                                    |

## Zeiten

Siehe [prozesskette.md](../themen/prozesskette.md "mention") für eine Erklärung der verschiedenen Status-Zustände eines Druckvorgangs

|                  |   |                                                                          |
| ---------------- | - | ------------------------------------------------------------------------ |
| Freigabe         |   | Angabe in `HH:MM`                                                        |
| Freigabe Termine |   | Angabe in `cron` Syntax - [https://crontab.guru/](https://crontab.guru/) |
| Freigabe täglich |   |                                                                          |
| Gedruckt         |   | Angabe in `HH:MM`                                                        |
| Kuvertiert       |   | Angabe in `HH:MM`                                                        |
| Verschickt       |   | Angabe in `HH:MM`                                                        |

## Vorlage einrichten

Um die Vorlage zu definieren, folgenden Sie den weiteren Unterseiten in diesem Bereich, um die einzelnen Komponenten der Vorlage besser zu verstehen

{% content-ref url="komponenten/vorgangstrenner.md" %}
[vorgangstrenner.md](komponenten/vorgangstrenner.md)
{% endcontent-ref %}

{% content-ref url="komponenten/identifizierer.md" %}
[identifizierer.md](komponenten/identifizierer.md)
{% endcontent-ref %}

{% content-ref url="komponenten/adressbereich.md" %}
[adressbereich.md](komponenten/adressbereich.md)
{% endcontent-ref %}

{% content-ref url="komponenten/zusaetzliche-felder.md" %}
[zusaetzliche-felder.md](komponenten/zusaetzliche-felder.md)
{% endcontent-ref %}

## weitere Parameter

|                                       |   |                                  |
| ------------------------------------- | - | -------------------------------- |
| minimale Anzahl an Seiten pro Vorgang |   | Standard: `1`                    |
| maximale Anzahl an Seiten pro Vorgang |   |                                  |
| Seiten drehen                         |   | Mögliche Werte `0, 90, 180, 270` |
