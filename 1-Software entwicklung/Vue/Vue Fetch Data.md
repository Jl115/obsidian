---
created: 2023-12-07 at 11:31
aliases:
  - "📜 - Class Note: Vue Datafetching"
tags:
  - Softwareentwicklung/Vue/DataFetching
011Version: 1
---
# ❗ Vue JS 3 Daten abrufen

**Video-Überblick:**
Dieses Tutorial von Net Ninja befasst sich mit dem Abrufen externer Daten in Vue.js 3 Komponenten. Es führt den JSON Server zur Simulation des Datenabrufs von einer API ein, zeigt, wie man in Komponenten Daten mit der `fetch` API abruft, und behandelt die bedingte Darstellung basierend auf den abgerufenen Daten.

## 📦 Ressourcen
- **JSON Server Dokumentation:** [Offizielle JSON Server Dokumentation](https://github.com/typicode/json-server)
- **Fetch API und Promises:** Für Unvertraute mit der Fetch API, JavaScript Promises oder asynchronem JavaScript
- **Vue.js Lebenszyklus-Hooks:** [Vue.js Dokumentation zu Lebenszyklus-Hooks](https://v3.vuejs.org/guide/instance.html#lifecycle-hooks)

## 🔑 Schlüsselpunkte

### 1. Einführung in JSON Server
- **JSON Server Einrichtung:** Einrichtung von JSON Server zur Simulation einer API mit einer `db.json` Datei, die in API-Endpunkte umgewandelt wird.
- **Erstellen von JSON-Daten:** Demonstration der Erstellung einer `db.json` Datei mit einem 'jobs'-Ressourcenarray, das Job-Objekte enthält.

### 2. Daten in Komponenten abrufen
- **Mounted Lifecycle Hook:** Implementierung des Datenabrufs im `mounted` Lebenszyklus-Hook von Vue-Komponenten.
- **Verwendung der Fetch API:** Demonstration der Verwendung der `fetch` API zur Datenanforderung vom JSON Server.

### 3. Komponentendaten befüllen
- **Aktualisierung von Komponentendaten:** Nach dem Abrufen der Daten werden diese verwendet, um die Daten-Eigenschaft einer Vue-Komponente zu füllen (z.B. `this.jobs` wird auf das abgerufene Jobs-Array gesetzt).
- **Fehlerbehandlung:** Implementierung einer `.catch()` Methode zur Fehlerprotokollierung bei fehlgeschlagenen Abrufanfragen.

### 4. Daten für Jobdetails abrufen
- **Jobdetails-Komponente:** Zeigt das Abrufen individueller Jobdetails in einer `JobDetails`-Komponente unter Verwendung der als Prop übergebenen Job-ID.
- **Dynamischer Endpunkt:** Der Endpunkt zum Abrufen individueller Jobdaten wird dynamisch mit der Job-ID erstellt (`/jobs/${this.id}`).

### 5. Bedingte Darstellung basierend auf Daten
- **Umgang mit Nullwerten:** Behandlung des Problems, auf Eigenschaften von `null` zuzugreifen, wenn die Daten anfangs nicht verfügbar sind. Lösung durch bedingte Darstellung mit `v-if`.
- **Ladeindikatoren:** Hinzufügen einer 'Lade'-Nachricht während des Datenabrufs mit der `v-else`-Direktive.

### 6. Verbesserung der Benutzererfahrung
- **Bedingte Anzeige der Jobliste:** Implementierung einer bedingten Darstellung der Jobliste in der `Jobs`-Komponente, um eine 'Lade Jobs'-Nachricht anzuzeigen, bis die Jobdaten abgerufen und verfügbar sind.
- **Verfeinerung der Ladeindikatoren:** Demonstration der kurzzeitigen Anzeige von Ladeindikatoren während des Datenabrufprozesses.

## 💯 Lernziele
- Verständnis für das Abrufen und Verarbeiten externer Daten in Vue.js-Komponenten
- Fähigkeit, Daten mit der Fetch API abzurufen und zu verarbeiten
- Kenntnis von bedingter Darstellung und Lebenszyklus-Hooks in Vue.js

## 📃 Zusammenfassung der Notizen
Dieses Tutorial demonstriert effektiv das Abrufen und die Handhabung externer Daten innerhalb von Vue.js-Komponenten, bietet praktische Beispiele und erklärt wichtige Konzepte für Anfänger.