# projekt_blumentopf

Automatisiert wird ein Treibhaus. 
Die Lufttemperatur sowie die Luftfeuchtigkeit werden überwacht und via Ventilator reguliert, sobald das Verhältnis nicht stimmt. Visuell wird dies mit einem Ampelsystem dargestellt.
Die Feuchtigkeit der Erde in der die Pflanze wächst wird überwacht. Sobald die Planze Wasser braucht, also die Feuchtigkeit zu niedrig ist, wird via Buzzer ein akkustisches Signal ausgegeben, welches abgeschaltet wird, sobald die Planze gegossen wurde. 


## Anforderungen
| Anforderungen      | Muss                | Wunsch              |
|:------------------ |:-------------------:| :------------------:|
|Arduino muss Signale der Sensoren DHT11/Wasserlevel empfangen.|x||
|Arduino gibt Werte auf einem Bildschirm aus.|x||
|Buzzer meldet akkustisch, wenn Planze Wasser braucht.|x||
|Ampelsystem visualisiert Status der Luft.|x||
|Ventilator lässt Luft im Treibhaus zirkulieren, wenn Temp./Hum. ratio nicht stimmt.|x||
|ESP32 (Wifi) lädt Messwerte in die Cloud.||x|
|Arduino sendet Email/SMS falls Pflanze Wasser benötigt.||x|

## Projektplan
- 01.12.2024 - Abgabe Projektplan
- 07.12.2024 - Kompatibilität von Hardware überprüft
- 07.12.2024 - Komponenten getestet
- 07.12.2024 - Flussdiagramm erstellt
- 14.12.2024 - Softwarecode geschrieben
- 21.12.2024 - Tests abgeschlossen
- 04.01.2025 - Projektabschluss (Video, Dokumentation, Präsentation)

## Flussdiagramm
In diesem Flussdiagramm wird das Auslesen und die Verzweigungen des Projekts aufgezeigt.

Funktionen:
- Gelb = Muss
- Türkis = Wunsch

![arduino blumentopf](https://github.com/user-attachments/assets/67ebdfcc-c06b-49a0-beef-22e57c7c482b)


## Projektbeschreibung
Kurze Beschreibung der Vorgehensweise

- Welche Teilfunktionen habt ihr einzeln getestet?
- Gab es dabei Probleme, wenn ja welche?
- Konnten alle Muss-Anforderungen umgesetzt werden?
- Nein, warum konnten nicht alle umgesetzt werden?
- War etwas unerwartet beim Schreiben des Programcodes?

## Tests
Kurze Beschreibung der Vorgehensweise

- Was sind die Testscenarios?
- Beschreibung oder Bild das Testziel aufzeigt
- Gibt es spezielle Gründe warum diese Tests gewählt wurden?
