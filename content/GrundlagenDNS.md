## Domain Name System
Das Internet ist ohne die Technologie des *Domain Name Systems*, im folgenden mit DNS abgekürzt, kaum noch vorstellbar. Über diesen Service ist es möglich für den Menschen einfach lesbare, alphabetische Namen, statt mehrstellige Nummern zu nutzen, um Ressourcen in einem Netzwerk aufzurufen und auf diese zuzugreifen. Diese alphanumerischen Namen werden ebenfalls als *Domain Names* bezeichnet. Das Routing in einem großen Netzwerk wie dem Internet wäre jedoch schwer über solche Namen zu realisieren, stattdessen werden hierzu numerische IP-Adressen verwendet. Um trotzdem die besser nutzbaren alphabetischen Ausdrücke nutzen zu können ist also ein Service zur Übersetzung dieser in IP-Adressen gefordert. Dieses Technologie bezeichnet man als *Domain Name System*.


Das im vorherigen Absatz beschriebene bedeutet, jedes Mal wenn der
Domain Name einer Netzwerkressource, wie eines Webservers, eingegeben
wird, muss diese zunächst in das IP-System übersetzt werden. Die
Auflösung des Domain Namens kann jedoch nicht durch die Übersetzung der
Zeichen erfolgen, sondern die Funktionsweise gleicht mehr der eines
Telefonbuchs. Auf einem DNS Server ist eine Liste hinterlegt. Jede Tupel
in dieser Liste besteht aus zwei Werten. Dem Domain Namen und der
dazugehörigen IP-Adresse. Wird nun über einen sogenannten DNS-Lookup ein
Domain Name überliefert, kann nun als Antwort die passende IP-Adresse
zurückgegeben werden, über welche die erfragte Ressource erreicht werden
kann.

Domain Namen werden nach einer Baumstruktur gegliedert. An erster Stelle stehen die sogenannten Top-Level-Domains (TLD).
