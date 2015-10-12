Zettelkasten - nach Luhmann - für Windows, Mac OS X und Linux
------------------------------------------------------------------------------
Der elektronische Zettelkasten ist ein Programm, das sich am Arbeitsprinzip des Zettelkastens von Niklas Luhmann orientiert. Die offizielle Homepage zum Programm ist [http://zettelkasten.danielluedecke.de](http://zettelkasten.danielluedecke.de).

### Download
Die aktuellste Programmversion [kann hier heruntergeladen](http://zettelkasten.danielluedecke.de/download.php) werden.

### Dokumentation und Anleitungen
Ausführliche Anleitungen zu den verschiedenen Funktionen gibt es [in der Wiki](http://zettelkasten.danielluedecke.de/wiki/doku.php). Fragen und Anregungen zum Zettelkasten können in der [Mailingliste](https://de.groups.yahoo.com/neo/groups/zettelkasten/info) gestellt werden.

### Changelog der aktuellen Entwicklerversion

#### Neue Funktionen und Änderungen
* Der Export von Zetteln ins Markdown-, Text- und LaTex-Format kann jetzt auch jeden Zettel als einzelne Datei exportieren ([#13](https://github.com/sjPlot/Zettelkasten/issues/13) und [#77](https://github.com/sjPlot/Zettelkasten/issues/77)).
* Beim Export ins Markdown-, Text- und LaTex-Format werden Fußnoten durch formatierte Autorenangaben ersetzt (sofern die Literatur mit Bibkey verknüpft ist).
* Im englischen Interface wurden _trails_ in _note sequences_ und _entry_ in _note_ umbenannt.
* Literaturfußnoten können jetzt auch den Bibkey statt der Nummer des Literatureintrags enthalten (`[fn luhsozsys:123]` würde z.B. umgewandelt in `Luhmann 1984: 123`).
* Das automatische Einklammern von Literaturfußnoten kann in den Einstellungen abgestellt werden ([#91](https://github.com/sjPlot/Zettelkasten/issues/91)).
* Literatur, die während der Neueingabe oder Bearbeiten eines Zettels als Literaturfußnote im Text referenziert wird, wird beim Beenden der Eingabe automatisch als Autorenangabe zum Zettel hinzugefügt, falls dies noch nicht geschehen ist.
* Verbesserte Stabilität aller Lese- und Schreib-Operationen von Daten (Import, Export, Laden, Speichern, Auto-Backup...).
* Geschwindigkeitsverbesserungen der Suchfunktionen ([#95](https://github.com/sjPlot/Zettelkasten/issues/95)).
* Neue Einstellung, um Formatierungs-Tags bei einer Suche _nicht_ zu entfernen. Dadurch wird die Suchgeschwindigkeit erhöht, jedoch werden Wörter, die durch Formatierungen unterbrochen werden, nicht gefunden (eine Suche nach `Zettelkasten` findet dann nicht `[f]Zettel[/f]kasten`).

#### Behobene Fehler
* Bei Dateien, die im Neueingabefenster per Drag'n'Drop ins Textfeld gezogen wurden, kam keine Abfrage zum Verschieben oder Kopieren der Dateien.
* Änderung [#82](https://github.com/sjPlot/Zettelkasten/issues/82) wurde rückgängig gemacht, da es Probleme mit URLs in BibTex-Autorenangaben gab.
* In der Registerkarte _Literatur_ wurden _Buchkapitel_ und _Artikel in Büchern_ bei der Filterfunktion vertauscht ([#90](https://github.com/sjPlot/Zettelkasten/issues/90)).
* Dateinamen mit Unterstrichen kollidierten mit Markdowninterpretation ([#26](https://github.com/sjPlot/Zettelkasten/issues/26)).
* Schreibtischexport ins Markdown deklarierte keine Überschriften ([#56](https://github.com/sjPlot/Zettelkasten/issues/56)).
* Im Exportfenster konnten beim Export ins Textformat keine Zettelelemente ausgewählt werden.
* Bei Fußnoten ohne Bibkey wurde die Seitenzahl nicht angezeigt ([#74](https://github.com/sjPlot/Zettelkasten/issues/74)).

### Screenshots
Aktuelle Screenshots [gibt es hier](http://zettelkasten.danielluedecke.de/gallery.php).
