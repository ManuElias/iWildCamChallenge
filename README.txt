Zur Bearbeitung der Projektaufgabe wurde das RetinaNet herangezogen. Für die Detection in den Bildern wurde der MegaDetector-V4 angewendet. Aufgrund der großen Datenmenge wurde sich im Team dazu entschieden, dass Projekt in Kaggle-Notebooks anstatt in Colab-Notebooks durchzuführen. Dies ersparte das Export und Import Problem, welches durch die große Datenmenge von 110GB Bilder entstanden wäre. Jedoch ist nach einiger Zeit aufgefallen, dass die Kaggle-Notebooks auf eine Laufzeit von 9h begrenzt sind und man in der Woche maximal 43h GPU-Rechenleistung zur Verfügung hat. Da jedoch die Nutzung des Detectors und des RetinaNets für die 62.870 Abgabe-Bilder in diesen Zeitspannen mit gegebener Rechenleistung für uns nicht möglich war, haben wir eine alternative Lösung erarbeitet. Diese enthält den Detector und das RetinaNet nur für einen kleinen Datenausschnitt. Für die Abgabe wurde ein herkömmlicher Klassifikator trainiert und auf die Abgabe-Bilder angewendet. Abschließend wurde der herkömmliche Klassifikator noch in Form einer App zur Nutzung im Alltag zur Verfügung gestellt.

Inhalt der Abgabe sind folgende Dateien:

1. Projekt Lösungen
2. MegaDetector_V4
3. RetinaNet
4. Herkömmlicher Klassifikator
5. Erste Kaggle Abgabe CSV
6. Zweite Kaggle Abgabe CSV
7. QuellCode zur App
8. Requirements.txt für App
9. MegaDetector_V4 BeispielErgebnis

Verfasser: Emanuel Elias, Franziska XXX, Christoph XXX
