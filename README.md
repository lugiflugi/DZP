# Datenzentriertes Programmieren FS26

Link zum [Moodle-Kurs DZP](https://moodle.zhaw.ch/course/view.php?id=28526)

## Ziele, Themen und Lernzyklus

- [Modulguide](https://moodle.zhaw.ch/mod/resource/view.php?id=1937571): Übergeordnete Lernziele und Übersicht der Inhalte
- [Semesterplan](https://moodle.zhaw.ch/mod/resource/view.php?id=1937572): Themen pro Semesterwoche
- [Lernzyklus](https://moodle.zhaw.ch/mod/resource/view.php?id=1937573): Ablauf der Lernaktivitäten pro Woche
  1. Einstieg und Vertiefung neues Thema (bis Mi)
  2. Start mit Übungsblatt (bis Mi)
  3. Abschluss Übungsblatt / Festigen des Themas im Plenum (Lektion Mi)
  4. Übungsblatt abschliessen (bis Mi)

## Arbeitsumgebung

### Programme

Wir arbeiten mit [Python Version 3.14.x](https://www.python.org/downloads/). Ältere Versionen sollten auch funktionieren. Pre-Release Versionen (z.B. 3.15) sind nicht empfohlen, da es zu Inkompatibilitäten mit den Packages kommen kann.

Weiter empfiehlt sich

- [Visual Studio Code](https://code.visualstudio.com/)
- [GitHub Desktop](https://desktop.github.com/)

### Arbeitsverzeichnis

Erstelle als Arbeitsumgebung für die beiden Module _Datenzentriertes Programmieren_ und _Numerische Grundlagen der Data Science_ ein Verzeichnis, z.B. namens `NGDS-DZP`, also so etwas

| Betriebssystem | Pfad                     |
| -------------- | ------------------------ |
| Windows        | `C:\Daten\ADLS\NGDS-DZP` |
| Mac            | `~/Daten/ADLS/NGDS-DZP`  |

Wir setzen alles so auf, dass dieses Verzeichnis später problemlos umbenannt oder verschoben werden kann.

### GitHub Repository klonen

Klone das [DZP GitHub Repository](`https://github.zhaw.ch/ADLS-Data-Science-and-Computation/Datenzentriertes-Programmieren-FS26.git`) in dem Arbeitsverzeichnis. Am einfachsten nutzt du dazu [GitHub Desktop](https://desktop.github.com/).

Alternativ kannst du das Arbeitsverzeichnis in Visual Studio Code öffnen, dort einen Terminal starten (_Terminal > New Terminal_) und den folgenden Befehl im Terminal eingeben:

```
git clone https://github.zhaw.ch/ADLS-Data-Science-and-Computation/Datenzentriertes-Programmieren-FS26.git
```

Nun gibt es ein neues Unterverzeichnis namens

| Betriebssystem | Pfad                                                         |
| -------------- | ------------------------------------------------------------ |
| Windows        | `C:\Daten\ADLS\NGDS-DZP\Datenzentriertes-Programmieren-FS26` |
| Mac            | `~/Daten/ADLS/NGDS-DZP/Datenzentriertes-Programmieren-FS26`  |

in dem die aktuelle Version des Repositories geklont ist. Dieses kannst du mit _GitHub Desktop_ oder dem Befehl `git pull` im Terminal immer aktualisieren, wenn wir neue Inhalte pushen.

### Verzeichnis für eigene Arbeit

Für die eigene Arbeit (Einarbeitung und Übungsaufgaben) brauchst Du ein weiteres Unterverzeichnis. Du kannst entweder gleich eines erstellen, z.B. `DZP`, also

| Betriebssystem | Pfad                         |
| -------------- | ---------------------------- |
| Windows        | `C:\Daten\ADLS\NGDS-DZP\DZP` |
| Mac            | `~/Daten/ADLS/NGDS-DZP/DZP`  |

Oder besser: Du erstellst ein eigenes Repository auf GitHub oder ZHAW GitHub Enterprise und klonst dieses auch ins `NGDS-DZP` Arbeitsverzeichnis. So kannst Du z.B. Woche für Woche Deine Arbeit committen und pushen, um Dir diese Praxis anzueignen und gleich auch ein Backup zu haben.

### Python Virtual Environment

Wir setzen ein Virtual Environment definiert durch die Datei `requirements.txt` auf. So haben alle die gleichen Packages installiert. Das Environment soll sich im übergeordneten Arbeitsverzeichnis, so dass es für NGDS und DZP benutzt werden kann.
Wir führen folgende Schritte im Terminal im Arbeitsverzeichnis aus. (Arbeitsverzeichnis in VS Code öffnen und dort einen neuen Terminal öffnen.)

| Schritt                                        | Windows                                                               | Mac                                                                   |
| ---------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------- |
| 1. Virtual Environment namens `.venv` erzeugen | `python -m venv .venv`                                                | `python3 -m venv .venv`                                               |
| 2. Environment aktivieren                      | `.venv\scripts\activate`                                              | `source .venv/bin/activate`                                           |
| 3. Pip aktualisieren                           | `python -m pip install -U pip`                                        | `python3 -m pip install -U pip`                                       |
| 4. Packages installieren                       | `pip install -r Datenzentriertes-Programmieren-FS26\requirements.txt` | `pip install -r Datenzentriertes-Programmieren-FS26/requirements.txt` |

## Arbeit am Projekt und Abgabe

- Projektauftrag: Projektarbeit in Gruppen
  1. Gruppenbildung bis 1. April 2026 (Mi, 15:00 Uhr)
  2. Offizieller Projektstart am 8. April 2026 (Mi, 15:00 Uhr)
  3. Ausformulierte Aufgabenstellung bis 22. April 2026 (Mi, 15:00 Uhr)
  4. Projektabgabe (inkl. Präsentation) bis 19. Mai 2026 (Di, 23:30 Uhr)
  5. Präsentationen 20./22./27. Mai 2026 (Mi/Fr/Mi)
  6. Peer-Reviews bis 27. Mai 2026 (Mi, 23:30 Uhr)

- Weitere Informationen dazu findest Du im auf GitHub unter folgendem Link: [Gruppenarbeit Auftrag](https://github.zhaw.ch/ADLS-Data-Science-and-Computation/Datenzentriertes-Programmieren-FS26/blob/main/00_Gruppenarbeit/Gruppenarbeit_Auftrag.ipynb).

## Lizenz

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
Dieses Werk ist lizenziert unter einer [Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](http://creativecommons.org/licenses/by-sa/4.0/).
