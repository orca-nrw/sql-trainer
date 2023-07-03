![EILD-Logo](src/img/eild_header_logo.png)

# SQL-Trainer
Dieser SQL-Trainer ist eine Lernanwendung für verschiedene SQL-Statements in Datenbanken. Ziel dieses SQL-Trainers ist es, dem Nutzer verschiedene Aufgaben zum Entwurf von SQL-Statements zu bieten. Neben über 200 Aufgaben zu SELECT-Befehlen gibt es außerdem knapp 160 DML-Aufgaben, sowie fast 40 DDL-Aufgaben.

Die Aufgaben sind dabei auf die 5 Themenbereiche Busfahrten, Fahrradhersteller, Theather, Reisen und Fußball verteilt. Jeder Themenbereich ist dabei weiter in 3 Schwierigkeitsgrade (Leicht, Mittel und Schwer) aufgeteilt.

Die vom Nutzer geschriebenen Anfragen, werden anschließend direkt im Browser ausgeführt und mit einer Musterlösung verglichen. Hierzu wird im Browser selbst eine kleine SQLite-Datenbank betrieben in der die Aufgaben ausgeführt werden. SQLite versteht den Großteil des SQL-Standards, den auch Oracle oder MySQL verwenden, hat aber gewisse Einschränkungen, beispielsweise bei der Verarbeitung von Date Typen.

Wenn Sie die unterstützten Befehle nachschlagen möchten, stellt SQLite.org eine [entsprechende Übersicht](https://www.sqlite.org/lang.html) bereit.

Schlagworte: Datenbanksysteme, Datenbank, SQL, DQL, DML, DDL

## Weitere Informationen
Der SQL-Trainer wurde im Projekt EILD.nrw weiterentwickelt. In EILD.nrw wird ein Ansatz mit weitgehender Adaptierbarkeit und Wiederverwendbarkeit der Lehrinhalte umgesetzt. Die entwickelten OER werden über ORCA.nrw zur Verfügung gestellt.
- [EILD.nrw]
- [ORCA.nrw]
- [ORCA.nrw Github]

## Verwendung

Es gibt verschiedene Möglichkeiten den Trainer zu benutzen. Am einfachsten ist die Verwendung der auf GitHub bereitgestellten Version [SQL-Trainer GH Pages]. Diese wird bei Änderungen aktualisiert und muss nicht selbst betrieben werden.

Alternativ lässt sich diese Version aus dem `gh-pages`-Branch als .zip-Datei herunterladen und anschließend auf Ilias, Moodle oder ähnliche Plattformen hochladen. Dort muss diese lediglich entpackt werden. Ilias erkennt die `index.html` automatisch als Startpunkt der Anwendung, auf anderen Plattformen muss dies eventuell noch manuell passieren.

Als letzte Alternative kann die Anwendung auch aus dem Sourcecode generiert werden. Das entsprechende Build-Skript aus der Package.json lässt sich mit `npm run build` ausführen. Der generierte Ordner ist dann identisch zu dem, der auch im `gh-pages`-Branch liegt.


## Lizenzierung

[![License: MIT][MIT-shield]][MIT]

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]


Die Anwendung SQL-Trainer wurde ursprünglich von der [Technischen Hochschule Köln][TH Köln] im Rahmen der Online-Lernplattform [EDB] entwickelt und wurde als Teil des Projektes [EILD.nrw] von Alexander Kosmehl weiterentwickelt und als Open-Source Anwendung veröffentlicht.

Dieses Repository enthält Software unter [MIT-Lizenz][MIT] und Content unter [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa]. Content sind insbesondere die Aufgabenstellungen, Definitionen und Hinweise. Ausgenommen von der CC BY-SA 4.0 Lizenz sind die verwendeten Logos sowie alle anders lizenzierten Inhalte.

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

![image](https://user-images.githubusercontent.com/73349129/233968870-b61f0850-e7c2-489f-a597-53e030794b22.png)



[MIT]: https://github.com/orca-nrw/sql-trainer/blob/master/LICENCE
[MIT-shield]: https://img.shields.io/badge/License-MIT-yellow.svg
[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
[HSD]: https://www.hs-duesseldorf.de/
[TH Köln]: https://www.th-koeln.de/
[EDB]: https://edb2.gm.th-koeln.de/index
[NF-Trainer]: https://github.com/orca-nrw/sql-trainer/tree/main
[NF-Trainer GH Pages]: https://orca-nrw.github.io/sql-trainer/
[EILD.nrw]: https://www.eild.nrw/
[EILD.nrw GitHub]: https://github.com/EILD-nrw
[ORCA.nrw]: https://www.orca.nrw/
[ORCA.nrw Github]: https://github.com/orca-nrw
