# MetaHeart - ein Projekt zum Metabolischen Syndrom

*_see English Version below_

## Was ist MetaHeart?

MetaHeart ist ein Projekt, dass im Rahmen des [Master-BIDS Studiengangs](https://www.master-bids.hs-mannheim.de) der [Hochschule Mannheim](https://www.hs-mannheim.de), in Kooperation mit der [Graduate School Rhein-Neckar](https://gsrn.de) und dem [MIRACUM-Konsortium](https://www.miracum.org/) im Modul [Datenmanagement und Archivierung](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung-1.html) im Wintersemester 2022/23 entstanden ist. Es hat zum Ziel, den gesamten Prozess eines Forschungsprojektes mit besonderem Fokus auf das Datenmanagement unter Berücksichtigung der [FAIR-Prinzipien](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#fair-prinzipien-und-standards-in-forschungsdatensätzen) zu durchlaufen und in diesem Git-Repository transparent zu dokumentieren.

## Auf welchen Daten beruht MetaHeart?

Das Projekt ist fiktiv und bedient sich synthetischen Datensätzen, die mithilfe von [Synthea](https://github.com/synthetichealth/synthea) generiert wurden und wie Bestandsdaten aus Krankenhäusern retrospektiv zur Analyse herangezogen werden. Diese sind als [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) hinterlegt.

Alle Patienten, die in diese Studie eingeschlossen sind, leiden am Metabolischen Syndrom. Im Zuge verschiedener Routineuntersuchungen oder notfallbedingter Arztbesuche oder Krankenhausaufenthalte wurden bei einem Großteil der Patienten Sekundärerkrankungen des Herz-Kreislaufsystems festgestellt, dokumentiert und wenn nötig, medikamentös behandelt. Diese Dokumentationen dienen uns als Datengrundlage ([Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation)) im MetaHeart-Projekt.

## Wie ist MetaHeart aufgebaut?

Für das MetaHeart-Projekt haben wir uns basierend auf den bereitgestellten [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) folgende wissenschaftliche [Fragestellung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#11-fragestellung) überlegt:

Im Wiki wurde

**A** ein [Projektplan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#1-projektbeschreibung) angelegt, der folgende Punkte beinhaltet:

1. [Fragestellung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#11-fragestellung)
2. [Zusammenfassung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#12-zusammenfassung)
3. [Einleitung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#13-einleitung)
4. [Hypothese](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#14-hypothese)
5. [Ergebnisse](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#15-ergebnisse)
6. [Schlussfolgerungen](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#16-schlussfolgerungen)

7. [Datenmanagement](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#2-datenmanagement)
8. [Datenquellen und -qualität](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#21-datenquelle-und-qualität)
9. [Datenprozessierung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#22-datenprozessierungsschema)

**B** ein [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/DMP_METAHEART#datenmanagementplan-metaheart) erstellt, der folgende Inhalte umfasst:

1. [Administrative Daten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/DMP_METAHEART#1-administrative-daten)

2. [Verantwortlichkeiten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/DMP_METAHEART#2-verantwortlichkeiten)

3. [Datenmanagement](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/DMP_METAHEART#3-datenmanagement)

Der DMP wird regelmässig auf den neuesten Stand gebracht durch einfügen von Dokumenten die sich auf das Projekt beziehen und schliessen auch Dokumente Dritter ein, wenn diese sich auf das Projekt beziehen. Metadaten werden zeitgleich aktualisiert und timestamped gespreichert. Die Frequenz der Updates ist wöchentlich. Die Daten werden über die  Projekt-ID abgerufen, die nach den Lizenzen [CC](https://github.com/Fuenfgeld/DMA2023TeamC/blob/main/Dokumentation/CC_BY-SA_4.0_License) und [MIT-Softwarelizenz](https://github.com/Fuenfgeld/DMA2023TeamC/blob/main/Dokumentation/LICENSE_MIT_CODE) bei Weiter- oder Wiederverwendung genannt werden müssen. 
 
 ## Wie wurde die Analyse durchgeführt?
 
 Die Übersicht zur Datenprozessierung findet ihr [hier](https://github.com/Fuenfgeld/DMA2023TeamC/blob/main/MetaMeart_Datenverarbeitungsschema.png).
 
 _ist das aktuell?_
 
 
 d. der Zugriff auf die Quelldaten so wie deren Prozessierung (Formatierung, Sortieren)
 
 e. Extraktion der forschungsrelevanten Daten aus den zur Verfüfung stehenden Datenbanken, deren Trasformation und Ablage in einem Datawarehouse erfolgten     während der ETL-Przesse die die Grundlage für die Datenanalyse bilden
 
 f. Analyse der Daten im DWH zum Erhalt der Ergbnisse, die die Beantwortung der Forschungsfrage erlauben und eine Darstellung dieser ermöglichen
 
 ## Kann ich MetaHeart nutzen?
 
 Ja! Die Skripte sind für jederman ausführbar und reproduzierbar unter Beachtung der [MIT-Lizenz](https://github.com/Fuenfgeld/DMA2023TeamC/blob/main/Dokumentation/LICENSE_MIT_CODE) . Hinweise zu [Systemumgebung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Systemumgebung) und Reproduzierbarkeit des Code sind im Wiki hinterlegt.

Summary _English_

## What is MetaHeart?

MetaHeart is a Project of the [Master-BIDS Study Course](https://www.master-bids.hs-mannheim.de), offered by the [University of Applied Sciences Mannheim](https://www.hs-mannheim.de), in Cooperation with the [Graduate School Rhein-Neckar](https://gsrn.de) and the [MIRACUM Consortium](https://www.miracum.org/) as part of the Course [Data management and Archiving](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung-1.html) 2022/23 entstanden ist. It aimed to simulate the entire process of a research project by considering the [FAIR principles](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#fair-prinzipien-und-standards-in-forschungsdatensätzen) of a good data management practice and documente the process in this Git repository transparently.

## What kind of data is used for MetaHeart?

 Projekt ist fiktiv und bedient sich synthetischen Datensätzen, die mithilfe von [Synthea](https://github.com/synthetichealth/synthea) generiert wurden und wie Bestandsdaten aus Krankenhäusern retrospektiv zur Analyse herangezogen werden. Diese sind als [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) hinterlegt.

Alle Patienten, die in diese Studie eingeschlossen sind, leiden am Metabolischen Syndrom. Im Zuge verschiedener Routineuntersuchungen oder notfallbedingter Arztbesuche oder Krankenhausaufenthalte wurden bei einem Großteil der Patienten Sekundärerkrankungen des Herz-Kreislaufsystems festgestellt, dokumentiert und wenn nötig, medikamentös behandelt. Diese Dokumentationen dienen uns als Datengrundlage ([Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation)) im MetaHeart-Projekt.
