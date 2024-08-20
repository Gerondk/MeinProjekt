# MeinProjekt

## Einrichten

- In Github anmelden
- "New" button oben links klicken.
- Repository name ("MeinProjekt") eingeben
- "Create repository" kliken.

## Lokales Klonen des Repository

- In Github den folgenden SSH Link kopieren: "git@github.com:Gerondk/MeinProjekt.git"
- Im Terminal den folgenden Befehl ausführen: "git clone git@github.com:Gerondk/MeinProjekt.git"

## Erstellen des "feature"-Branches

- Zu Repository-Folder wechseln
- Im Terminal den folgenden Befehl ausführen: 
  - git checkout -b feature
  - mkdir utils
  - cd utils
  - touch database.py
  - git add utils/database.py
  - git commit -m "Neue Funktion hinzugefügt"

## Merge feature-Branch

- Im Terminal den folgenden Befehl ausführen:
  - git checkout main
  - git add main.py (nach der Änderung)
  - git commit -m "Hauptdatei aktualisiert"
  - git merge feature
  - Im Edit Fenster Änderungen and ":wq" eingeben und "Eingabe-Taste" drücken 

