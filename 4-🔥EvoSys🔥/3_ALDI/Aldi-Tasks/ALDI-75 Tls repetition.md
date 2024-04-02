---
created: 2024-04-01 at 05:14
aliases:
  - "🏫 - Class:"
tags:
  - Course/
  - /Index
012Version: 1
---

# 📃 - Class - `=this.file.aliases[0]`

---
# ❓ - Information
Subject::
Course Code:: 75
Tags:: #evosys 
Started:: 2024-04-01
Professors::
Speakers::

---
# 🌍 Subject Description
-   
---

## 📜 - Notes and Ideas
- Datenbank Anpassen:
---
#### Schema Tabelle location

| delay      | repeat    | break      | text_to_speach_conf_id |
| ---------- | --------- | ---------- | ---------------------- |
| int        | int       | int        | int                    |
| default 10 | default 3 | default 60 | pk                     |
| 0-100      | 0-10      | 0-300      |                        |
- ==Wichtig die sachen sind in milisekunden aber sollten als sekunden zählen==
----

## 🎯 - Assignments
1. 
## ⌛ - Lectures
1. 
## 📦 - Resources
1. 
## 📅 - Important Dates
- [ ] It should be possible to repeat text-to-speech output in a similar way to DIVERA 24/7. The repetition should only refer to the voice output and not also to the alarm tone.
- [ ] If text-to-speech is activated, it should be possible to specify the number of repetitions of the voice output in a separate field ("Wiederholung", default is 10)
- [ ] If text-to-speech is activated, the seconds between repetitions of the voice output should be able to be specified in a separate field ("Pause", default is 60)
- [ ] Current problem: If the alarm tone is set to mute, the voice output does not start immediately, but waits a few seconds. The voice output should start immediately.
- [ ] Additional:
- [ ] on getPlans add Plan type “Trainingsobjekt” colors
- [x] in serialising remove replace slash logic to allow slashes in textes (especially in marquee)


