# Vancouver AI Community Meetups Archive

Curated public archive of Vancouver AI Community meetup documentation.

## Scope

- Source: `content/projects/01-vancouver-ai-community/meetups`
- Generated: 2026-02-17
- Events indexed: 22
- Transcripts: 20
- Recaps: 17
- Years covered: 2024, 2025, 2026

## Structure

- `transcripts/` - canonical transcript markdown files
- `recaps/` - recap markdown files (if included)
- `index/documents.json` and `index/documents.csv` - per-document metadata
- `index/events.json` and `index/events.csv` - grouped per-event index

## Maintainer Update Workflow

This repository is published from the source knowledge-base repo (`kk-ai-ecosystem`).

```bash
# In kk-ai-ecosystem
python3 scripts/content-scripts/publish-meetup-archive.py \
  --target-repo "/path/to/vancouver-ai" \
  --push
```

The command will:

1. Regenerate the archive export package from canonical meetup source files
2. Mirror files into this repository clone
3. Commit changes if needed
4. Push updates to `origin/main`

## Notes

- Duplicate files with identical content are automatically deduplicated.
- This repo is intended as a shareable data source subset of the larger knowledge base.
