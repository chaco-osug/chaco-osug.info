---
title: 'Gescannte Dokumente in lesbares PDF umwandeln'
---

### Voraussetzungen
* Computer mit Linux-Betriebssystem
* Installierte Anwendungen mit den dazugehörigen Abhängigkeiten
	* img2pdf
	* ocrmypdf
* Ordner mit gescannten Dokumenten im JPG-Format (im Beispiel: `/gescannte/Dokumente/`)

### Ablauf
In der Konsole werden folgende Kommandos eingegeben:

`cd /gescannte/Dokumente/`

`img2pdf *.jp* --output scan_combined.pdf`

[:fa-coffee:]

`ocrmypdf -l spa+deu scan_combined.pdf scan_combined_OCR.pdf`
[:fa-coffee:] [:fa-clock-o:]

