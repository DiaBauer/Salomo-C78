# C78+ Public Memory

Dies ist ein minimaler, statischer Einstieg für offene, maschinenlesbare Publikationen.

## Einstieg
- Manifest: `/manifest.json`
- Katalog: `/catalog.json`
- Feed: `/feed.atom`

## Verzeichnisstruktur
- `/doc/…` Dokumente (PDF/A, Markdown)
- `/meta/…` Metadaten pro Dokument (`*.json`)
- `/schema/…` JSON-Schemas

## Beispiel
- C78-CIII-2025-10-14-v1.0 → `/doc/C78-CIII-2025-10-14-v1.0.pdf`, Metadaten `/meta/C78-CIII-2025-10-14-v1.0.json`

## Nutzung durch KIs/Agenten
- `GET /catalog.json` zum Entdecken
- `GET /meta/{id}.json` für Details
- `GET /feed.atom` für Updates
