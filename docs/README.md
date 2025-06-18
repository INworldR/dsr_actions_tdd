# Dokumentation

Dieser Ordner enthält die Sphinx-Dokumentation für das Calculator-Projekt.

## Dokumentation erstellen

Um die HTML-Dokumentation zu erstellen:

```bash
# Virtuelle Umgebung aktivieren
source ../venv/bin/activate

# HTML-Dokumentation erstellen
make html
```

Die generierten HTML-Dateien befinden sich im `_build/html/`-Ordner.

## Dokumentation anzeigen

Öffnen Sie `_build/html/index.html` in Ihrem Browser, um die Dokumentation anzuzeigen.

## Struktur

- `index.rst` - Hauptseite der Dokumentation
- `api.rst` - API-Referenz für die Calculator-Klasse
- `conf.py` - Sphinx-Konfiguration
- `_build/` - Generierte Dokumentationsdateien (wird ignoriert von Git)

## Theme

Die Dokumentation verwendet das "Read the Docs" Theme für ein modernes, responsives Design.
