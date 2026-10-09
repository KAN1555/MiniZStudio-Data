# MiniZStudio-Data

Public, read-only distribution repository for MiniZStudio. Source code and user-local data remain in separate repositories or on individual PCs.

## Data
- `catalog.json`: v1 manifest with entries for layouts, regulations, vehicles, settings and lapRecords.
- `layouts/`: administrator-approved course layouts
- `regulations/`, `vehicles/`: publicly distributable presets
- `settings/`: generic analysis defaults, never per-user preferences
- `lap-records/`: deliberately published, consent-approved *anonymous* lap results
- `schemas/`: JSON Schema contracts
- `versions/`: future release metadata

Entries in the manifest must refer only to reviewed JSON files under their matching directories. An empty collection means no public data is available yet.

**Do not publish:** names, account identifiers, contact details, raw controller traces, IP addresses, private telemetry, authentication tokens, or local lap histories. A lap record must be reviewed for publication approval; a client must not upload it automatically. Publication workflow requires administrator review.
