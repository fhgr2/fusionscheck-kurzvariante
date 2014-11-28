gemeinde-benchmarking
=====================

Tool für das ZVM (Ursin Fetz)

Anforderungen
=============

Fachlich
========
Grundsätzlich soll ein Tool analog zu http://www.htwchur.ch/management/institut-sife/team-themen-und-taetigkeiten/tool-exportfitness-check.html geschaffen werden. Anstatt um Export-Fitness ist das Thema Gemeinde Benchmarking im Kontext von Gemeindefusionen.

Es werden 10 Fragen gestellt. 
Beispiel für eine Frage: Wie viele Einwohner hat ihre Gemeinde?
Die effektiven Fragen wird Curdin Derungs noch liefern.

Diskussion mit Curdin Derungs vom 28.11.2014:
- Welche Typen von Fragen kommen vor? Ja/Nein-Fragen, Fragen mit einer Auswahl, Fragen nach einer Anzahl, usw.?
- 
Es handelt sich vorwiegend um Zahlen, als z.B. "Wie viele Einwohner hat die Gemeinde". 
- Müssen alle 10 Fragen beantwortet werden? Wenn nein, welche Auswirkungen hat dies auf das Spider-Diagramm.
- 
Folgende Variante wäre zu bevorzugen:
- Das Spiderdiagramm wird fortlaufend ergänzt. Sobald eine Frage beantwortet wird, wird ein Stützpunkt eingezeichnet. Sobald zwei Stützpunkte nebeneinander vorhanden sind, wird eine Linie gezogen. (Die Fragen werden in derselben Reihenfolge gestellt, wie Sie im Diagramm dargestellt werden.) 
- Viele Spider-Diagramme haben 8 Achsen. Da würden sich 8 bzw. 16 Fragen anbieten.

Entscheid: 10 Achsen.
- Was soll die Aussage des Diagramms sein? Evtl. gäbe es Alternativen zum Spider-Diagramm.

Entscheid: momentan soll ein Spider-Diagramm genutzt werden.
- Soll zusätzlicher Aufwand für die Unterstützung von veralteten Browsern getrieben werden? (Siehe z.B. https://www.browser-statistik.de/ und https://www.browser-statistik.de/statistiken/versionen/ )

Nein. Einigermassen aktuelle Browser sollen unterstützt werden, sicherlich aber nicht IE 6.

- Soll zusätzlicher Aufwand für die Optimierung auf mobile Geräte getrieben werden?
Definitiv nein.

Die Antworten werden dann auf eine Skala von 0 bis 100 (oder ähnlich abgebildet) um Sie danach in einem Spiderdiagramm einer Mustergemeinde (die Daten kommen von Curdin Derungs) gegenübergestellt zu werden.

Optionale Anforderungen (mit Curdin Derungs zu klären)

- Muss sich das Spiderdiagramm speichern lassen? In welchem Format?

Eine Speicherung auf einem Server ist nicht notwendig. Die Generierung eines Links, der dann weitergeschickt werden kann, wäre gemäss Curdin Derungs wünschenswert.

Technisch
=========
JavaScript-basiertes Tool, welches sich ins Typo3 einbinden lässt, analog zur Übersicht der Fachzeitschriften auf http://www.htwchur.ch/services/fuer-alle/bibliothek/abonnierte-fachzeitschriften.html.

Administrativ
=============
- Aufwand: 40 h
- Projekt: 11437 ZVM-12-Fusionscheck (falls die 40 h aufgebruacht sind, bei mir melden, resp. auf 11113 IKT-10-Kleinprojekte aF+E buchen).
