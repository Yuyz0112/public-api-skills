# Jira Cloud API

[Jira Cloud Platform REST API](https://developer.atlassian.com/cloud/jira/platform/rest/v3/) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `v3`

> **Note:** This is for Jira Cloud only. Jira Server/Data Center does not have an official OpenAPI specification.

## Usage

Point your AI agent to read `the-jira-cloud-platform-rest-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (2.3 MB) | 1,684 files |
| Resources | - | 99 index files |
| Operations | 616 (all in one) | 616 individual files |
| Schemas | 967 (all in one) | 967 individual files |

## Structure

```
the-jira-cloud-platform-rest-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 99 resource index files
    ├── operations/             # 616 operation detail files
    ├── schemas/                # 967 schema files
    └── authentication.md
```

## Regenerate

```bash
# Update openapi.json from Atlassian
curl -o apis/jira-cloud/openapi.json "https://developer.atlassian.com/cloud/jira/platform/swagger-v3.v3.json"

# Regenerate
bun run generate:jira-cloud
```

## Source

- OpenAPI Spec: https://developer.atlassian.com/cloud/jira/platform/swagger-v3.v3.json
- API Docs: https://developer.atlassian.com/cloud/jira/platform/rest/v3/
