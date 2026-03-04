# Masterarbeit: Analyse der Latenz-induzierten Nutzerverlangsamung anhand Mausbewegungsdaten

Dieses Repository enthält den vollständigen Analyse-Code, die Datenverarbeitungspipelines und die statistischen Auswertungen meiner Masterarbeit. 

## Repository-Struktur

Das Projekt ist in drei Hauptbereiche unterteilt:

### 1. Main Study (`/mainStudy`)
Der Kern der Untersuchung mit den Daten der Hauptprobanden.
* **`mouseDataMainStudy/`**: Hochfrequente Rohdaten des Maus-Trackings.
* **`trialDataMainStudy/`**: Zusammenfassende Daten pro Trial.
* **`trial_exclusion.ipynb`**: Pipeline für den Datenausschluss.
* **`effect.ipynb`**: Statistische Auswertung und finale Visualisierungen.
* **`exploratory.ipynb`**: Zum Vergleich mit den Ergebnissen der Vorstudie + Validation der Anpassung des Studiendesigns.


### 2. Pre-Study (`/preStudy`)
Datenanalyse von Daten aus eine Vorgängerstudie.
* Enthält Skripte zur ersten Exploration (`exploratory.ipynb`) und zur Datenbereinigung (`clean.ipynb`).
* **`effect.ipynb`**: Statistische Auswertung und finale Visualisierungen.

### 3. Latency System (`/latency_system`)
* Messwerte zur Bestimmung der Ende-zu-Ende Verzögerung des Systems.
* **`latency_system.ipynb`**: Visualisierung der Daten.
