# Wir bauen eine Bibliothek mit JSON

Wir verwenden die "JavaScript Object Notation" (JSON), um eine Bibliothek dynamisch zu generieren. Die Bücher werden via eier JSON-Datei eingelesen und dann automatisch angezeigt. Wir nutzen sogenannte 'templates', um die Darstellung aller Bücher zu standardisieren.

1. Kopieren Sie den Code via github (Ctrl-Shift-P dann Git:Clone) in ihren Arbeitsordner.

2. Fügen Sie der JSON-Datei ein neues Buch hinzu. Achten Sie darauf, die korrekte Syntax (geschweifte Klammern, Kommas etc.) zu verwenden.

3. Wir geben jedem `div`, das ein Buch umfasst eine eigene Klasse `book`. Wir werden diese wie folgt darstellen: 
    - Wir setzen ```padding``` überall auf 10px.
    - `margin` wird auf 2px gesetzt.
    - Die Breite des Eintrags wird auf 30% der Ansicht (view-width) gesetzt.
    - Die minimale Breite wird auf `max-content` gesetzt.
    - Wir geben dem Eintrag einen Schatten (`box-shadow`)
    - Wir fügen CSS Code ein so, dass der Schatten dunkler wird, wenn wir mit der Maus über den Eintrag fahren.

3. Jahrgänge sollen mit der 'Courier' monospace Schriftart dargestellt werden.

4. Wir fügen in der Funktion `generateBookList` eine Bedingung ein: Falls ein Buch einen älteren Jahrgang als 1945 hat, soll die Jahreszahl in roter Schrift geschrieben werden.