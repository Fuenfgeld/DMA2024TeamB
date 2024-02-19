# DMA2024TeamB

!Daten/PRECISE-BC.jpg

# PRECISE-BC: Probing QALY Changes in Breast Cancer Patients with and without Comorbidities

**Ein Data Management Projekt im Rahmen des Online-Masters "Biomedizinische Informatik und Data Science" an der Hochschule Mannheim.**

Dieses GitHub-Repository enthält den Code und die Dokumentation für das Data Management Projekt "PRECISE-BC". Ziel des Projekts ist die Datenaufbereitung, -verarbeitung und Analyse von synthetischen Patientendaten, die mit Synthea TM generiert wurden. Das Hauptaugenmerk liegt auf der Auswirkung von Komorbiditäten auf die Lebensqualität von Brustkrebspatientinnen und -patienten.

## Projektübersicht

Das Projekt simuliert und erarbeitet alle Prozesse eines Datenmanagement-Projekts:

1. Erstellen des [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Datenmanagementplan) der
[Projektoutline und Studienziele](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Projektoutline-und-Studienziele) sowie 
[Datenschutzfolgeabschätzung](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Datenschutzfolgeabsch%C3%A4tzung)
2. [Erstellung der Quelldatenbank](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Erstellung-Quelldatenbank) mittels Rohdaten/
[Quelldaten](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Quelldaten)
3. Überführen der Daten in ein Data Warehouse, [(ETL-Prozess)](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/ETL%E2%80%90Prozess)
4. Erarbeitung eines [statistischen Analyse Plans](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Statistischer-Analyse-Plan) sowie Analyse und Visualisierung der Daten gemäss der selbst gewählten Forschungsfrage


## Forschungsfrage

Wie beeinflussen Komorbiditäten die Lebensqualität von Brustkrebspatientinnen und -patienten?

## Projektdurchführung

- **Datenmanagement:** Erstellung eines Datenmanagementplans, Durchführung einer Datenschutz-Folgenabschätzung.
- **Quelldatenbank:** Quelldaten wurden mithilfe eines Google Colab Notebooks in die Quelldatenbank geladen.
- **ETL-Prozess:** Daten wurden aus der Quelldatenbank extrahiert, transformiert und in ein Data Warehouse geladen.
- **Datenanalyse:** Durchführung einer explorativen Datenanalyse und experimenteller Machine Learning Ansätze.
- **Archivierung:** Veröffentlichung des Projekts als Release im GitHub Repository und Archivierung auf Zenodo.

## Ergebnisse

Die Analyseergebnisse und erstellten Plots sind im [GitHub Wiki](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Datenanalyse-und-Resultate) dokumentiert.

## Systemumgebung

Die Skripte wurden in Python und SQLite erstellt, mit Google Colab als Entwicklungsumgebung. Alle Informationen zur Systemumgebung sind im [[Wiki - Systemumgebung](https://github.com/Fuenfgeld/DMA2024TeamB/wiki/Systemumgebung)) dokumentiert.

## Projektausführung

Um die Projektausführung nachzuvollziehen, führen Sie die Notebooks in der angegebenen Reihenfolge online in Google Colab oder lokal auf Ihrem Rechner aus:

1. [Setup_and_fill_Database.ipynb](https://github.com/Fuenfgeld/DMA2024TeamB/blob/main/Code/teamb_import_csv_into_sql.ipynb)
2. [ETL_Process.ipynb](https://github.com/Fuenfgeld/DMA2024TeamB/blob/main/Code/Datawarehouse_TeamB_V2_20240204.ipynb)
3. [Data_Analysis.ipynb](https://github.com/Fuenfgeld/DMA2024TeamB/blob/main/Code/EDA_template_teamb.ipynb)

**Viel Erfolg bei der Exploration unseres Projekts! Bei Fragen stehen wir gerne zur Verfügung.**
