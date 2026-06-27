# Veloverkehr Zürich

Visualisierung der Velozähler-Daten der Stadt Zürich.

## Datenquelle

Die Daten stammen vom Tiefbauamt der Stadt Zürich über das offene Datenportal
[data.stadt-zuerich.ch](https://data.stadt-zuerich.ch), Lizenz CC0 (frei nutzbar,
keine Anmeldung oder API-Schlüssel nötig). Die App lädt bei jedem Aufruf die
aktuellen Zähldaten direkt von dieser Schnittstelle — es werden keine
Test-/Mock-Daten verwendet.

Fällt die Schnittstelle aus, zeigt die App eine Hinweismeldung statt
abzustürzen.

## Anwendung öffnen

Die eigentliche Visualisierung ist **nicht** das Standard-Vite-Setup, sondern
die Datei:

```
Veloverkehr Zürich.dc.html
```

Diese Datei direkt im Browser öffnen, um die Anwendung zu sehen.

Das übrige Vite/React-Projekt (`src/`, `npm run dev`) ist ein leeres
Standard-Gerüst und enthält nicht die fertige Anwendung.

## Hinweis

Keine API-Schlüssel oder Zugangsdaten erforderlich. Bei zukünftigen Erweiterungen
mit Zugangsdaten: eine `.env`-Datei verwenden und in `.gitignore` aufnehmen.
