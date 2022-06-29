# Höhenpunkte ausdünnen

Mit diesem Befehl im Menü Extras werden Höhenpunkte in der aktuellen Datei gelöscht. Das in CadnaA angewendete Verfahren bezieht in jedem Iterationsschritt das gesamte Bodenmodell ein. Der Anwender gibt die gewünschte Obergrenze der z-Abweichung („Toleranz“) zwischen jedem „weggeworfenen“ Punkt und dem letztlich resultierenden vereinfachten Geländemodell ein. Das als Ergebnis verbleibende Bodenmodell weicht maximal um die genannte Obergrenze vom Orginalmodell ab.

DIALOGOPTIONEN

Toleranz (m)
Wert, der die vertikale Abweichung gegenüber dem resultierenden Geländemodell begrenzt (Standardwert: 0.10 m).

Option "alte Methode"
Ist diese Option aktiviert, so wird das in früheren Versionen von CadnaA verwendete Verfahren angewandt.


# Höhenpunkte ausdünnen (Multifile)
Dieser Befehl entspricht dem Befehl Höhenpunkte ausdünnen in demselben Menü Extras, bis auf die Möglichkeit nach Angabe der Toleranz mehrere Dateien mit Höhenpunkten auswählen zu können.

Über die Schaltfläche "Optionen" im Dialog Dateien importieren können die Optionen für den ASCII-Import festgelegt werden.

HINWEIS: Diese Funktion gestattet den Import selbst von Geländemodellen, die im Ausgangszustand die vorgegebene maximale Dateigröße von 32 Bit-Betriebssystemen (2 GigaByte) übersteigen würden.
