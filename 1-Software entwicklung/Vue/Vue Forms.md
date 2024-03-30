---
created: 2023-12-07 at 11:22
aliases:
  - "📜 - Class Note: Vue Forms"
tags:
  - Softwareentwicklung/Vue/Forms
011Version: 1
---
# ❗ Vue JS Formulare & Eingabefelder

**Video-Überblick:**
Dieses Tutorial von Net Ninja ist Teil einer Serie über Vue.js 3 und konzentriert sich auf die Verwendung von Formularen und Eingabefeldern. Es zeigt die Handhabung von Formulardaten, die Implementierung von Zwei-Wege-Datenbindung mit `v-model`, die Reaktion auf Formularübermittlungen und die Arbeit mit verschiedenen Formulareingabetypen wie Texteingaben, Auswahlboxen und Kontrollkästchen. Zusätzlich werden Tastaturereignisse und Formularübermittlung mit grundlegender Validierung behandelt.

## 📦 Ressourcen
- **Vue.js Dokumentation:** [Offizielle Vue.js Dokumentation](https://v3.vuejs.org/)
- **CSS-Styling:** Zusätzliche CSS-Tutorials und Ressourcen auf dem YouTube-Kanal von Net Ninja
- **Fortgeschrittene Formularverarbeitung:** Weitere Tutorials und Dokumentationen für fortgeschrittene Formularverarbeitung in Webanwendungen

## 🔑 Schlüsselpunkte

### 1. Einführung in Vue Formulare und Grundlegende Einrichtung
- **Erstellen eines Vue-Projekts:** Beginn mit der Erstellung eines neuen Vue-Projekts namens 'web-form' unter Verwendung der Vue CLI. Einrichtung umfasst Features wie Linter/Formatter und Babel-Konfiguration.
- **Styling und Struktur:** Grundlegendes CSS-Styling für Body und Formular zur Gestaltung von Layout und Erscheinungsbild.

### 2. Verwendung von `v-model` für Zwei-Wege-Datenbindung
- **Grundlagen von `v-model`:** Einführung in die `v-model`-Direktive zur Erstellung einer Zwei-Wege-Datenbindung an Formularelementen.
- **Verarbeitung von Texteingaben:** Demonstration der Verwendung von `v-model` bei Texteingaben für E-Mail und Passwort.

### 3. Arbeit mit Auswahlboxen
- **Implementierung einer Auswahlbox:** Erstellung einer Auswahlbox für Berufsrollen und Bindung des ausgewählten Werts an eine Vue-Daten-Eigenschaft.
- **Standardwerte festlegen:** Diskussion über die Festlegung von Standardwerten für Auswahlmöglichkeiten.

### 4. Umgang mit Kontrollkästchen
- **Einzelnes Kontrollkästchen:** Verwendung von `v-model` mit einem einzelnen Kontrollkästchen, Bindung seines Zustands an eine boolesche Vue-Daten-Eigenschaft.
- **Mehrere Kontrollkästchen mit Arrays:** Behandlung mehrerer Kontrollkästchen, deren geprüfte Werte in einem Array gespeichert werden.

### 5. Behandlung von Tastaturereignissen
- **Grundlagen von Tastaturereignissen:** Einführung in die Handhabung von Tastaturereignissen wie Keyup, Keypress und Keydown.
- **Fähigkeiten mit Tastaturereignissen hinzufügen:** Implementierung einer Funktion, bei der Benutzer Fähigkeiten durch Tippen und Verwenden eines bestimmten Tastendrucks (Komma) zur Liste hinzufügen können.

### 6. Formularübermittlung und Validierung
- **Behandlung der Formularübermittlung:** Anhängen eines Submit-Ereignislisteners an ein Formular und Überschreiben des standardmäßigen Übermittlungsverhaltens, um das Neuladen der Seite zu verhindern.
- **Grundlegende Validierung:** Implementierung einer grundlegenden Validierung für das Passwortfeld.

### 7. Erweiterte Funktionen und Herausforderungen
- **Löschfunktion für Fähigkeiten:** Hinzufügen eines Klickereignisses zu jedem Fähigkeiten-Pill, um Benutzern das Entfernen einer Fähigkeit aus der Liste zu ermöglichen.
- **Styling der Fähigkeiten-Pills:** Zusätzliches CSS-Styling für eine bessere Benutzeroberfläche.

### 8. Finalisierung und Testen des Formulars
- **Protokollierung von Formulardaten:** Bei der Formularübermittlung werden die eingegebenen Daten (E-Mail, Passwort, Rolle, Fähigkeiten, Akzeptanz der Bedingungen) in der Konsole protokolliert.


- **Testen der Funktionalität:** Das Tutorial endet mit einer Demonstration der gesamten Funktionalität des Formulars.

## 💯 Lernziele
- Verständnis der Grundlagen von Formularen und Eingabefeldern in Vue.js
- Fähigkeit, Zwei-Wege-Datenbindung mit `v-model` zu implementieren
- Kenntnisse im Umgang mit verschiedenen Formulareingabetypen
- Erfahrung in der Handhabung von Tastaturereignissen und Formularübermittlungen

## 📃 Zusammenfassung der Notizen
Dieses Tutorial bietet eine umfassende Anleitung zur Arbeit mit Formularen in Vue.js und demonstriert wichtige Konzepte anhand praktischer Beispiele und realer Szenarien.