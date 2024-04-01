---
created: 2024-04-01 at 16:51
aliases:
  - "📜 - Class Note: JavaScript Hoisting"
tags:
  - Softwareentwicklung/javascript
011Version: 1
---

## 📦 Ressourcen
- https://developer.mozilla.org/en-US/docs/Glossary/Hoisting
- https://www.w3schools.com/js/js_hoisting.asp

## 🔑 Schlüsselpunkte
- Hoisting ist ein JavaScript-Mechanismus, bei dem Variablen und Funktionsdeklarationen an den Anfang ihres jeweiligen Bereichs (Scope) verschoben werden.
- Es ist wichtig zu beachten, dass nur die Deklarationen verschoben werden, nicht die Initialisierungen.
- Bei Variablen bedeutet dies, dass sie deklariert sind, aber undefiniert bleiben bis zur Zuweisung eines Wertes.
- Bei Funktionen bedeutet dies, dass die gesamte Funktion an den Anfang verschoben wird und vollständig verwendbar ist.
- Hoisting tritt automatisch in JavaScript auf und kann zu unerwarteten Ergebnissen führen, wenn man es nicht versteht.

## ❓ Voraussetzungen
- Grundkenntnisse in JavaScript

## ❓ Fragen & Antworten
1. Was wird in JavaScript gehoistet?
   - In JavaScript werden sowohl Variablendeklarationen (mit 'var') als auch Funktionsdeklarationen gehoistet.

## 🎯 Lernziele
- [ ] Verstehen, was Hoisting in JavaScript ist
- [ ] Verstehen, wie Hoisting das Verhalten von Code beeinflussen kann

## 📃 Zusammenfassung der Notizen
- Hoisting ist ein Prozess in JavaScript, bei dem Deklarationen von Variablen und Funktionen an den Anfang ihrer jeweiligen Bereiche (Scopes) verschoben werden. 
- Dies bedeutet, dass man eine Variable oder Funktion verwenden kann, bevor sie deklariert wurde. 
- Es ist jedoch wichtig zu beachten, dass beim Hoisting nur die Deklarationen und nicht die Initialisierungen an den Anfang verschoben werden. 
- Daher wird der Versuch, auf den Wert einer gehoisteten Variable zuzugreifen, bevor ihr ein Wert zugewiesen wurde, zu 'undefined' führen.
- Bei Funktionen wird die gesamte Funktion zum Zeitpunkt des Hoisting vollständig
### Beispiel

``` js
x = 5; // Assign 5 to x  
  
elem = document.getElementById("demo"); // Find an element  
elem.innerHTML = x;                     // Display x in the element  
  
var x; // Declare x
```
## 📃 Hand notes
- 