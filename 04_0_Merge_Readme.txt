#### Ausgangslage:


## Erhaltene Daten:

Meldeverzug.zip
Ergänzung_Originaldaten.zip


## 1. Schritt: (Initialdaten entpacken)

Entpacken Meldeverzug.zip, d.h. Erstellen neuer Ordner "Meldedaten_RKI" mit 698 .rds Dateien


## 2. Schritt:

Erstellen zusaetzlichen Ordner "Meldedaten_RKI_orig".


## 3. Schritt: (Duplikate/Dopplungen fuer Pruefung in extra Ordner)

Kopiere die folgenden Dateien FROM "Meldedaten_RKI" TO "Meldedaten_RKI_orig"

cases_GermanTemporal_2020-04-06.rds
cases_GermanTemporal_2020-04-07.rds
cases_GermanTemporal_2020-04-29.rds
cases_GermanTemporal_2020-04-30.rds
cases_GermanTemporal_2020-05-18.rds
cases_GermanTemporal_2020-05-19.rds
cases_GermanTemporal_2020-07-13.rds
cases_GermanTemporal_2020-07-14.rds
cases_GermanTemporal_2021-08-10(1).rds
cases_GermanTemporal_2021-08-10.rds
cases_GermanTemporal_2021-09-08.rds
cases_GermanTemporal_2021-09-09.rds
cases_GermanTemporal_2021-10-25.rds
cases_GermanTemporal_2021-10-26.rds


## 4. Schritt: (Duplikate entfernen)

Loesche die folgenden Dateien IN "Meldedaten_RKI"

cases_GermanTemporal_2020-04-07.rds
cases_GermanTemporal_2020-04-30.rds
cases_GermanTemporal_2020-05-19.rds
cases_GermanTemporal_2020-07-14.rds
cases_GermanTemporal_2021-08-10.rds
cases_GermanTemporal_2021-09-09.rds
cases_GermanTemporal_2021-10-26.rds


## 5. Schritt: (Doppelten Tag vereinheitlichen)

Umbenennen der folgenden Dateien IN "Meldedaten_RKI"

cases_GermanTemporal_2021-08-10(1).rds -> cases_GermanTemporal_2021-08-10.rds


## 6. Schritt: (Ergaenzungsdaten entpacken - beachte: kein Umlaut)

Entpacken Ergänzung_Originaldaten.zip, d.h. Erstellen neuer Ordner "Ergaenzung_Originaldaten" mit 10 .rds Dateien


## 7. Schritt: 

Im Verlauf des zusaetzlichen Teils des Skripts werden dann die Luecken gefuellt.
Es werden die zusaetzlichen Daten verwendet und in "Meldedaten_RKI" gespeichert.
Ebenso werden 2mal Luecken gefuellt und in "Meldedaten_RKI" gespeichert.
