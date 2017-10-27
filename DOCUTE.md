# docute: Dokumentationstool

## Über docute
**Dokumentationstool**

## Installation
**Mittels Paketmanager npm (Node.js Package Manager)**

Mit dem Paketmanager npm kann docute schnell installiert werden.<br />
Dazu den Befehl `npm i -g docute-cli` in die Kommandozeile des Betriebssystems eingeben. 


## Schnellstart

Zuerst muss ein Ordnername gewählt werden, z. B. "./docs".
Mit dem Befehl `docute init ./docs` in der Kommandozeile kann docute initialisiert werden und es werden automatisch drei Dateien erstellt.
- README.md: Beinhaltet den Content
- index.html: Beinhaltet Scripte und Stile
- .nojekyll: Indikator, benötigt für github pages

## Ansicht des Inhalts:

Mit dem Befehl `docute ./docs` wird der docute-Webserver gestartet und man kann sich den Inhalt ansehen, nachdem man ihn bearbeitet hat.
Zur Ansicht im Browser: http://localhost:8080
