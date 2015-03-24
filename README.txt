+++++++++++++++++++++++++
+ Software fuer Windows +
+++++++++++++++++++++++++

http://latex.tugraz.at/programme/windows
-> MikTeX (http://www.miktex.org)
-> PostScript (http://pages.cs.wisc.edu/~ghost/)
-> Editor: TeXnicCenter


+++++++++++++++++++++++++
+ Struktur              +
+++++++++++++++++++++++++

----bilder/	-> Verzeichnis, indem die Bilder liegen, die mit \includegraphics eingebunden werden koennen
  |
  --extras/	-> Verzeichnis, indem verschiedene Sonderdateien, wie Titelblatt oder Definitionsheader liegen
  |
  --kapitel/	-> Verzeichnis, indem nun der eigentliche Inhalt steht - ausbaubar :-)
  |
  --literatur/	-> Verzeichnis, indem Literaturdateien im BibTeX Format liegen
  |
  --diplom.tex	-> Die Hauptdatei



extras/header.tex enthaelt saemtliche Formatierungen enthalten, diese koennen dort nach Belieben veraendert werden.

extras/titelseite.tex beschreibt die Titelseite. Auch hier sind Variablen, die mit individuellen Eintraegen versehen werden muessen.

diplom.tex fasst alle einzelnen Dateinen zusammen und bildet das Hauptdokument
-> pdfTeX
