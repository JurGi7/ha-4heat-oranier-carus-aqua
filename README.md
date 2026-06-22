# Oranier Carus Aqua 2.0 - Home Assistant Custom Integration

Eine benutzerdefinierte Home Assistant Integration zur lokalen Steuerung und Überwachung des wassergeführten Pelletofens **Oranier Carus Aqua 2.0** (sowie anderer Öfen, die auf der **4Heat-Plattform** basieren) über das lokale Netzwerk (TCP-Sockets).

Diese Integration läuft vollständig lokal, benötigt keine Cloud-Anbindung und fragt die Daten direkt vom WLAN-Modul des Ofens ab.

## Funktionen

- 📊 **Umfangreiche Sensorik:** Auslesen von Temperaturen (Kessel, Pufferspeicher, Raumtemperatur, Abgastemperatur), Betriebszuständen, Fehlermeldungen und Schneckenlaufzeiten.
- 🎛️ **Steuerung:** Ofen remote ein- und ausschalten (über die bereitgestellten Switches).
- 🔄 **Echtzeit-Aktualisierung:** Automatisches Polling der Ofendaten über einen zentralen Daten-Coordinator.
- 🔒 **100% Lokal:** Keine Verbindung zu externen Servern erforderlich.

## Installation

### Methode 1: Über HACS (Empfohlen)

Da es sich um ein benutzerdefiniertes Repository handelt, kannst du es wie folgt zu HACS hinzufügen:

1. Navigiere in Home Assistant zu **HACS** -> **Integrationen**.
2. Klicke oben rechts auf die drei Punkte (`...`) und wähle **Benutzerdefinierte Repositories**.
3. Füge die URL deines Repositories ein:
   ```text
   [https://github.com/JurGi7/ha-4heat-oranier-carus-aqua](https://github.com/JurGi7/ha-4heat-oranier-carus-aqua)

## Danksagung & Credits 🙏

Diese Integration basiert ursprünglich auf der großartigen Arbeit von **@zaubererty** und seinem Repository [homeassistant-4heat](https://github.com/zaubererty/homeassistant-4heat). Ein herzliches Dankeschön an ihn für das Erstellen der Protokoll-Grundlagen und der initialen Codebasis, auf der diese spezifische Anpassung für den Oranier Carus Aqua 2.0 aufbauen konnte.

## Haftungsausschluss & Lizenz

Dies ist eine unabhängige, von der Community entwickelte Integration. Sie steht in keiner Verbindung zu der firma Oranier oder den Entwicklern der originalen 4Heat-App. Die Nutzung erfolgt auf eigene Gefahr.

Dieses Projekt ist unter den Bedingungen der **MIT-Lizenz** lizenziert – basierend auf der ursprünglichen Lizenz des Upstream-Repositories.
