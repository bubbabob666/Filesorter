# Filesorter

Ein einfaches Python-Skript, dass automatisch Dateien in einem Verzeichnis sortiert. Das Tool scannt einen angegebenen Ordner und verschiebt Dateien basierend auf Dateiendungen in entsprechende Unterordner.

## Weitere Infos
- Sortiert von allein: Erkennt die Dateiendungen (wie .pdf oder .jpg) und packt die Sachen in die passenden Ordner.
- Stürzt nicht ab: Wenn mal was schiefgeht (z. B. eine Datei gerade blockiert ist), fängt das Skript den Fehler ab und läuft trotzdem weiter.
- Leicht anpassbar: Man kann oben im Code ganz einfach selbst neue Dateitypen oder Ordnernamen hinzufügen.

## Installation & Nutzung
1. Python 3 installiert haben.
2. Klone das Repository oder lade die Datei `Filesorter.py` herunter.
3. Führe das Skript über das Terminal aus:
   ```bash
   python file_sorter.py
