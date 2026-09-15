# Schwarze Pumpe Investor Radar v2

Repository-Ziel: `jhstb/projekt-Schwarze-Pumpe`

## Struktur
- `Schwarze_Pumpe_Investor_Radar_v2.html` – lokale Web-App
- `data/investors.json` – Investor-Stammdaten
- `data/activities.json` – Activity History
- `data/settings.json` – Projekt-/Funnel-Konfiguration
- `backup/Schwarze_Pumpe_Investor_Radar_v1.html` – unveränderte v1

## Nutzung
Die App funktioniert zunächst lokal im Browser. Änderungen werden lokal gespeichert.

## GitHub Sync
Die App kann `data/investors.json` und `data/activities.json` direkt über die GitHub Contents API lesen/schreiben.
Der Token wird nur zur Laufzeit eingegeben und nicht im HTML gespeichert.

Für einen produktiven Mehrbenutzerbetrieb ist ein OAuth-/Backend-Ansatz sicherer als ein direkt im Browser verwendeter Personal Access Token.
