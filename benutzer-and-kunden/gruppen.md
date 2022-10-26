# Gruppen

## Allgemein

* Der Begriff "Gruppe" ist im Kontext des Outputmanagers eine Gruppe von Benutzer-Zugängen



* Jede Gruppe ist **genau einem Kunden** zugewiesen
* Benutzergruppen können Kostenstellen zugewiesen werden (siehe [kostenstellen.md](../administration/kostenstellen.md "mention"))

{% hint style="warning" %}
Die **individuellen Einstellungen auf Gruppen-Ebene überschreiben die Rechte auf Kunden-Ebene** ( [kunden.md](kunden.md "mention"))
{% endhint %}

## <mark style="color:red;">Einschränkung</mark>: Gruppen und Druckaufträge

Druckaufträge welche von einem Benutzer einer Gruppe erstellt werden, werden automatisch dieser Gruppe zugeordnet.

SCHAUBILD EINFÜGEN

## <mark style="color:red;">Einschränkung</mark>: Gruppen und Vorlagen

Druckaufträge welche von einem Benutzer einer Gruppe erstellt werden, können nur Vorlagen, welche der gleichen Gruppe zugeordnet sind, erkannt werden.

SCHAUBILD EINFÜGEN





## Gruppen verwalten

![](<../.gitbook/assets/grafik (5).png>)

### Attribute

Im folgenden Sind alle Attribute für Gruppen beschrieben.

{% tabs %}
{% tab title="Allgemein" %}
#### Kunde

Welchem Kunden soll die Gruppe zugewiesen werden?

#### Kostenstelle

Optionale Auswahl einer Kostenstelle - siehe [kostenstellen.md](../administration/kostenstellen.md "mention")

#### Name&#x20;

Bezeichnung der Gruppe z.B. `Buchhaltung`, `Geschäftsführung`

#### Code

Ein individueller Code - der z.B. einer internen Kodierung entspricht

#### Beschreibung

Ein Optionaler Beschreibungstext
{% endtab %}

{% tab title="Preise" %}
#### siehe  [preiszuordnung.md](../themen/preiszuordnung.md "mention")
{% endtab %}

{% tab title="Einschränkungen beim Druck" %}
Diese Einschränkungen basieren auf der Auswahl des Kunden - eine allgemeine Erklärung zu allen Optionen zu finden unter:

[#einschraenkungen-beim-druck](rollen-and-rechte/druckbenutzer.md#einschraenkungen-beim-druck "mention")
{% endtab %}
{% endtabs %}





####



