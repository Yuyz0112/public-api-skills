# Cloudflare API

[Cloudflare API](https://developers.cloudflare.com/api/) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `cloudflare-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 2,531 | 2,531 individual files |
| Schemas | 5,231 | 5,231 individual files |

## Regenerate

```bash
curl -o apis/cloudflare/openapi.json "https://raw.githubusercontent.com/cloudflare/api-schemas/main/openapi.json"
bun run generate:cloudflare
```

## Source

- OpenAPI Spec: https://github.com/cloudflare/api-schemas
- API Docs: https://developers.cloudflare.com/api/
