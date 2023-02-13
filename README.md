# MetaHeart - ein Projekt zum Metabolischen Syndrom

## Was ist MetaHeart?

MetaHeart ist ein Projekt, dass im Rahmen des [Master-BIDS Studiengangs](https://www.master-bids.hs-mannheim.de) der [Hochschule Mannheim](https://www.hs-mannheim.de), in Kooperation mit der [Graduate School Rhein-Neckar](https://gsrn.de) und dem [MIRACUM-Konsortium](https://www.miracum.org/) im Modul [Datenmanagement und Archivierung](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung-1.html) im Wintersemester 2022/23 entstanden ist. Es hat zum Ziel, den gesamten Prozess eines Forschungsprojektes mit besonderem Fokus auf das Datenmanagement unter Berücksichtigung der [FAIR-Prinzipien](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#fair-prinzipien-und-standards-in-forschungsdatensätzen) zu durchlaufen und in diesem Git-Repository transparent zu dokumentieren.

## Auf welchen Daten beruht MetaHeart?

Das Projekt ist fiktiv und bedient sich synthetischen Datensätzen, die mithilfe von [Synthea](https://github.com/synthetichealth/synthea) generiert wurden und wie Bestandsdaten aus Krankenhäusern retrospektiv zur Analyse herangezogen werden. Diese sind als [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) hinterlegt.

Alle Patienten, die in diese Studie eingeschlossen sind, leiden am Metabolischen Syndrom. Im Zuge verschiedener Routineuntersuchungen oder notfallbedingter Arztbesuche oder Krankenhausaufenthalte wurden bei einem Großteil der Patienten Sekundärerkrankungen des Herz-Kreislaufsystems festgestellt, dokumentiert und wenn nötig, medikamentös behandelt. Diese Dokumentationen dienen uns als Datengrundlage ([Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation)) im MetaHeart-Projekt.

## Wie ist MetaHeart aufgebaut?

Für das MetaHeart-Projekt haben wir uns basierend auf den bereitgestellten [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) folgende wissenschaftliche [Fragestellung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#11-fragestellung) überlegt:



Im Wiki wurde 
1. ein [Projektplan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#1-projektbeschreibung) angelegt, der folgende Punkte beinhaltet:

2. ein [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/DMP_METAHEART#datenmanagementplan-metaheart) erstellt, der folgende Inhalte umfasst:

 c. die Planung des Vorgehens wurde in einem Datenmanagementplan als Begleitdokument beschrieben und regelmässig auf den neusten Stand gemacht#
 
 d. der Zugriff auf die Quelldaten so wie deren Prozessierung (Formatierung, Sortieren)
 
 e. Extraktion der forschungsrelevanten Daten aus den zur Verfüfung stehenden Datenbanken, deren Trasformation und Ablage in einem Datawarehouse erfolgten     während der ETL-Przesse die die Grundlage für die Datenanalyse bilden
 
 f. Anslyse der Daten im DWH zum Erhalt der Ergbnisse, die die Beantwortung der Forschungsfrage erlauben und eine Darstellung dieser ermöglichen
 
 ## Kann ich MetaHeart nutzen?
 
 Ja!
