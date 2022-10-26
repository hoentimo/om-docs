# Vorgangstrenner

Als Vorgangstrenner wird das Merkmal bezeichnet, welches die einzelnen Sendungen innerhalb eines Dokuments mit mehreren Vorgängen trennt.

{% hint style="danger" %}
Der Vorgangstrenner muss in **jeder Sendung** enthalten sein - er ist verpflichtend notwendig um eine korrekte Aufteilung der Sendungen zu ermöglichen.
{% endhint %}

{% hint style="info" %}
**Tipp:** In vielen Fälle kann der Identifizierer als Vorgangstrenner dienen.
{% endhint %}

{% hint style="info" %}
Der Vorgangstrenner kann auch ein [weisstext.md](../../fortgeschrittene-themen/weisstext.md "mention") sein
{% endhint %}

![Beispiel: Vorgangstrenner - in diesem Fall kann das gleiche Merkmal wie der Identifizierer verwendet werden](<../../.gitbook/assets/grafik (2).png>)

### Optionen

#### Vorgangstrenner auf Startseite des Vorgangs

Dies ist die Standardeinstellung - nur die erste Seite des Vorgangs wird durchsucht

#### **Vorgangstrenner bei geändertem Wert**

Der Inhalt des Vorgangstrenners wird zwischen Vorgängen verglichen.  So kann z.B. ein Vorgangstrenner inklusive einer Kundennummer definiert werden wie `Rechnung für Kunde <Kundennummer>.` Bei jeder Änderung des Textes wird automatisch ein neuer Vorgang erzeugt.

{% hint style="warning" %}
Diese Option ist **nur für erfahrene Benutzer** gedacht da sie unvorhersehbare Effekte haben kann. **Jede Änderung** des Inhaltes des Vorgangstrenners erzeugt einen neuen Vorgang (exakter Vergleich)
{% endhint %}
