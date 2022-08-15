# go-e-surplus
Steuerungssoftware, mit der man sein Fahrzeug direkt mit überschüssigem Strom der Solaranlage laden kann.

# Motivation

Um die bestehende Solaranlage intelligent zu nutzen, ist es sinnvoll, überschüssige Energie direkt in ein Elektrofahrzeug zu laden, statt sie ins Netz einzuspeisen. Mit dem go-e Charger steht eine Wallbox zur Verfügung, welche
- einphasig oder dreiphasig laden kann
- per API / MQTT steuerbar ist

Dadurch ist diese Wallbox gut geeignet, um ein die Funktion Überschussladen umzusetzen.

# Technisches Umfeld

- SolarEdge Solaranlage
- HomeAssistant Smart Home Steuerung

# Ziel

Die Wallbox soll so eingebunden werden dass der Benutzer mit dem Button auf der Wallbox zwischen 2 Lademodus wählen kann:
- Überschussladen (d.h. Steuerung lädt das Auto nur wenn überschüssige Leistung vom der PV-Anlage geliefert wird)
- Normales Laden (ohne Steuerung, wenn man das Auto laden muss und keine Zeit hat auf Sonne zu warten)





