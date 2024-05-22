### Aktualisierung der MyCBR SDK basierend auf Arbeiten von studentischen Arbeiten 

Die Aktualisierungen / neuen Versionen sind jeweils unter den Branches zu finden. Jeder Branch enthält ein zugehöriges UML-Klassendiagramm zu ebendieser Version (importierbar auf [draw.io](https://app.diagrams.net/)). 
Basierend auf dieser Version wurde ein Tool zum Codevergleich von Nazar verwendet. Die Differenzen zwischen der Standke und der 3.x Version sind jeweils in den Patchnotes.txt Dateien aufgelistet. Ist eine Zeile leer (insbesondere bei der 3.4 Version), so wurde die angezeigte Differenz nicht übernommen, da die Standke Version in den Fällen eine aktuellere Code-Version enthielt. 

Version 3.2 war die Ausgangsversion, bzw. die bereits weiterentwickelte Version von Standke. 

Version 3.3 fügt die Projektarbeit von Kreuzkam hinzu, die diverse Bugfixes beinhaltet.

Version 3.4 für die Arbeit von Ude und Floeter hinzu, welche sich hauptsächlich mit dem Handling von Taxonomien befasst

Version 3.5 "Speedimprovement" von Stram war geplant - aber es konnten keine relevanten Änderungen gefunden werden. Vermutlich waren diese Änderungen in 3.3 oder 3.4 bereits integriert. 


Somit ist der Branch myCBR-3.4-Standke-Kreuzkam-Ude-Floeter die derzeit aktuellste Version. 

### ToDo

1.) Version 3.3 fügte Log4j ein. Trotz besseren Wissens bzgl. der gefunden Schwachstellen, habe ich diesen integriert um Inkonsistenzen zu vermeiden. Dieser muss noch durch eine Alternative ausgetauscht werden. 

2.) Einige Tests werden nicht verwendet bzw. besitzen viel auskommentierten Code.

3.) Der XMLExporter exportiert eine .myMmap, der XMLImporter importiert dieser aber nicht mehr. Ist sicherlich nicht so gewollt?
