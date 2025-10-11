# Endpoints

These are JSON Server-style endpoints used when API is enabled. Base URL: value stored in `localStorage['rpl.apiBase']`.

- `/applicants` (GET/POST)
- `/evidence` (GET/POST)
- `/decisions` (GET/POST)
- `/audit` (GET/POST)
- `/settings` (GET/PUT) with single row `id=1`
- `/actions/upsert` (POST) — custom action for GPT integrations

## Example cURL
```bash
curl -X POST "$BASE/audit" \
  -H 'Content-Type: application/json' \
  -d '{"at":"2025-10-10T12:00:00Z","userRole":"asesor","action":"review","detail":"OK"}'
```
