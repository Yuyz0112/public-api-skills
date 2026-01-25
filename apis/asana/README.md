# Asana API

[Asana REST API](https://developers.asana.com/docs) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `asana/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 217 | 217 individual files |
| Schemas | 244 | 244 individual files |

## Regenerate

```bash
curl -o apis/asana/openapi.yaml "https://raw.githubusercontent.com/Asana/openapi/refs/heads/master/defs/asana_oas.yaml"
bun run generate:asana
```

## Source

- OpenAPI Spec: https://github.com/Asana/openapi
- API Docs: https://developers.asana.com/docs
