# Lernjournal-M117 Tim Kunz

## 23.02.24

### B_ETHERNETVERKABELUNG_ANNEX

#### Netzwerktopologien

##### Welche Topologie entspricht dem historischen Yellowcable (Koaxialkabel) und welche der aktuellen Ethernetverkabelung?

- Die Bustopologie entspricht dem Yellowcable.

- Die aktuelle Ethernetverkabelung verwendet in der Regel eine Stern- oder Baum-Topologie.

##### Was unterscheidet die Baumtopologie von der Meshtopologie?

- Baumtopologie ist Hierarchisch, besitzt klare Pfade und ist einfach zu verwalten.

- Meshtopologie ist Vollständig vernetzt, besitzt eine hohe Redundanz, ist teurer und komplexer.

##### Was ist der Nachteile einer Stern- oder Baumstruktur?

- Sterntopologie ist Abhängig vom zentralen Punkt, ein Ausfall dort betrifft das gesamte Netzwerk.

- Die Skalierbarkeit der Sterntopologie ist begrenzt, es treten hohe Kosten für leistungsstarke zentrale Knotenpunkte auf.

- Komplexität steigt mit Hierarchie bei der Baumtopologie.

- Abhängigkeit von Hauptleitungen, Skalierbarkeit kann bei der Baumtopologie herausfordernd sein.

##### Welche Netzwerktopologie treffen sie in aktuellen LANs an?

- In aktuellen LANs ist die Stern-Topologie und die Baumtopologie sehr verbreitet.

#### Kommunikation

##### Was ist der Vorteil der modernen Ethernetverkabelung gegenüber dem historischen Yellow-Cable?

Moderne Ethernetverkabelung bietet gegenüber historischem Yellow-Cable folgende Dinge:

- Höhere Datenübertragungsraten.

- Bessere Rauschunterdrückung.

- Flexibilität und Einfachheit bei der Installation und Verwaltung.

- Verbesserte Skalierbarkeit durch einfachen Anschluss neuer Geräte.

- Effiziente Punkt zu Punkt Kommunikation durch Switchbasierte Netzwerktopologie.

##### Sie möchten zwei PC’s direkt mit einem Ethernetkabel verbinden. Was muss dabei beachtet werden?

Um zwei PCs direkt miteinander zu verbinden:

- Verwenden Sie ein Crossover Ethernetkabel.

- Falls kein Crossover-Kabel vorhanden ist, schliessen Sie die PCs einfach an einen Switch an.

- Stellen Sie manuell statische IP-Adressen für die Netzwerkkarten der PCs ein.

- Überprüfen Sie Firewall-Einstellungen, um den Datenaustausch zu ermöglichen.

#### Regelung der Kommunikation

##### Was bedeutet die Abkürzung CSMA/CD und was regelt sie?

- CSMA/CD steht für Carrier Sense Multiple Access with Collision Detection. Es regelt den Zugriff auf ein gemeinsames Übertragungsmedium in Ethernet-Netzwerken und ermöglicht mehreren Geräten, den Kanal zu teilen. In modernen Netzwerken mit Switches ist diese Methode weniger relevant geworden.

##### Was versteht man unter Kollisionen und warum muss jedes Gerät die Leitung ständig auf solche abhören?

- In einem Netzwerk bezieht sich eine Kollision auf den Konflikt, der entsteht, wenn mehrere Geräte gleichzeitig versuchen, Daten über den gleichen Übertragungskanal zu senden.

- Es ist wichtig, die Leitung auf solche abzuhören, damit die Daten korrekt gesendet und empfangen werden können und für eine effizientere Verbindung zu sorgen.

##### Warum muss bei einem Rückzug infolge Kollisionsentdeckung ein Zufallszeit abgewartet werden, bis ein erneuter Sendeversuch gestartet werden kann?

- Es muss eine Zufallszeit abgewartet werden, um weitere Kollisionen zu vermeiden.

#### Materialwahl für das Übertragungsmedium

##### Worin liegen die Unterschiede von Draht, Litze oder Glas (Vor-, Nachteile)?

- Die Vorteile von Draht sind, dass sie Robust und langlebig sind und eine gute Leitfähigkeit haben.
- Die Nachteile von Draht sind, dass sie weniger flexibel als Litze sind und bei wiederholtem biegen zum Brechen neigen.

- Die Vorteile von Litze sind, dass sie flexibler als Draht sind und besser bei Anwendungen, bei denen Bewegung oder Biegung nötig ist.
- Die Nachteile von Litze sind, dass sie weniger Leitfähig als Draht sind.

- Die Vorteile von Glasfaser sind, dass sie eine hohe Bandbreite für Datenübertragung über große Entfernungen und ein Geringes Gewicht und geringe Dämpfung der Signalqualität haben und Immun gegen elektromagnetische Interferenzen sind.

##### Wo setzt man welches Material ein?

- Draht setzt man vor allem für die Hausverkabelung und in festen Installationen ein.

- Litze ist gut geeignet für Anwendungen mit Bewegung und Biegung.

### Gelerntes

Heute habe ich gelernt, dass man ein Netzwerk mit Ethernet Kabeln und Switches nur dann in einem Loop verbinden soll, wenn man die Switches richtig einstellt und sie auch fähig sind. Ausserdem wusste ich vor heute nicht, dass xDSL-Modems nicht nur einen WLAN-Accesspoint eingebaut haben, sondern auch eine Firewall, eine Switch und einen Router.
