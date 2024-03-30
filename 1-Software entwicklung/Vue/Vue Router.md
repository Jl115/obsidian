---
created: 2023-12-04 at 18:34
aliases:
  - "📜 - Class Note: Vue Router"
tags:
  - Softwareentwicklung/Vue/Router
011Version: 1
---
# ❗ Thema: Vue JS 3 Tutorial - Der Vue Router

## 📦 Ressourcen
- Offizielle Dokumentation von Vue Router: [Vue Router](https://router.vuejs.org/)
- Vue CLI: [Vue CLI](https://cli.vuejs.org/)
- Verständnis von Single Page Applications: [Single Page Applications](https://developer.mozilla.org/en-US/docs/Glossary/SPA)
- Erweiterte Funktionen des Vue Routers: Dynamisches Routen-Matching, verschachtelte Routen und Route Guards.
- Vue Router und State Management: Integration des Vue Routers mit Vuex für das State Management.
- Serverseitiges Rendering mit Vue Router: Implementierung des Vue Routers in serverseitig gerenderten Anwendungen mit Frameworks wie Nuxt.js.

## 🔑 Schlüsselpunkte

#### Einführung in Vue Router
- Vue JS ermöglicht die Erstellung von Single-Page-Applications (SPA).
- In SPAs wird eine einzelne HTML-Seite vom Server gesendet, danach übernimmt Vue das Routing im Browser.
- Vue injiziert dynamisch Komponenten für verschiedene Routen in die Root-App-Komponente basierend auf der URL-Route.

#### Einrichtung von Vue Router
- Vue Router ist ein separates Paket, das mit Vue zusammenarbeitet, um ein Routing-System zu etablieren.
- Es kann manuell oder über die Vue CLI eingerichtet werden.
- Die Vue CLI vereinfacht den Einrichtungsprozess, indem sie den Router in neuen Projekten automatisch konfiguriert.

#### Router-Konfiguration
- Vue Router benötigt einen `router` Ordner mit einer `index` Datei.
- Die `index` Datei enthält ein `routes` Array, wobei jedes Objekt eine Route repräsentiert.
- Jedes Route-Objekt umfasst den `path`, `name` und die zu rendernde `component`.
- Die Router-Instanz wird am Ende der Index-Datei mit `createRouter` erstellt.
- Die Funktion `createWebHistory` wird verwendet, um die Browsernavigation durch Routen zu ermöglichen.

#### Implementierung von Routen in Templates
- Das `router-view` Tag in der Root-Komponente (`App.vue`) zeigt an, wo Route-Komponenten gerendert werden.
- Der Ordner `views` enthält typischerweise Route-Komponenten (z.B. `Home`, `About`).

#### Router-Links
- Vue verwendet `router-link` Tags anstelle von Anker (`<a>`) Tags.
- `router-link` hat ein `to` Attribut, das den Pfad oder den Routennamen angibt.
- Es unterbricht Navigationsanfragen und verhindert vollständige Seitenneuladungen.
- Das `router-link` Tag kann für aktive Routen gestylt werden.

#### Dynamische Router-Links
- Dynamisches Binden an das `to` Attribut ermöglicht die Verwendung von Objekten für Routennamen.
- Dieser Ansatz vereinfacht die Wartung von Routen, da das Ändern von Pfadnamen an einer Stelle sich durch die gesamte Anwendung widerspiegelt.

#### Ordnerstruktur
- Für größere Anwendungen ist es ratsam, Komponenten in Unterordnern zu organisieren.
- Der Ordner `components` beinhaltet wiederverwendbare Komponenten, die nicht an spezifische Routen gebunden sind.

#### Routenparameter
- Routenparameter (z.B. IDs) werden im Pfad durch einen Doppelpunkt (`:`) gekennzeichnet.
- Sie können innerhalb von Komponenten über `$route.params` abgerufen werden.
- Routenparameter können auch als Props an Komponenten übergeben werden.

#### Umleitungen und 404-Seiten
- Umleitungen werden in der `router` Index-Datei mit der `redirect` Eigenschaft konfiguriert.
- Eine Catch-All-Route (`*`) kann verwendet werden, um eine 404 Nicht Gefunden-Seite für undefinierte Routen anzuzeigen.

#### Programmatische Navigation
- Vue Router ermöglicht programmatische Navigation mit `this.$router.go()` für die Historiennavigation und `this.$router.push()` für Routenumleitungen.
- Die `go()` Methode navigiert vorwärts oder rückwärts in der Browserhistorie.
- Die `push()` Methode fügt eine neue Route zum Historienstapel hinzu und leitet den Benutzer um.

## ❓ Fragen & Antworten

*Für spezifische Fragen zum Tutorial, bitte hier einfügen

.*

## 💯 Lernziele
- Verständnis der Grundlagen und der Konfiguration des Vue Routers.
- Fähigkeit zur Einrichtung und Verwendung von Vue Router in Vue JS-Projekten.
- Kenntnis der fortgeschrittenen Funktionen und Integrationsmöglichkeiten des Vue Routers.

## 📃 Zusammenfassung der Notizen

*Hier können ergänzende Notizen und wichtige Punkte aus dem Tutorial zusammengefasst werden.*