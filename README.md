# Sermon Research Library

Private structured research layer for the Sermon Development System (SDS).

## Architecture

```text
Google Drive source archive
        ↓
source cards / issue dossiers / passage + topic indexes
        ↓
SDS EXEGETICAL_SOURCE_LEDGER
        ↓
project adjudication → sermon architecture → manuscript
```

## Governing distinction

- **Google Drive** stores original source files.
- **This repository** stores structured, recoverable research metadata and reusable findings.
- **sermon-dev-sys** governs how evidence is evaluated and used.

This repository is not an ebook archive. Do not commit copyrighted books, journal PDFs, scans, or large source corpora here.

## Core principles

1. Retrieve by material exegetical question, not indiscriminate bulk ingestion.
2. Preserve page/location traceability back to the original source.
3. Treat source competence as claim-relative.
4. Record dependence between secondary sources.
5. Preserve significant scholarly disagreement rather than flattening it into one answer.
6. Keep project adjudications distinct from source evidence.
7. Grow the library just in time from actual sermon and research projects.

## Layout

```text
CONFIG.yaml
LIBRARY-INDEX.yaml
RETRIEVAL-PROTOCOL.md
schemas/
templates/
sources/
passages/
issues/
adjudications/
```

See `RETRIEVAL-PROTOCOL.md` for the operating workflow.
