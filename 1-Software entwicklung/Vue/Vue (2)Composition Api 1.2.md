---
created: 2023-12-07 at 11:35
aliases:
  - "📜 - Class Note: Vue Composition Api 1.2"
tags:
  - Course/
  - /Note
011Version: 1
---
# ❗ Vue JS 3 Tutorial für Anfänger #11 - Die Composition API (Teil 2)

**Video-Überblick:**
Dieses Tutorial von Net Ninja setzt die Erkundung der Composition API in Vue.js 3 fort und geht auf fortgeschrittene Themen ein, wie den Umgang mit Props, Lebenszyklus-Hooks, das Abrufen von Daten und das Erstellen wiederverwendbarer Composition-Funktionen (Composables).

## 📦 Ressourcen
- **Vue.js 3 Dokumentation zur Composition API:** [Offizielle Vue.js 3 Dokumentation](https://v3.vuejs.org/guide/composition-api-introduction.html)
- **Asynchrones JavaScript:** Zur Vertiefung des Verständnisses von `async` und `await` in JavaScript empfiehlt sich die Überprüfung relevanter JavaScript-Tutorials oder Dokumentationen.

## 🔑 Schlüsselpunkte

### 1. Verwendung von Props mit der Composition API
- **Verschachtelung von Komponenten:** Demonstration der Weitergabe von Props (z.B. Posts) von einer Elternkomponente (Home) an eine Kinderkomponente (PostList) mittels der `setup`-Funktion.
- **Akzeptieren von Props:** Zeigt, wie Props in der `setup`-Funktion der Kinderkomponente akzeptiert und verwendet werden.

### 2. Lebenszyklus-Hooks in Setup
- **Verwendung von Lebenszyklus-Hooks:** Einführung der Nutzung von Lebenszyklus-Hooks (z.B. `onMounted`, `onUpdated`, `onUnmounted`) direkt in der `setup`-Funktion.
- **Kombination mit der Options API:** Veranschaulicht, dass die traditionelle Options API weiterhin neben der Composition API für Lebenszyklusmethoden verwendet werden kann.

### 3. Datenabruf in Setup
- **Asynchroner Datenabruf:** Erklärung, wie asynchrone Operationen innerhalb der `setup`-Funktion mit `async` und `await` durchgeführt werden. Behandelt das Abrufen von Daten von einem JSON-Server und das Verarbeiten von Antworten und Fehlern.

### 4. Wiederverwendbare Composable-Funktionen
- **Erstellen von Composables:** Detaillierte Erstellung externer, wiederverwendbarer Funktionen (Composables) für den Datenabruf. Diese Funktionen werden dann bei Bedarf in Komponenten importiert.
- **Beispiel-Composable:** Erstellung eines `getPost`-Composables zum Abrufen einzelner Blogposts. Demonstration des Imports und der Verwendung dieses Composables in einer Komponente.

### 5. Implementierung einer Post-Details-Komponente
- **Routing zu Details:** Darstellung der Einrichtung eines Routings für eine Post-Detailseite, einschließlich der Weitergabe eines Routenparameters (`id`) an die `Details`-Komponente.
- **Abrufen von Post-Details:** Verwendung des `getPost`-Composables in der `Details`-Komponente, um individuelle Post-Details basierend auf der übergebenen `id` abzurufen und anzuzeigen.

### 6. Stil- und Template-Verbesserungen
- **Hinzufügen von Stilen:** Abschluss mit der Hinzufügung von CSS-Stilen für die `Details`-Komponente zur Verbesserung der Anzeige von Post-Titeln und -Inhalten.

## 💯 Lernziele
- Verständnis für fortgeschrittene Aspekte der Composition API in Vue.js 3
- Fähigkeit, Props, Lebenszyklus-Hooks und asynchronen Datenabruf effektiv zu nutzen
- Kenntnisse im Erstellen und Implementieren wiederverwendbarer Composables

## 📃 Zusammenfassung der Notizen
Dieses Tutorial demonstriert effektiv die Leistungsfähigkeit und Flexibilität der Vue.js 3 Composition API, insbesondere bei der Erstellung organisierter, wartbarer und wiederverwendbarer Code. Die praktischen Beispiele, wie das Abrufen von Daten und das Einrichten von Composables, bieten wertvolle Einblicke für Vue.js-Entwickler.
