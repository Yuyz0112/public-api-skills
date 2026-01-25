# PagerDuty API

[PagerDuty REST API](https://developer.pagerduty.com/api-reference/) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `pagerduty-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 390 | 390 individual files |
| Schemas | 244 | 244 individual files |

## Regenerate

```bash
curl -o apis/pagerduty/openapi.json "https://raw.githubusercontent.com/PagerDuty/api-schema/main/reference/REST/openapiv3.json"
bun run generate:pagerduty
```

## Source

- OpenAPI Spec: https://github.com/PagerDuty/api-schema
- API Docs: https://developer.pagerduty.com/api-reference/
