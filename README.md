# <a name="Inhaltsverzeichnis"></a> Stundenblog von Tabea und Juliane

## Informatikprojekt 3


[Erste Stunde](#eins)

[Zweite Stunde](#zwei)

[Dritte Stunde](#drei)

[Vierte Stunde](#vier)

[Fünfte Stunde](#fünf)

[Sechste Stunde](#sechs)

[Siebte Stunde](#sieben)

[Achte Stunde](#acht)

[Neunte Stunde](#neun)


Das sind die veröffentlichten Snap Projekte:


# Vorstellung der 3D Effekte:
https://snap.berkeley.edu/snapsource/snap.html#present:Username=juliane000&ProjectName=Vorstellung%20der%203D%20Effekte

# Pyramiden-Effekt: 
https://snap.berkeley.edu/snapsource/snap.html#present:Username=juliane000&ProjectName=3D%20Pyramiden-Effekt

# Haus-Effekt: 
https://snap.berkeley.edu/snapsource/snap.html#present:Username=juliane000&ProjectName=3D%20Haus-Effekt





### <a name="neun"></a>Neunte Informatikstunde am 23.3. 2
Häuser bauen (schiefes dach -> Mittelpunkt) versch. Formen und Größen
Sortieren unseres Snap Programms

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="acht"></a>Achte Informatikstunde am 9.3. 2
-schreiben im Stundenblog
_herausfinden, dass es eine kursive Schrift gibt, jedoch nur im raw modus
- Lehrerranking

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sieben"></a>Siebte Informatikstunde am 8.3. 1
- Falsche Umsetzung des vorherigen Projektes
-> Besprechen der Konsequenzen für betroffene Gruppen  
- Pyramideneffekt
- andere unsichtbar, dann auf einen Sprite vereint

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="sechs"></a>Sechste Informatikstunde am 2.3. 2
- stamp 3 D mit verschiedenen geometrischen Formen
- Zeichenversuche
- Schießen
- Mausfokus
- Versuch Bewegung auf y-Achse
- Plan Hausbau

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="fünf"></a>Fünfte Informatikstunde am 1.3. 1


- size Block
- Versuch Bewegung auf y achse
- stamp 3 D

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)

### <a name="vier"></a>Vierte Informatikstunde am 23.2.2018 2

Zu Beginn dieser Doppelstunde setzten wir zunächst den Block aus den vorbereiteten Bausteinen zusammen und uns fiel auf, dass Snap! keinen lila Baustein: "define: process vertex" vorliegen hatte. Zahlreiche Versuche den anfangsbaustein durch verschiedene Mittel nachzubauen, scheiterten leider. Unter anderem versuchten wir den Baustein im ganzen mittels "make a block" eigenständig zu erstellen, aber auch den eingesetzten Baustein zu errichten. Doch da kein leerer Startbaustein zu finden war und auch Herr Buhl uns nicht weiterhelfen konnte, entschieden wir uns schließlich für die Ausführung mit dem gewöhnlich Startbaustein, welcher an die Fahne gekoppelt ist. 

Der nicht aufzufindende Startbaustein:
![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/define%20process%20vertex.png?raw=true "Variablen")

Unser abgeschlossener Block zum Erschaffen eines 3D-Effektes:

![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/23.2..png?raw=true "Variablen")

Als wir uns nun freuten, nach der aufwendigen "Bastelarbeit" endlich fertig zu sein, brach der Ablauf des Blockes immer ab. Dies wird durch ein rotes Aufleuchten angezeigt. Unser Baustein behinderte sich folglich selbst, da Bestandteile dem Rest widersprachen und somit die Ausführung gestoppt wird. Somit befassten wir uns den Rest der Stunden mit der Fehleranalyse und wurden schließlich auch fündig. Dafür nahmen wir zunächst den Block auseinander und testeten seine einzelnen Bestandteile. Dabei viel auf, dass die selbstkreierten Bausteine fehlerhaft sein mussten. Wir kontollierten sie und sahen, dass wir beim Zusammenführen von Bausteingruppen zu einelnen Bausteinen den abschließenden "report" - Bausteinen vergessen hatten. 

So versuchten wir noch schnell alle betroffenen Bausteine mit dem "report"-Glied abzuschließen. In der letzten Minuten schlossen wir damit ab, sodass wir zwar sehen konnten, dass der Block nicht mehr rotauflechtet, doch einen Test, der seine Funktion bestätigen würde, konnten wir nicht mehr durchführen.


[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="drei"></a>Dritte Informatikstunde am 22.2.2018 

Am heutigen Donnerstag besprachen wir das weitere Vorgehen. Wir sahen, dass in der Scratch Seite drei gute Ideen für dreidimensionale Effekte vorlagen. Die Umsetzung der ersten Variante, die Juliane bereits in der letzten Stunde angefangen hatte, setzten wir für unser Projekt, nach gemeinsamen Besprechen der bereits vorliegenden Blockbestandteile, gemeinsam fort. 
 
Grundlage für das überschreiben von zweidimensionalen zu "dreidimensionalen" Werten im zweidimensionalen Programm Snap! beruht auf den Trigeomentischen Regeln, welche die Beziehungen von Sinus, Cosinus, und Tangens, also Winkeln und Längen von Geraden zueinander, beschreiben:

sin(A1 + A2) = sin(A1) * cos(A2) + sin(A2) * cos(A1)
cos(A1 + A2) = cos(A1) * cos(A2) - sin(A1) * sin(A2)
sin(A1 - A2) = sin(A1) * cos(A2) - sin(A2) * cos(A1)
cos(A1 - A2) = cos(A1) * cos(A2) + sin(A1) * sin(A2)

Dadurch ist es möglich durch festgelegte Zusammenhänge die zwidimensionalen Werte so zu steuern, dass ein dreidimensionales Bild erscheint. Die Nutzung von "new x/y/z" verursacht eine Umrechnung von drei Koordinatenwerten zu der Projektion von den zweidimensionalen "old x/y" auf der stage. 

Mithilfe der Anleitung schlossen wir den Bau der Teilblöcke des Gesamtblockes beinahe ab. Morgen ist die Nutzung unseres programmierten Programms das Tagesziel.  



[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="zwei"></a>Zweite Informatikstunde am 16.2.2018

Da heute leider Tabea fehlte, musste ich alleine weiter schauen, wie wir unser Ziel für dieses Projekt umsetzen könnten. Dafür schaute ich  außerhalb von Youtube nach Anleitungen und Hilfestellungen für das Programmieren mit 3D Effekten. 

Neben der offiziellen Seite von Scratch (Vorgänger von snap), welche eine Erläuterung für  <a href="https://scratch-dach.info/wiki/3D in Scratch">3D in Scratch</a> anbietet und bei der öffentliche, abgeschlossene Projekte verlinkt sind, wie dieses <a href="https://scratch.mit.edu/projects/47766/#editor">Beispiel</a>, schaute ich mir auch die englischsprachige Version an, welche verständlicher und weniger theoritisch, als die deutsche version ist, an. Für "<a href="https://wiki.scratch.mit.edu/wiki/How_to_Make_a_Three-Dimensional_Project">How to Make a Three-Dimensional Project</a>" entschied ich mich schließlich .

Somit begann ich im Anschluss mit dem Erstellen der geforderten Variablen und fügte sie so zu den fertigen Bausteinen hinzu. Einige sind in diesem Screenshot abgebildet:

![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/Variablen.png?raw=true "Variablen")


Dieselben nutzte ich im Anschluss, um die kurzen Untereinheiten für Transformation (scale, translation und rotation (roll pitch, yaw)) und Projektion zu erstellen und somit eine Überschreibung von den zweidimensionalen daten zu dreidimensionalen Daten zu ermöglichen. Außerdem vereinte ich funktionelle Bauseingruppen über die Funktion "make a block" zu Bausteinen, damit deren Nutzung im Gesamtblock, beim Einfügen in freie Felder der "Operators" möglich wird.

Vorgaben und Erläuterungen der Scratch-Seite (verlinkt über diesen Screenshot):

<a href="https://en.scratch-wiki.info/wiki/How_to_Make_a_Three-Dimensional_Project">![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/Transformation.png?raw=true "Scratch")</a>

Eigene Umsetzung auf Snap:

![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/16.2..png?raw=true "Variablen")


Zuletzt ließ ich für die kommende Stunde meine Ergebnisse zunächst gespeichert und sortiert liegen. Für die nächste Stunde nehme ich mir vor, mit Tabea gemeinsam die genaueren Zusammenhänge zwischen den Bausteinen, Blöcken und deren Funktionen zu erschließen und die letzten Glieder des Gesamtblockes zu programmieren.
 

[→Inhaltsverzeichnis](#Inhaltsverzeichnis)


### <a name="eins"></a>Erste Informatikstunde am 15.2.2018

Heute war es an der Reihe, sich zu entscheiden, welchem Themengebiet der Informatik wir uns in der nächsten Zeit widmen wollen. Da nun das dritte und letzte Projekt ansteht und wir uns in diesem komplizierteren Aufgaben zuwenden sollten, beschlossen wir ein weiteres Mal uns Anregungen auf Youtube zu suchen.

Dabei stießen wir auf verschiedene Spiele, die vielschichtiger sind als die, die wir in dem vorhergegangenen Projekt bearbeitet haben. Zu diesen zählten unter andem ein Irrwald, ein Basketball und ein Jump´n run Spiel, und diese auch auf verschiedenen Level-Ebenen. Wir entschlossen uns letztendlich für das Programmieren von dreidimensionalen Formen mithilfe des Programmes "<a href="http://snap.berkeley.edu/snapsource/snap.html">Snap</a>". Die Idee entstammte <a href="https://www.youtube.com/watch?v=bTn4S9WyVUc
">diesem</a> Video. Beispiele dafür sind zwar nicht so reichlich, doch einfache Figuren wie Würfel, Häuser und Pyramiden würden wir notfalls versuchen selbt zu erarbeiten.

Zuletzt besprachen wir mit Herrn Buhl, ob der Anspruch dieses Zieles angemessen für die abschließende Ersatzleistung sei. Da er uns dies 
zutraute und dem Projekt seinen Zuspruch gab, nahmen wir uns für die nächsten Stunden die Arbeit an dreidimensionalen Effekten vor.

![bsp applab](https://raw.githubusercontent.com/Tabea000/3.Informatikprojekt-Stundenblog/master/Bildverzeichnis/Beispiel.png?raw=true "Transformation")


[→Inhaltsverzeichnis](#Inhaltsverzeichnis)
