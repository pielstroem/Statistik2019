# Hausaufgabe 1

*Zu erledigen bis zum 29.04.2019 9:00 Uhr*

## 1.1 Installation
Installieren sie Python Anaconda (https://www.anaconda.com/) mit der Python Version 3.7 auf ihrem Rechner. Anaconda enthält
u.a. auch das Paket "Jupyter". Suchen Sie sich ein Tutorial (z.B. https://www.dataquest.io/blog/jupyter-notebook-tutorial/) 
um sich mit den Grundfunktionen von Jupyter vertraut zu machen.

## 1.2 Datensatz: Autoren
Wir untersuchen, wie alt Buchautoren werden. Wählen Sie eine Gruppe von Autoren, z.B. aus einer bestimmten Epoche (100 Jahre),
einem Genre und einer Sprache, und recherchieren Sie, vorzugsweise in einer Bibliographie, für 50 Autoren, welches Alter diese
jeweils erreicht haben (Geburts- und Todesjahr). (Dafür sollte die gewählte Epoche zumindest so weit zurück liegen, daß keiner 
der betreffenden Autoren mehr lebt.)

## 1.3 Datensatz: Drama

Suchen Sie ein Theaterstück in XML-TEI aus. Beispiele für Quellen:
Deutsch: https://textgridrep.org/
Englisch (Shakespeare): http://www.folgerdigitaltexts.org
Französich: https://github.com/cligs/theatreclassique
Spanisch: https://github.com/GHEDI/BETTE/tree/master/corpus
Latein/Altgriechisch: http://www.perseus.tufts.edu/
Beispiel für Theaterstück in XML-TEI (Galdos, Electra):

https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra.xml
Erzeugen Sie eine Tabelle, in der jede Zeile einer Person entspricht, mit folgenden Spalten:
id
label (Name der Person)
gender
role (protagonist, lover, antagonist, other)
importance (primary, secondary, minor)
per_mes_sps (Anzahl von Sprechakten dieser Person; dafür berechnen bzw. zählen wir wie viele sp (oder speaker) Elemente diese Person spricht
Sie können selber definieren, wie Sie die Werte für role (protagonist, lover, antagonist, other) und importance (primary, secondary, minor) den Personen zuteilen.

Beispiel für Tabelle:

https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra_nodes%3Dcharacters.csv

Lesen Sie die Daten in Pandas ein und zeigen Sie das Dataframe an. Berechnen Sie den Mittelwert von per_mes_sps des Theaterstücks (dieses Mal gerne mit .mean()).
Abgabeformat: Nachname_Nr_Titel.pdf Abgabetermin ist der 16.5.2018. An: jose.calvo@uni-wuerzburg.de
