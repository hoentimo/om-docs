---
description: Im folgenden wird die Einrichtung eines neuen Kunden beschrieben.
---

# Kunden

## Voraussetzungen

* Es muss ein [Lettershop eingerichtet](../administration/lettershop.md) sein
* Sie müssen die Rolle [Lettershop-Administrator](broken-reference) oder höher besitzen

## Allgemein

| Feld                 | Beschreibung                   | mehr     |
| -------------------- | ------------------------------ | -------- |
| Lettershop           | der zugeordnete Lettershop     |          |
| Kunde                | Bezeichnung des Kunden         |          |
| Kundennummer         | optionale Kundennummer         |          |
| ergänzende Zuordnung | optionales Gruppierungsmerkmal | Freitext |

## Kontaktdaten

Bei folgenden Daten handelt es sich um die Kontaktdaten des primären Kontakts des Kunden, z.B. Technischer Leiter

|                    |                       |   |
| ------------------ | --------------------- | - |
| E-Mail-Adresse     | Primärer Emailkontakt |   |
| Straße, Hausnummer |                       |   |
| Postleitzahl       |                       |   |
| Ort                |                       |   |
| Vorname            |                       |   |
| Nachname           |                       |   |
| Telefon            |                       |   |

## Zustellungs-Optionen

|                                         |                                         |                                                                        |
| --------------------------------------- | --------------------------------------- | ---------------------------------------------------------------------- |
| Standard Medientyp                      | Definiert Standard Medientyp            | siehe [medientypen.md](../themen/medientypen.md "mention")             |
| Admin darf Aufträge im Portal erstellen | Steuert Menüpunkt "Neuer Druckauftrag"  |                                                                        |
| Postalische Zustellung                  | Kunde verwendet postalische Zustellung  | Standard: ja                                                           |
| E-Mail Zustellung                       | Kunde verwendet Email Zustellung        |                                                                        |
| Digitale Zustellung                     | Kunde verwendet Digitale Zustellung     | siehe [digitaler-versand.md](../themen/digitaler-versand.md "mention") |
|                                         |                                         |                                                                        |

### &#x20;Foxdox / Postbox

Die folgenden Einstellungen gelten nur für d.velop Partner welche einen Postbox/Foxdox zugang haben - siehe hierzu [#foxdox-postbox](../themen/digitaler-versand.md#foxdox-postbox "mention")

|                                |                  |   |
| ------------------------------ | ---------------- | - |
| d.velop post Anbieter          | API Benutzername |   |
| d.velop post Anbieter Passwort | API Passwort     |   |
| d.velop Anbieter Schlüssel     | API Schlüssel    |   |

Die Einstellungen können mit dem Button `d.velop post Verbindung testen` jederzeit überprüft werden

### E-Mail

Die folgenden Einstellungen sind für den digitalen Emailversand notwendig - siehe hierzu [#e-mail](../themen/digitaler-versand.md#e-mail "mention")

Die Werte sind je nach Email-Anbieter unterschiedlich.

**Technischer Hinweis:** Der Versand findet außschließlich über TLS/SSL statt.

|                |                                        |                               |
| -------------- | -------------------------------------- | ----------------------------- |
| SMTP Server    | URL des Versandservers                 | z.B `smtp.meinedomain.de`     |
| SMTP Port      | Port des Servers                       | z.b `587`                     |
| Benutzer       | Benutzername                           | z.B. `email_user`             |
| Passwort       | Passwort                               |                               |
| Name Absender  |                                        | z.B  `Digital Versand`        |
| Email Absender |                                        | z.B. `versand@meinedomain.de` |
| Email Betreff  | Betreff ausgehender Emails             | siehe Platzhalter             |
| Email Text     | Text ausgehender Emails (HTML möglich) | siehe Platzhalter             |

#### Platzhalter Email Betreff / Text <a href="#platzhalter-email" id="platzhalter-email"></a>

Platzhalter....für Platzhalter

## Preise

{% hint style="warning" %}
<mark style="color:red;">Die folgenden Preis-Einstellungen</mark> <mark style="color:red;"></mark><mark style="color:red;">**überschreiben**</mark> <mark style="color:red;"></mark><mark style="color:red;">die Einstellungen die beim Lettershop hinterlegt sind. Dies ermöglicht individuelles Pricing je Kunde.</mark>
{% endhint %}

|                               |                                       |                    |
| ----------------------------- | ------------------------------------- | ------------------ |
| Preis Farbdruck               | Kosten je Farbdruck                   | Angabe in EUR-Cent |
| Preis SW-Druck                | Kosten je SW-Druck                    | Angabe in EUR-Cent |
| Preis automatisch kuvertieren | Kosten je Kuvertier-Vorgang (Sendung) | Angabe in EUR-Cent |
| Preis Standard Papier         | je Blatt                              | Angabe in EUR-Cent |
| Preis digital                 | je Sendung                            | Angabe in EUR-Cent |
| Preis Email                   | je Sendung                            | Angabe in EUR-Cent |

## Sicherheit & Compliance

Die folgenden Optionen ermöglichen Compliance und individuellen Sicherheitsstandards des Kunden

|                                                      |   |                                                                                             |
| ---------------------------------------------------- | - | ------------------------------------------------------------------------------------------- |
| Anmeldung beschränken auf IP Bereich - Start-Adresse |   | z.B. `109.75.210.0`                                                                         |
| Anmeldung beschränken auf IP Bereich - End-Adresse   |   | z.B. `109.72.210.255`                                                                       |
| minimale Passwortlänge                               |   |                                                                                             |
| min. Anzahl Großbuchstaben in Passwort               |   |                                                                                             |
| min. Anzahl Kleinbuchstaben in Passwort              |   |                                                                                             |
| min. Anzahl Sonderzeichen in Passwort                |   |                                                                                             |
| min. Anzahl Ziffern in Passwort                      |   |                                                                                             |
| max. Passwortalter in Tagen                          |   | nach Ablauf dieser Frist werden Benutzer aufgefordert ihr Passwort selbstständig zu ändern. |

&#x20;
