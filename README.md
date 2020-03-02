# Localisation-via-ML-Methods

**Dieses Repository enthält die Diplomschrift von Ida Hönigmann und Peter Kain aus dem Schuljahr 2019/20.**

## Meetings

### 13.09.2019

* Viele Fotos vom Aufbau
* Zuerst Tenserflow, dann eigene Implementierung in C++ (dadurch früheres Testen des Konzeptes)

### 20.09.2019

* Lightning talk jeden Freitag (Beginnt mit TensorFlow und Blender)
* Blender für Testdatengenerierung
* TensorFlow, dann erst C++
* bis Ende November muss feststehen ob airtems (und wer davon) zur ECER fährt

### 14.10.2019

* getane Arbeit: Blender-Datengenerierung implementiert, OpenCV-Bildbearbeitung begonnen
* StereoCamera Kapitel Rückmeldung von Michael
* in Herbstferien arbeiten!
* Arbeit zu tun: TensorFlow

### 21.10.2019

* getane Arbeit: TensorFlow begonnen, OpenCV Bilder gemerged (wegen Problemen in Tensorflow)
* Distortion Kapitel Rückmeldung von Michael nach den Herbstferien
* in Herbstferien mehr arbeiten!
* Arbeit zu tun: TensorFlow

### 04.11.2019

* Distortion einfacher beschreiben (Stichwort: tonnenförmige Verzeichnung)
* TensorFlow Fehler möglich durch fehlerhafte Normierung
* Diplomschrift heute noch schicken (markieren was sich geändert hat)

### 18.11.2019

* Probleme in DA aufnehmen + warum und was hat nicht funktioniert?
* 10k Testdaten generiert
* kernel killed process because of ressource starvation
* NN verändern (insbesondere Conv Layers) -> weniger RAM Verbrauch
* wenn noch nicht genug: weniger Bilder
* noch immer nicht funktionierend: Bilder weiter downscalen oder croppen
* Wunsch: bis Weihnachen 90% Diplomschrift fertig

### 25.11.2019

* ressource starvation behoben
* aktueller Stand: loss: 0.2483 und mean_absolute_percentage_error: 13.2273
* 50 Seiten Diplomschrift :-)
* weights laden; mit 50 Bildern trainieren; weights speichern
* NN ist gleich geblieben
* begonnen mit 10k Bildern (von Suzanne_m_greyscale) zu trainieren

### 9.12.2019

* Verteilungsfunktion der Entfernungen + kapitel?
* Todo: mehr Testdaten generieren
* Beginn der C++ Implementierung
* Visualisierung der Gewichte
* Momentum term
* acc bleibt bei 13%

### 16.12.2019

* aktuelle Version spätestens am 19.12.2019 nocheinmal schicken
* Korrelation zwischen cnt(conv layers) und Anzahl Bilder benötigt?
* C++ Implementation weitergemacht: Layer werden richtig verbunden
* mehr Statistik in der Diplomschrift (siehe Korrelation ...)
* auf Heizhaus PC rendern :-) (ab Freitag?)
* Bessere Loss-Function?

### 13.01.2020

* Ferien für Entwicklung von C++ genutzt
* Vergleich Tensorflow in Python und C++ von Peter z.B. mit XOR
* Funktioniert Blender NN auch auf echter Drohne? (Benchmark)
* PC wird aufgesetzt

### 20.01.2020

* C++ Implementierung weitergeschrieben
* neue Blender Render generiert
* Daten auf x- y- und z-Entfernung umgestellt 
* alte Bebop auf Funktionalität testen
* mit Manuel ros gazebo durchgehen

### 27.01.2020

* TensorFlow < C++ Implementierung (xor)
* Bilder jetzt in rgb und floats
* mehr Testdaten
* Trainieren auf Heizhaus PC
* bis Mittwoch: neueste Version abgeben

### 24.02.2020

* aktueller Stand heute (wegen Plagiatscan)
* gemeinsame Abnahme am 6. März
* Experiment 1 durchgeführt und DA dazu geschrieben
* Todo: Experiment 2 in nächster Zeit machen

### 2.03.2020

* am 6. März zwischen 15:30 und 15:30 im K03
* 3D Druck fertig
* Experiment 2 in nächster Zeit zu tun
