# Störungsbericht – Ultraschallgerät (GE Logiq P5)

- Störungsdatum: 12.05.2024  
- Gerät: Ultraschallgerät – GE Logiq P5  
- Seriennummer: US-112780-Z  
- Abteilung: Sonographieeinheit – Zweiter Stock

---

## Problembeschreibung

Beim Einschalten des Geräts funktionieren Bildschirm und Benutzeroberfläche normal,  
aber **es wird kein Bild angezeigt**, wenn eine Sonde verwendet wird – der Bildschirm bleibt schwarz.

---

## Erstinspektion

- Anschluss der Sonde am Geräteeingang überprüft → korrekt verbunden  
- Zwei verschiedene Sonden (Convex und Linear) getestet → gleiches Problem  
- Gerät mehrfach neu gestartet → Problem besteht weiterhin  
- Keine Fehlermeldungen auf der Benutzeroberfläche angezeigt

---

## Ursachenanalyse (Root Cause Analysis)

Mit Wartungswerkzeugen wurde festgestellt, dass die **Beamformer-Platine** keine Impulse an die Sonden sendet.  
Ein Fehler in der internen Schaltung wurde identifiziert, mit **erhöhter Temperatur** auf der Platine,  
was auf einen **Defekt im Stromversorgungsteil** hinweist – insbesondere einen **beschädigten Kondensator**.

---

## Korrekturmaßnahme (Fix Applied)

- Rückabdeckung geöffnet und Beamformer-Einheit inspiziert  
- Einen **durchgebrannten Kondensator (100μF / 25V)** auf der Hauptplatine ersetzt  
- Bereich gereinigt und Lötstellen sorgfältig repariert  
- Erfolgreicher **Selbsttest** nach dem Zusammenbau durchgeführt  
- Bildtest mit Phantom durchgeführt → normale Bildanzeige

---

## Vorbeugende Maßnahme (Preventive Action)

- Aufnahme der Beamformer-Einheit in den **regelmäßigen Temperaturprüfplan**  
- Empfehlung: Gerät in gut belüfteter Umgebung betreiben, ggf. mit zusätzlicher Kühlung  
- Antrag gestellt zur Lagerung einer **Ersatz-Beamformer-Platine** im Wartungsbestand

---

## Zuständige Ingenieurin

- Name: Wasan Qusay Hasan  
- Freigabe durch Vorgesetzten: [Unterschrift]  
- Nächster Wartungstermin: 12.06.2024
