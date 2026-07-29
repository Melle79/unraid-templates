# Unraid-Vorlagen von Melle79

Dieses Repository liefert die Docker-Vorlagen für **Unraid Community
Applications**. Es enthält keinen Programmcode – nur die XML-Dateien, aus
denen der Katalog seine Einträge baut.

| App | Beschreibung | Projekt |
|---|---|---|
| **Brickfolio** | Selbstgehostete PWA für LEGO-Sammlungen: scannen, verwalten, bewerten | [Melle79/brickfolio](https://github.com/Melle79/brickfolio) |

## Aufbau

    ca_profile.xml         Beschreibung dieses Repositories (verlangt der Katalog)
    templates/*.xml        je eine Vorlage pro App
    icon.png               Symbol des Repositories

## Ohne Community Applications installieren

Die Vorlage lässt sich auch direkt einlesen: in Unraid unter *Docker →
Vorlage hinzufügen* diese Adresse eintragen:

    https://raw.githubusercontent.com/Melle79/unraid-templates/main/templates/brickfolio.xml
