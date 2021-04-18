# IT mit Schmiss – QuicksortDemo

Das Programm lässt unterschiedliche Varianten von Quicksort laufen, 
illustriert ihre Verfahrensweise mit einer Wertetabelle, führt 
Stresstests mit Zufalls-Arrays durch und vergleicht sie 
miteinander in einem Benchmark. 

Eigene Variationen des Algorithmus könnt Ihr einfach hinzufügen, 
indem Ihr eine Datei in `src/sorters` kopiert und ihr einen eigenen
Namen gebt, z.B. `MeinSort.java`. Den Quelltext solltet Ihr auch in 
`resources/MeinSort.txt` kopieren, damit die GUI ihn findet und anzeigen kann. 

Nach dem Build findet die GUI das zusätzliche Verfahren und zeigt es in der Liste an. 
Leider habe ich noch keinen Schutz gegen Endlosschleifen einbauen können.

Das Projekt habe ich in IntelliJ programmiert. Ihr könnt es damit auch selbst bauen 
und laufen lassen. Es gibt zusätzlich zur GUI auch eine Konsolen-Version in 
`main/MainConsole`, die Ihr auch direkt laufen lassen könnt.

## Download und Installation

Auf der rechten Seite seht Ihr die "Releases". Klickt das neuste davon an und ladet
die passende JAR-Datei herunter. Wenn Ihr eine Java-Runtime oder ein JDK installiert 
habt, solltet Ihr die JAR-Datei mit Doppelklick starten können.

Wenn Ihr bereits BlueJ, IntelliJ oder Visual Studio Code mit Java-Paket besitzt, 
sollte das der Fall sein.

Ansonsten müsst Ihr z.B. auf [AdoptOpenJDK](https://adoptopenjdk.net/) eins 
herunterladen und installieren. Ich empfehle ein JDK der Version 11 mit HotSpot-JVM. 
Eventuell müsst Ihr Euch nach der Installtion des JDK einmal ab- und wieder anmelden.
