---
created: 2023-10-28 at 13:26
aliases:
  - 📜 - Class Note:Schultag 28-10
tags:
  - Course/Semester3/Modul347/Schultag-28-10
011Version: 1
---
# ❗ Topic
- 


 ---
## 📦 Resources
- 
## ## 🔑 Key Points

- ### Die wichtigsten Punkte von der Schule:
    
    - Verstehen der grundlegenden Netzwerkkonzepte und wie Daten im Internet übertragen werden.
    - Wissen über verschiedene Softwareentwicklungs-Ports und ihre spezifischen Verwendungen.

---

- ### Ports Softwareentwickler:
    
    1. **Port 80 (HTTP)**: Standardprotokoll für den Webzugriff.
    2. **Port 443 (HTTPS)**: Verschlüsselte und sichere Webkommunikation.
    3. **Port 22 (SSH)**: Sichere Terminalverbindung.
    4. **Port 21 (FTP)**: Dateiübertragung.
    5. **Port 3306 (MySQL)**: Datenbankkommunikation.
    6. **Port 5432 (PostgreSQL)**: Datenbankkommunikation.
    7. **Port 25 (SMTP)**: E-Mail-Übertragung.
    8. **Port 1433 (Microsoft SQL Server)**: Datenbankkommunikation.
    9. **Port 8080**: Alternativer HTTP-Port für Entwicklungszwecke.

---

- # Notes Input Präsentation
    

## ❓ Prerequisites

- Grundlegende Kenntnisse über Netzwerkkonzepte und Datenübertragung.
- Verständnis von Softwareentwicklung und Deployment-Prozessen.

---

## ❓ Q & A

- ### Notes Input Präsentation: Erstellung von Docker-Images
    
    - #### Warum sollte man ein eigenes Image einer Applikation mit Docker erstellen?
        
        - Es bietet eine **konsistente Umgebung**: Die Applikation läuft immer in derselben Umgebung, unabhängig von der Infrastruktur.
        - **Portabilität**: Ein Docker-Image ist portabel und kann über verschiedene Systeme hinweg ausgeführt werden.
        - **Skalierbarkeit**: Mehrere Instanzen des Images können gleichzeitig ausgeführt werden.
        - **Versionierung und Rollbacks**: Einfaches Verwalten von verschiedenen Versionen.
        - **Sicherheit**: Kontrolle über den Inhalt und die Konfiguration der Applikation.
    - #### Wie wird eine Dockerfile strukturiert, um eine Python/Flask-Applikation zu erstellen?
        
        1. **Basisimage auswählen**:
        
        Dockerfile
        

`FROM python:3.9`

2. **Arbeitsverzeichnis festlegen**:

Dockerfile

`WORKDIR /app`

3. **Anwendungsdateien kopieren**:

Dockerfile

`COPY . /app`

4. **Abhängigkeiten installieren**:

Dockerfile

`RUN pip install --no-cache-dir -r requirements.txt`

5. **Umgebungsvariablen setzen**:

Dockerfile

`ENV FLASK_APP=app.py ENV FLASK_RUN_HOST=0.0.0.0`

6. **Startbefehl angeben**:

Dockerfile

- - `CMD ["flask", "run"]`
        
    - #### Wie funktionieren Umgebungsvariablen in einem Dockerfile?
        
        - Direkte Zuweisung über das `ENV`-Stichwort. Beispiel: `ENV MY_VARIABLE=my_value`
        - Über den Befehl `docker build`, z.B.: `docker build --build-arg MY_VARIABLE=my_value .`
        - Referenzieren von Variablen im Dockerfile mit `$`, z.B.: `RUN echo $MY_VARIABLE`

---

## 🎯 Learning Objectives

- Verständnis für die Bedeutung und den Einsatz von Docker in der Softwareentwicklung.
- Fähigkeit, Docker-Images für Anwendungen zu erstellen und zu verwalten.
- Kenntnisse über die Konfiguration und Verwendung von Umgebungsvariablen in Dockerfiles.

---

## 📃 Summary of Notes

- Docker ist ein wichtiges Werkzeug in der modernen Softwareentwicklung und bietet viele Vorteile wie Konsistenz, Portabilität und Skalierbarkeit.
- Mit Dockerfiles können Entwickler spezifizierte Images erstellen, die alle Abhängigkeiten und Konfigurationen für eine Anwendung enthalten.
- Umgebungsvariablen sind ein mächtiges Mittel zur Konfiguration von Docker-Containern und können auf verschiedene Weisen im Dockerfile definiert und verwendet werden.