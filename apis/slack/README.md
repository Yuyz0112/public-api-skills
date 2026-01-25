# Slack API

[Slack Web API](https://api.slack.com/web) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `1.7.0`

## Usage

Point your AI agent to read `slack-web-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (1.4 MB) | 312 files |
| Resources | - | 56 index files |
| Operations | 253 (all in one) | 253 individual files |
| Schemas | 48 (all in one) | 48 individual files |

## Structure

```
slack-web-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 56 resource index files
    ├── operations/             # 253 operation detail files
    ├── schemas/                # 48 schema files
    └── authentication.md
```

## Regenerate

```bash
# Update and convert from Swagger 2.0
curl -o apis/slack/swagger.json https://raw.githubusercontent.com/slackapi/slack-api-specs/master/web-api/slack_web_openapi_v2.json
npx swagger2openapi apis/slack/swagger.json -o apis/slack/openapi.json --patch
rm apis/slack/swagger.json

# Regenerate
bun run generate:slack
```

## Source

- OpenAPI Spec: https://github.com/slackapi/slack-api-specs
- API Docs: https://api.slack.com/web
