5.1 Untersuchen sie, analog zu unserem Vorgehen in der letzten Seminarstunde, das erreichte Lebensalter von Frauen uns Männern in Ihrem eigenen Datensatz. (Sollte Ihr Datensatz eine bisher eine Genderbalance von 0 : 100% haben, wäre das der Zeitpunkt, ihn um ein paar Zeilen zu ergänzen.) Laden Sie den Datensatz in ein Jupyter-Notebook. Ermitteln Sie Mittelwert und Standardabweichung für die Lebensalter aller Autoren zusammen, sowie für Frauen und Männer getrennt.

5.2 Konstruieren Sie, analog zu unserem Vorgehen in der letzten Seminarstunde, ein Nullmodell, an dem sich abschätzen lässt, wie sich 2 rein zufällige Stichproben aus der selben Grundgesamtheit unterscheiden können. Programmieren Sie ein Schleife in der Sie wiedeholt jeweils 2 gleich große Stichproben aus einer normalverteilten Grundgesamtheit ziehen. Berechnen Sie für jede der beiden Stichproben einen Mittelwert und speichern Sie die differenz dieser Mittelwerte in einer Liste. Stellen Sie die Verteilung dieser Mittelwertdifferenzen in einem Histogramm dar. Wählen Sie für die Normalverteilte Grundgesamtheit die in 5.1 ermittelten Parameter des Gesamtdatensatzes für Mittelwert und Standardabweichung. (Hinweis: Bis hierhin ist das alles Wiederholung der letzten Sitzung.)

5.3 Erstellen Sie nun eine neue Schleife, aber nicht mit den einfachen  Mittelwertdifferenzen, sondern mit einer Implementierung des t-Wertes.

Sie können dafür folgende Formel verwenden:

$ t = \frac{\bar{X}_1 - \bar{X}_2}{s_p \sqrt\frac{2}{n}} $

wobei:

$ s_p = \sqrt{\frac{s_{X_1}^2+s_{X_2}^2}{2}} $

Eine ausführliche (wenngleich nicht wissenschaftlich zitierbare) Erläuterung finden sie in der [Wikipedia](https://en.wikipedia.org/wiki/Student%27s_t-test)

Abgabe bis zum 06.06.2019, 10:00 Uhr