---
created: 2023-12-07 at 11:33
aliases:
  - "📜 - Class Note: Vue Composition Api 1.1"
tags:
  - Softwareentwicklung/Vue/CompositionApi
011Version: 1
---
# ❗ Vue JS 3 Composition API (Teil 1)

**Video-Überblick:**
Dieses Tutorial von Net Ninja bietet eine ausführliche Einführung in die Composition API von Vue.js 3 und stellt sie der in früheren Tutorials verwendeten Options API gegenüber. Es behandelt die Grundlagen der Composition API, einschließlich reaktiver Variablen, der Funktionen `ref` und `reactive`, berechneter Eigenschaften und spezieller Hooks wie `watch` und `watchEffect`.

## 📦 Ressourcen
- **Vue.js 3 Dokumentation:** [Offizielle Vue.js 3 Dokumentation zur Composition API](https://v3.vuejs.org/guide/composition-api-introduction.html)
- **Reaktivität in Vue.js:** [Vue.js Dokumentation zur Reaktivität](https://v3.vuejs.org/guide/reactivity-fundamentals.html)

## 🔑 Schlüsselpunkte

### 1. Einführung in die Composition API
- **Composition vs. Options API:** Erklärung der Composition API als Alternative zur Options API für die Erstellung von Vue-Komponenten.
- **Verwendung der `setup` Funktion:** Demonstration der Erstellung einer `setup`-Funktion in Vue-Komponenten.

### 2. Erstellung und Rückgabe von Werten in `setup`
- **Einfache Variablen:** Zeigt, wie man einfache Variablen (z.B. `let name = 'Mario'`) in der `setup`-Funktion deklariert und zurückgibt.
- **Reaktivität mit `ref`:** Einführung der `ref`-Funktion zur Erstellung reaktiver Variablen.

### 3. Reaktivität im Detail
- **Aktualisierung reaktiver Variablen:** Demonstration der Änderung reaktiver Variablen (z.B. `name.value = 'Luigi'`).
- **Verwendung von `reactive` für Objektreaktivität:** Einführung der `reactive`-Funktion zur Erstellung reaktiver Objekte.

### 4. Berechnete Eigenschaften
- **Erstellung berechneter Eigenschaften:** Erklärung, wie man die `computed`-Funktion in der `setup`-Funktion verwendet.
- **Praktisches Beispiel mit Filterung:** Beispiel für die Verwendung berechneter Eigenschaften zur Filterung einer Namensliste.

### 5. Beobachtung reaktiver Änderungen
- **Verwendung von `watch` und `watchEffect`:** Beschreibt, wie `watch` und `watchEffect` verwendet werden, um Code auszuführen, wenn sich reaktive Variablen ändern.

### 6. Beenden von Watchers
- **Beenden von `watch` und `watchEffect`:** Zeigt, wie man `watch` und `watchEffect` beendet.

## 💯 Lernziele
- Verständnis der Grundlagen der Composition API in Vue.js 3
- Fähigkeit, reaktive Variablen, berechnete Eigenschaften und spezielle Hooks zu verwenden
- Kenntnisse im Umgang mit der `setup`-Funktion und dem Lifecycle-Hook-Konzept

## 📃 Zusammenfassung der Notizen
Dieses Tutorial bietet eine umfassende Einführung in die Composition API in Vue.js 3 und hebt ihre Vorteile für die Organisation und Wiederverwendung von Code in größeren Projekten hervor. Die praktischen Beispiele und detaillierten Erklärungen bilden eine solide Grundlage für das Verständnis dieser leistungsstarken Funktion von Vue.js.
