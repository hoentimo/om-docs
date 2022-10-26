---
description: Im folgenden wird die Einrichtung der Erkennungsmerkmale beschrieben.
---

# Reguläre Ausdrücke

Es ist möglich, Reguläre Ausdrücke für die Erkennung sowie Extraktion von Daten zu verwenden.

Da diese Optionen in verschiedenen Komponenten auftreten, werden diese hier einmalig erklärt.

### Verwendung

Es ist möglich Reguläre Ausdrücke (Regular Expressions) zu verwenden, um dynamische Werte zu filtern und so einen Identifizierer zu erstellen.\
\
So kann z.B. der Vergleichswert  `.*(Mahnung|Erinnerung|Aufforderung).*` verwendet werden um den Betreff eines Dokuments zu erkennen, welches die Werte "Mahnung", "Erinnerung" oder "Aufforderung" enthalten.\


{% hint style="info" %}
Hilfe/Tools zu Regulären Ausdrücken unter [https://regex101.com/](https://regex101.com/)
{% endhint %}



### Erkennungstyp

| Auswahl    | Erklärung                                                    | mehr                                                       |
| ---------- | ------------------------------------------------------------ | ---------------------------------------------------------- |
| enthält    | Der Vergleichswert ist im ausgewählten Bereich enthalten.    | `Versicherung` ist im Wort `Versicherungspolice` enthalten |
| entspricht | Der Wert im Dokument entspricht **exakt** dem Vergleichswert | Groß/Kleinschreibung und Sonderzeichen werden beachtet.    |

### Filter für Ergebnis <a href="#filter-fuer-ergebnis" id="filter-fuer-ergebnis"></a>

?





##
