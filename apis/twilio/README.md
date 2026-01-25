# Twilio API

[Twilio REST API](https://www.twilio.com/docs/usage/api) in [Agent Skills](https://agentskills.io/) format.

## Usage

Point your AI agent to read `twilio-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Operations | 197 | 197 individual files |
| Schemas | 148 | 148 individual files |

## Regenerate

```bash
curl -o apis/twilio/openapi.json "https://raw.githubusercontent.com/twilio/twilio-oai/main/spec/json/twilio_api_v2010.json"
bun run generate:twilio
```

## Source

- OpenAPI Spec: https://github.com/twilio/twilio-oai
- API Docs: https://www.twilio.com/docs/usage/api
