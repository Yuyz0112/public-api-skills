# GitLab API

[GitLab REST API](https://docs.gitlab.com/ee/api/) in [Agent Skills](https://agentskills.io/) format.

**API Version:** `v4`

## Usage

Point your AI agent to read `gitlab-rest-api/SKILL.md` as the entry point.

## Stats

| Metric | Original | Agent Skills |
|--------|----------|--------------|
| Source | 1 file (3.3 MB) | 2,877 files |
| Resources | - | 176 index files |
| Operations | 1,837 (all in one) | 1,837 individual files |
| Schemas | 454 (all in one) | 454 individual files |

## Structure

```
gitlab-rest-api/
├── SKILL.md                    # Entry point
└── references/
    ├── resources/              # 176 resource index files
    ├── operations/             # 1,837 operation detail files
    ├── schemas/                # 454 schema files
    └── authentication.md
```

## Regenerate

```bash
# Replace spec file (if needed)
cp gitlab_v3.yaml apis/gitlab/openapi.yaml

# Regenerate
bun run generate:gitlab
```

## Source

- OpenAPI Spec: `gitlab_v3.yaml` (local file)
- API Docs: https://docs.gitlab.com/ee/api/
