# 35_moodle-pAIpline

Prototypische Pipeline zur KI-gestützten Erstellung von Moodle-Kursen.

## Projektziel
Ziel dieses Projekts ist die Konzeption und prototypische Umsetzung
einer Pipeline zur Unterstützung der Moodle-Kurserstellung mit Hilfe
von Large Language Models (LLMs).
Der Schwerpunkt liegt auf der Analyse der internen Moodle-XML-Struktur
und der Definition, wie KI-generierte Inhalte in diese Struktur
integriert werden könnten.

## Technologien
- Moodle (lokale Installation)
- PHP / XML (internes Moodle-Format)
- Large Language Models (z. B. ChatGPT)
- Git zur Versionsverwaltung

## Projektstruktur
35_moodle-pAIpline/
├── README.md
├── docs/
│ ├── xml-analysis.md
│ ├── pipeline.md
│ └── limitations.md
└── examples/
├── moodle-xml/
└── prompts/

## Projektfortschritt nach Sprints

### Sprint 1 – Projektsetup & Grundlagen
- Projektidee und Zieldefinition festgelegt
- Lokale Moodle-Installation vorbereitet
- Git-Repository angelegt und Grundstruktur erstellt
- Erste Recherche zur Moodle-Kursstruktur durchgeführt
- Rollen und Aufgaben im Team grob definiert
- Datenbank (MariaDB) eingerichtet

### Sprint 2 – Moodle-Kurs & Inhalte
- Beispielkurs in Moodle manuell erstellt
- Erste Kursinhalte (Textseiten) hinzugefügt
- Quiz und Fragen im Moodle-System angelegt
- Funktionsweise von Kursen und Aktivitäten analysiert
- Vorbereitung für Kurs-Backups und XML-Analyse

### Sprint 3 – Moodle-Backup & XML-Extraktion
- Kurs-Backup in Moodle angestoßen
- Temporäre Backup-Dateien im moodledata-Verzeichnis identifiziert
- Relevante XML-Dateien aus dem Backup extrahiert
- Struktur des Moodle-Backups untersucht
- XML-Dateien in das Projekt übernommen

### Sprint 4 – XML-Analyse & Pipeline-Konzept
- Analyse von moodle_backup.xml durchgeführt
- Analyse der course.xml (Kurs-Metadaten)
- Analyse der questions.xml (Quiz & Question Bank)
- XML-Struktur dokumentiert und beschrieben
- Konzeptionelle KI-Pipeline definiert

### Sprint 5 – KI-Integration (konzeptionell)
- KI-Prompts zur Kurserstellung entworfen
- KI-generierte Beispielinhalte erstellt
- Zuordnung von KI-Inhalten zur Moodle-XML-Struktur definiert
- Mapping KI → XML dokumentiert
- Erweiterung der Projekt-Dokumentation

### Sprint 6 – Vorbereitung Abschlusspräsentation
- Projektfortschritt konsolidiert
- Ergebnisse zusammengefasst
- Limitationen und offene Punkte dokumentiert
- Präsentation vorbereitet
- Projektabschluss geplant

## Hinweise
Dieses Projekt stellt einen konzeptionellen und technischen Prototyp dar.
Eine vollständige Automatisierung der KI-Integration in Moodle ist geplant,
aber derzeit noch nicht umgesetzt.
