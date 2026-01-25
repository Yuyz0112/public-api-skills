# GitHub API

[GitHub REST API](https://docs.github.com/en/rest) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `1.1.4`

## Usage

Point your AI agent to read `github-v3-rest-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (11 MB) | 2,026 files |
| Resources | - | 43 index files |
| Operations | 1,078 (all in one) | 1,078 individual files |
| Schemas | 904 (all in one) | 904 individual files |

## Structure

```
github-v3-rest-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 43 resource index files
    ├── operations/             # 1,078 operation detail files
    ├── schemas/                # 904 schema files
    └── authentication.md
```

## Regenerate

```bash
# Update openapi.json from GitHub
curl -o apis/github/openapi.json https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json

# Regenerate
bun run generate:github
```

## Source

- OpenAPI Spec: https://github.com/github/rest-api-description
- API Docs: https://docs.github.com/en/rest
