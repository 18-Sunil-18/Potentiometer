# Potentiometer
Drehregler zum Regeln der Blinkgeschwindigkeit einer LED verwenden.

Aufgabe: Eine LED soll blinken. Die Blinkgeschwindigkeit soll mit einem Drehregler eingestellt werden.

Material: Arduino / ein Drehregler (Potentiometer) / Breadboard / LED / 100 Ohm Widerstand / Kabel

Lerninhalt: Spannung eines Drehreglers auslesen, Sensorwerte mathematisch verarbeiten und für eine Ausgabe verwenden (In diesem Fall für die Dauer einer Pause).

Ein Drehregler hat drei Anschlüsse. Außen wird + und – angeschlossen. Von dem mittleren Pin geht ein Kabel zu einem analogen Eingangspin am Mikrocontroller-Board. Wenn man den Drehregler dreht, dann gibt der mittlere Pin ein Spannung zwischen 0 und 5 Volt aus. Drehregler ganz links: 0 V und Drehregler ganz rechts: 5V, bzw. Seitenverkehrt, je nach Verkabelung.
