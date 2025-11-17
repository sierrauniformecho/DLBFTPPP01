# Studienabgabe: Modellbildung mit Python (Aktienkursprognose)

Diese Studienabgabe gehört zum Modul *DLBFTPPP01 - Programmierung mit Python* an der IU. Ziel ist es, auf Basis historischer Aktienkurse ein einfaches Prognosemodell zu entwickeln und die Ergebnisse zu visualisieren. 

## Zielsetzung:
- Datenabruf über **Alpha Vantage API**
- Datenaufbereitung & Feature Engineering
- Modelltraining (z.B. lineare Regression)
- Evaluation & Visualisierung der Prognosen

## Projektstruktur
- data = Rohdaten & gespeicherte CSVs
 - src = Code-Module
   - fetch_data.py = API Daten holen
   - prepare_data.py = Features & Train/Test-Split
   - model.py = Modellaufbau & Vorhersage
   - evaluation.py = Fehlermaße
   - plotting.py = Visualisierung


#### Quelle: *Alpha Vantage API*
#### Modul: *DLBFTPPP01 - Programmierung mit Python*
#### Autor: *S. Lohr*
#### Jahr: *2025*
