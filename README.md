# MetaHeart - ein Projekt zum Metabolischen Syndrom

*_see [English Version](https://github.com/Fuenfgeld/DMA2023TeamC#metaheart---project-summary) below_

# :de:

## :heart_decoration: Was ist MetaHeart?

MetaHeart ist ein Projekt, dass im Rahmen des [Master-BIDS Studiengangs](https://www.master-bids.hs-mannheim.de) der [Hochschule Mannheim](https://www.hs-mannheim.de), in Kooperation mit der [Graduate School Rhein-Neckar](https://gsrn.de) und dem [MIRACUM-Konsortium](https://www.miracum.org/) im Modul [Datenmanagement und Archivierung](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung-1.html) im Wintersemester 2022/23 entstanden ist. Es hat zum Ziel, den gesamten Prozess eines Forschungsprojektes mit besonderem Fokus auf das Datenmanagement unter Berücksichtigung der [FAIR-Prinzipien](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagement#fair-prinzipien-und-standards-in-forschungsdatensätzen) zu durchlaufen und in diesem Git-Repository transparent zu dokumentieren.

## :heart_decoration: Auf welchen Daten beruht MetaHeart?

Das Projekt ist fiktiv und bedient sich synthetischen Datensätzen, die mithilfe von [Synthea](https://github.com/synthetichealth/synthea) generiert wurden und wie Bestandsdaten aus Krankenhäusern retrospektiv zur Analyse herangezogen werden. Diese sind als [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) hinterlegt.

Alle Patienten, die in diese Studie eingeschlossen sind, leiden am Metabolischen Syndrom. Im Zuge verschiedener Routineuntersuchungen oder notfallbedingter Arztbesuche oder Krankenhausaufenthalte wurden bei einem Großteil der Patienten Sekundärerkrankungen des Herz-Kreislaufsystems festgestellt, dokumentiert und wenn nötig, medikamentös behandelt. Diese Dokumentationen dienen uns als Datengrundlage ([Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation)) im MetaHeart-Projekt.

## :heart_decoration: Wie ist MetaHeart aufgebaut?

Für das MetaHeart-Projekt haben wir uns basierend auf den bereitgestellten [Quelldaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation) folgende wissenschaftliche [Fragestellung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#fragestellung) überlegt:

Werden die Ausprägungen von Herz-Kreislauferkrankungen, die als Folge des Metabolischen Syndroms auftreten, durch den ethnischen Hintergrund des Patienten beeinflusst, und hat dieser Unterschiede in der medikamentösen Behandlung zur Folge?

Das Wiki umfasst folgende Punkte:

1. Die [Projektbeschreibung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung), die folgende Punkte beinhaltet:

* [Fragestellung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#fragestellung)

* [Zusammenfassung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#zusammenfassung)

* [Einleitung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#einleitung)

* [Hypothese](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#hypothese)

* [Ergebnisse](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#ergebnisse)

* [Schlussfolgerungen](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#schlussfolgerungen)

2. Ausführungen zum [Datanmanagement](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagement) und den FAIR-Prinzipien

3. den [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART) mit folgenden Inhalten:

* [Administrative Daten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#1-administrative-daten)

* [Verantwortlichkeiten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#2-verantwortlichkeiten)

* [Datenmanagement](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#3-datenmanagement)

4. Hinweise zur [Reproduzierbarkeit](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Reproduzierbarkeit) des Code
 
 ## :heart_decoration: Wie wurde die Analyse durchgeführt?
 
 Die Übersicht zur Datenprozessierung findet ihr [hier](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementprozesse).
  
1. Schritt: Erstellung einer [Quelldatenbank](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenbankerstellung)
2. Schritt: [ETL-Prozess](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/ETL--Prozesses): Pseudonymisierung der Patienten, Selektion der für die Forschungsfrage relevanten Daten, Erstellung der Datawarehouse-Datenbank
3. Schritt: eigentliche [Analyse](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenpräsentation-und--speicherung)

 ## :heart_decoration: Kann ich MetaHeart nutzen?
 
 Ja! Die Skripte sind für jederman ausführbar und reproduzierbar unter Beachtung der [MIT-Lizenz](https://github.com/Fuenfgeld/DMA2023TeamC/blob/main/Dokumentation/LICENSE_MIT_CODE) . Hinweise zur [Reproduzierbarkeit](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Reproduzierbarkeit) des Code, der [Systemumgebung](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Systemumgebung) und den [Metadaten](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Metadata-file) sind im Wiki hinterlegt. Die Nachnutzung der Dokumentation und Daten in diesem Repository unterliegen der [Creative Commons Lizenz 4.0](https://creativecommons.org/)
![image](https://user-images.githubusercontent.com/122311423/223393555-ebcd489e-ca28-4222-bbac-fa6629f015e3.png).

# _MetaHeart - Project Summary_

# :gb: :us:

## :heart_decoration: What is MetaHeart?

MetaHeart is a Project of the [Master-BIDS Study Course](https://www.master-bids.hs-mannheim.de), offered by the [University of Applied Sciences Mannheim](https://www.hs-mannheim.de), in Cooperation with the [Graduate School Rhein-Neckar](https://gsrn.de) and the [MIRACUM Consortium](https://www.miracum.org/) as part of the Course [Data management and Archiving](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung-1.html) 2022/23 entstanden ist. It aimed to simulate the entire process of a research project by considering the [FAIR principles](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/METAHEART-Projekt#fair-prinzipien-und-standards-in-forschungsdatensätzen) of a good data management practice and document the process in this Git repository transparently.

## :heart_decoration: What kind of data is used for MetaHeart?

This project is fictional. It is based on artifial, synthetic datasets, generated by [Synthea](https://github.com/synthetichealth/synthea). This data is treated like retrospective patient data from hospitals in Massachusetts/USA. The source data is maintained [here](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation).

All patients in this study suffer from Metabolic Syndrom. In the course of routine examinations, emergency visits to the doctor or hospitalisations, secondary diseases of the cardiovascular system were documented and medicated if necessary. This documentation serves us as ([source data](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Quelldatendokumentation)) in the MetaHeart project.

## :heart_decoration: What does the MetaHeart Wiki contain?

The Wiki contains the following details:

1. the [Project description](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung) containing the following:

* [aim of the study](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#fragestellung)

* [summary](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#zusammenfassung)

* [introduction](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#einleitung)

* [hypothesis](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#hypothese)

* [results](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#ergebnisse)

* [conclusion](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Projektbeschreibung#schlussfolgerungen)

2. implementations regarding [Data management](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagement) and FAIR principles

3. the [Data management plan](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART) containing the following:

* [Administrative data](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#1-administrative-daten)

* [Responsibilites](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#2-verantwortlichkeiten)

* [Data management](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Datenmanagementplan-(DMP)--METAHEART#3-datenmanagement)

4. Details about [Reproducibility](https://github.com/Fuenfgeld/DMA2023TeamC/wiki/Reproduzierbarkeit) of the Code
