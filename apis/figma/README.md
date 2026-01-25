# Figma API

[Figma REST API](https://www.figma.com/developers/api) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `figma-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 46 | 46 individual files |
| Schemas | 223 | 223 individual files |

## Regenerate

```bash
curl -o apis/figma/openapi.yaml "https://raw.githubusercontent.com/figma/rest-api-spec/main/openapi/openapi.yaml"
bun run generate:figma
```

## Source

- OpenAPI Spec: https://github.com/figma/rest-api-spec
- API Docs: https://www.figma.com/developers/api
