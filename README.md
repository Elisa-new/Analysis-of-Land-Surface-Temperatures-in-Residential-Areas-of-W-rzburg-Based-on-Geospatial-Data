# Bachelorarbeit_LST_Wue

# Analyse der Landoberflächentemperatur in Würzburgs Wohngebieten anhand von Geodaten: Neu- und Bestandsgebiete im Vergleich

Dieses Repository enthält die im Rahmen der Bachelorarbeit verwendeten Jupyter Notebooks sowie ergänzende Dateien zur Reproduzierbarkeit der Methodik.

Die Notebooks sollten in der unten aufgeführten Reihenfolge ausgeführt werden. Die jeweiligen Datensätze müssen zuvor von den in der Arbeit beschriebenen Quellen heruntergeladen und in einer entsprechenden Ordnerstruktur (s.h. "Colab_Notebook_Pfade") abgelegt werden. 
## Reihenfolge der Notebooks

### 1. GHSL

Das Notebook **„GHSL“** dient der Identifikation der Untersuchungsgebiete anhand des Global Human Settlement Layer (GHSL). Zudem enthält es die Beschreibung der Untersuchungsgebiete auf Basis der bebauten Fläche.

### 2. Beschreibung

Im Notebook **„Beschreibung“** befindet sich der Code zur Auswertung der Datensätze DGM1, LoD2 und ALKIS. Die Ergebnisse dienen der Charakterisierung der Untersuchungsgebiete.

### 3. Preprocessing

Das Notebook **„Preprocessing“** umfasst die Vorverarbeitung der Landsat-Daten und bereitet diese für die weiteren Analysen vor.

### 4. NDVI, LST und Albedo

Die Notebooks **„NDVI“**, **„LST“** und **„Albedo“** enthalten die indikatorspezifischen Auswertungsschritte.

## Shapefiles der Untersuchungsgebiete

Die in QGIS manuell digitalisierten Umrisse der Bebauungspläne sind im Ordner **„Shapefiles_Gebiete“** gespeichert.

## Datenquellen

Die verwendeten Datensätze werden in der Bachelorarbeit detailliert beschrieben. Aufgrund möglicher Lizenz- und Nutzungsbeschränkungen sind die Originaldatensätze nicht Bestandteil dieses Repositories und müssen eigenständig von den jeweiligen Datenanbietern bezogen werden.




