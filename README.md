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

## 01.03.2024

### C_NETZWERKADRESSIERUNG_ANNEX

#### 1. Beantworten sie folgende Fragen zum Thema Hostnamen:

##### a. Gibt es Einschränkungen beim Hostnamen wie z.B. max. Anzahl Zeichen, Sonderzeichen, Gross-Kleinschreibung etc.

- Der Hostname darf bis zu 63 Zeichen lang sein.
- Erlaubt sind Buchstaben (a-z, A-Z), Ziffern (0-9) und der Bindestrich (-). Der Bindestrich darf jedoch nicht am Anfang oder Ende des Hostnamens stehen.
- Leerzeichen und Sonderzeichen außer dem Bindestrich sind nicht erlaubt.
- Hostnamen sind normalerweise nicht casesensitive, das bedeutet, "NoteBook" und "notebook" werden als identisch betrachtet.

##### b. Wo kann man bei Microsoft WINDOWS 10/11 den Hostnamen eintragen?

#### 2. Beantworten sie folgende Fragen zum Thema MAC-Adresse:

#### 3. Beantworten sie folgende Fragen zum Thema IP-Adresse:

#### 4. Erklären sie in ein paar Worten, was Subnetting für Vorteile hat

- Subnetting ermöglicht die Aufteilung eines großen IP-Adressraums in kleinere Teile, was eine effizientere Nutzung der verfügbaren IP-Adressen ermöglicht.
- Durch Subnetting können Netzwerke in isolierte Segmente unterteilt werden. Dies ermöglicht die Implementierung von Sicherheitsrichtlinien und den Schutz sensibler Daten.
- Subnetting erleichtert die Organisation und Verwaltung von Netzwerken.
- Durch die Begrenzung der Broadcast-Domänen auf einzelne Subnetze wird der Broadcast-Verkehr in einem Netzwerk minimiert.
- Subnetting bietet eine skalierbare Lösung, da es ermöglicht, Netzwerke an veränderte Anforderungen anzupassen, ohne dabei die gesamte IP-Adressstruktur neu gestalten zu müssen.

#### 5. In den folgenden Fallbeispielen (Fall-1 bis Fall-3) sind die Bilder nicht ganz komplett. Entweder fehlt das Dezimaläquivalent oder die binäre Darstellung. Ergänzen sie bitte:

##### Fall 1

10.35.3.112
   
00001010.00100011.00000011.01110000

255.0.0.0
   
11111111.00000000.00000000.00000000

10.35

3.112

2^24 = 

16'777'216 -2 = 16'777'214

10.0.0.0

10.255.255.255

#### 6. Wo kann man bei Microsoft Windows 10/11 den Standardgateway (DefaultRouter) eintragen?

In Microsoft Windows 10 und Windows 11 wird der Standardgateway (Default Router) normalerweise über die Netzwerkeinstellungen konfiguriert.

#### 7. Wichtige IPv4-Adressen:

a. Wie lauten die drei für LANs reservierte IP-Adressbereiche?

1. Der erste Bereich umfasst alle IP-Adressen von 10.0.0.0 bis 10.255.255.255 - für grössere Netzwerke
2. Der zweite Bereich umfasst alle IP-Adressen von 172.16.0.0 bis 172.31.255.255 für mittelgrosse Netzwerke
3. Der dritte bereich umfasst alle IP-Adressen von 192.168.0.0 bis 192.168.255.255 für kleinere Netzwerke

b. Wie lautet die Loopbackadresse (Localhost) und was bezweckt sie?

Die localhost Adresse lautet 127.0.0.1 und wird verwendet, um Netzwerkkommunikation mit dem eigenen Gerät zu simulieren, ohne dass die Daten das physische Netzwerk verlassen.

c. Unter welchen Voraussetzungen werden sie eine APIPA-Adresse (Zero-Conf) erhalten? In welchem Bereich liegt diese?

