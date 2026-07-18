# End of War — Kriegs-Konfiguration (Live-Ops)

Öffentliche Live-Konfiguration für das Community-Meta „The Great War" von **TD End of War** (Steam).

- `war_config.json` — append-only JSON-Journal. Bestehende Einträge werden NIE geändert oder gelöscht; jede Veröffentlichung hängt genau einen neuen Eintrag mit `revision = max+1` an.
- Der Spiel-Client lädt diese Datei beim Start, prüft alle Werte gegen harte Grenzen (ungültige Einträge werden verworfen, nicht korrigiert) und behält den letzten gültigen Stand, falls die Datei nicht erreichbar ist.
- Es liegen hier ausschließlich Balancing-Zahlen und Ticker-Texte — keine Geheimnisse, keine persönlichen Daten.

Schema und Clamp-Tabelle: siehe `development/kriegszentrale/war_config_schema.md` im Spiel-Repository. Bearbeitung über das Kriegszentrale-Werkzeug (HTML) oder von Hand per Pull Request/Commit.
