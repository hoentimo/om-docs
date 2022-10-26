# Adressbereich

Jede Sendung **muss** einen Adressbereich besitzen - dieser muss innerhalb der Vorgaben des Adressbereichs liegen.

* &#x20;siehe [#position-adressbereich](../../themen/adressen.md#position-adressbereich "mention") sowie [#adresse-syntax](../../themen/adressen.md#adresse-syntax "mention") für weitere Informationen, welche Adressinformationen zwingend notwendig sind und wie diese zu formatieren sind.

![Beispiel: Korrekt platzierter und erkannter Adressbereich](<../../.gitbook/assets/image (4).png>)

### Alternative Textsortierung

Sollte eine korrekte Erkennung des Adressbereichs nicht möglich sein, kann diese Option verwendet werden.&#x20;

{% hint style="info" %}
Das Ergebnis ist abhängig von der Software, welche das Quelldokument erzeugt hat.
{% endhint %}

### Adressbereich-Verschiebung

Das System besitzt eine intelligente Adressbereichverschiebung, welche - unter gewissen Einschränkungen - nicht sauber gesetzte Adressbereiche verschieben kann.&#x20;

{% hint style="warning" %}
Diese Option sollte nur verwendet werden, wenn Seitens des Kunden eine Anpassung der Quelldokumente nicht möglich oder mit sehr hohem Aufwand verbunden ist. Es sollte Ziel sein, bereits korrekt positionierte Quelldokumente seitens der Kunden zu erhalten
{% endhint %}

#### Option: Zielbereich überdecken

Diese Option bewirkt, dass der Zielbereich mit einem weißen Hintergrund hiniterlegt wird - somit werden eventuell störende Objekte welche im Bereich sind überdeckt.
