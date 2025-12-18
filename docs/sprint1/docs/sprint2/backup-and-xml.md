# Sprint 2 – Moodle Backup & XML-Analyse

## Ziel
Analyse der Moodle-Backup-Struktur als Grundlage für eine automatisierte Kurserstellung.

## Vorgehen
- Erstellung eines Moodle-Kurs-Backups (.mbz)
- Manuelle Extraktion der Backup-Datei
- Analyse der enthaltenen XML-Dateien

## Zentrale Datei
- moodle_backup.xml

## Erkenntnisse
- Kurse, Abschnitte und Aktivitäten sind vollständig in XML beschrieben
- Quizze und Fragen sind strukturiert abbildbar
- XML eignet sich als Ziel- oder Zwischenformat für LLM-generierte Inhalte

## Einschränkung
Bei der lokalen Moodle-Installation blieb die asynchrone Wiederherstellung in der Warteschlange hängen.  
Die XML-Analyse konnte dennoch erfolgreich durchgeführt werden.
