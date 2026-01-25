# webhook-secret-scanning-scan-completed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: completed | Yes |  |
| `type` | enum: backfill, custom-pattern-backfill, pattern-version-backfill | Yes | What type of scan was completed |
| `source` | enum: git, issues, pull-requests... | Yes | What type of content was scanned |
| `started_at` | string (date-time) | Yes | The time that the alert was resolved in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `completed_at` | string (date-time) | Yes | The time that the alert was resolved in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `secret_types` | string[] | No | List of patterns that were updated. This will be empty for normal backfill scans or custom pattern updates |
| `custom_pattern_name` | string | No | If the scan was triggered by a custom pattern update, this will be the name of the pattern that was updated |
| `custom_pattern_scope` | enum: repository, organization, enterprise | No | If the scan was triggered by a custom pattern update, this will be the scope of the pattern that was updated |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

