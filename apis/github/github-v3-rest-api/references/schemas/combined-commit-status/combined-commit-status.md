# combined-commit-status

Combined Commit Status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | string | Yes |  |
| `statuses` | simple-commit-status[] | Yes |  |
| `sha` | string | Yes |  |
| `total_count` | integer | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `commit_url` | string (uri) | Yes |  |
| `url` | string (uri) | Yes |  |

