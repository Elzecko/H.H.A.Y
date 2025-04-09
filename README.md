# H.H.A.Y
# Höhenmessgerät-Webseite

Diese Webseite zeigt in Echtzeit verschiedene Daten an, die mit einem mobilen Höhenmessgerät gesammelt oder online bezogen werden. Sie ist für die mobile Nutzung (Hochformat) optimiert und besteht aus mehreren Tabs mit spezifischen Informationen.

## Funktionen

- **Home:** Begrüßung und Beschreibung der Website
- **Wetter:** Anzeige der aktuellen Wetterlage anhand des aktuellen Standorts
- **Position:** Anzeige der aktuellen GPS-Koordinaten
- **Info:** Informationen zum Projekt und den Erstellern

## Technologien

- HTML5, CSS3, JavaScript
- [Geolocation API](https://developer.mozilla.org/de/docs/Web/API/Geolocation_API) zur Standortbestimmung
- [OpenWeatherMap API](https://openweathermap.org/api) zur Anzeige der Wetterdaten

## Installation

1. Repository klonen oder HTML-Datei herunterladen:
   ```bash
   git clone https://github.com/dein-benutzername/hoehenmess-webseite.git
   ```

2. Öffne die Datei `index.html` in einem mobilen Browser oder Desktop-Browser (mobilfreundlich).

## Vorbereitung zur Nutzung der Wetterdaten

1. Registriere dich bei [OpenWeatherMap](https://openweathermap.org/).
2. Erstelle einen kostenlosen API-Schlüssel.
3. Ersetze in der `index.html` den Platzhalter `DEIN_API_KEY` durch deinen Schlüssel:
   ```javascript
   const apiKey = "DEIN_API_KEY";
   ```

## Anforderungen

- Internetverbindung
- GPS-Funktionalität (z. B. auf Mobilgeräten)

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz veröffentlicht. Weitere Informationen siehe LICENSE-Datei.

## Autoren

- Dein Name
- ggf. Teammitglieder

## Vorschläge oder Fehler

Fehlerberichte und Verbesserungsvorschläge sind willkommen. Bitte erstelle ein Issue oder einen Pull Request.

