# community-profile

Community Profile

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `health_percentage` | integer | Yes |  |
| `description` | string | Yes |  |
| `documentation` | string | Yes |  |
| `files` | object | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `content_reports_enabled` | boolean | No |  |

## Nested Fields

### `files`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code_of_conduct` | [nullable-code-of-conduct-simple](nullable-code-of-conduct-simple.md) | Yes |  |
| `code_of_conduct_file` | [nullable-community-health-file](nullable-community-health-file.md) | Yes |  |
| `license` | [nullable-license-simple](nullable-license-simple.md) | Yes |  |
| `contributing` | [nullable-community-health-file](nullable-community-health-file.md) | Yes |  |
| `readme` | [nullable-community-health-file](nullable-community-health-file.md) | Yes |  |
| `issue_template` | [nullable-community-health-file](nullable-community-health-file.md) | Yes |  |
| `pull_request_template` | [nullable-community-health-file](nullable-community-health-file.md) | Yes |  |

