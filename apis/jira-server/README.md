# Jira Server API

[Jira Server/Data Center REST API](https://docs.atlassian.com/software/jira/docs/api/REST/8.13.17/) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `8.13.17`

> **Note:** This is for Jira Server/Data Center. For Jira Cloud, see the `jira-cloud` directory.

## Usage

Point your AI agent to read `jira-8-13-17/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (268 KB) | 376 files |
| Resources | - | 58 index files |
| Operations | 316 (all in one) | 316 individual files |
| Schemas | 0 (all in one) | 0 individual files |

## Structure

```
jira-8-13-17/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 58 resource index files
    ├── operations/             # 362 operation detail files
    └── schemas/                # 0 schema files
```

## Regenerate

```bash
# Regenerate
bun run generate:jira-server
```

## Source

- OpenAPI Spec: Local `openapi.json`
- API Docs: https://docs.atlassian.com/software/jira/docs/api/REST/8.13.17/
