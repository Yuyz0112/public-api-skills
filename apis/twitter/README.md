# Twitter (X) API

[X API v2](https://developer.x.com/en/docs/twitter-api) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `x-api-v2/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 192 | 192 individual files |
| Schemas | 393 | 393 individual files |

## Regenerate

```bash
curl -o apis/twitter/openapi.json "https://api.twitter.com/2/openapi.json"
bun run generate:twitter
```

## Source

- OpenAPI Spec: https://api.twitter.com/2/openapi.json
- API Docs: https://developer.x.com/en/docs/twitter-api
