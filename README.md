# Prozessflow Geschäftsgeheimnisschutz – Hinweise zur Pflege

## Dateien

- `index.html` – Gerüst, Gestaltung und Logik der Grafik. Hier steht kein Inhalt.
- `daten.js` – sämtliche Inhalte. Der Kommentar am Dateianfang erklärt die Felder.
- `Ablauf_Geschaeftsgeheimnisschutz.html` – beide Dateien in einer einzigen Datei zusammengefasst, zum Weitergeben und Öffnen ohne Entpacken.

Zum Bearbeiten `index.html` und `daten.js` im selben Ordner belassen und `index.html` im Browser öffnen.

## Inhalte ändern

Alle Änderungen finden in `daten.js` statt. An `index.html` muss nichts angefasst werden.

- `SCHRITTE` – die Kästen der Grafik. Ein neuer Block ergibt einen neuen Schritt.
- `VERBINDUNGEN` – die Pfeile zwischen den Schritten, über `von` und `nach` mit den IDs aus `SCHRITTE`.
- `DISCLAIMER` – der Hinweis unter der Überschrift.
- `GRUNDLAGEN` – die Absätze zu Rechtsgrundlagen und Einordnung im Vorspann.

Die Position eines Schritts im Raster ergibt sich aus `spalte` und `zeile`, das Aussehen aus `typ`. Wird ein Schritt verschoben oder gelöscht, müssen die zugehörigen Einträge in `VERBINDUNGEN` mitgezogen werden, sonst zeigt ein Pfeil ins Leere.

## Veröffentlichung über GitHub Pages

Für GitHub Pages muss die Datei im Repository `index.html` heißen, sonst ist die Seite nicht unter der kurzen Adresse erreichbar. Entweder lädt man `index.html` und `daten.js` gemeinsam hoch, oder man benennt die Einzeldatei in `index.html` um und lädt nur diese hoch.

## Nach dem Bearbeiten

`Ablauf_Geschaeftsgeheimnisschutz.html` wird aus `index.html` und `daten.js` erzeugt und aktualisiert sich nicht von selbst. Wenn die Einzeldatei weitergegeben oder hochgeladen werden soll, muss sie nach einer Änderung neu erstellt werden.

## Rechtsstand

Rechtsstand 7. November 2026. Der Digital Omnibus ist nicht eingearbeitet. Die Normenzeilen in Schritt 4 und 6a wurden am 25. November 2026 auf die geklärte Absatzzählung umgestellt, also Art. 4 Abs. 6 DA mit der Parallelregelung in Art. 5 Abs. 9 DA und Art. 4 Abs. 6, 7 DA mit Art. 5 Abs. 9, 10 DA.
