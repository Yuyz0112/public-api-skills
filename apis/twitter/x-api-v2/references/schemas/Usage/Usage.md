# Usage

Usage per client app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cap_reset_day` | integer (int32) | No | Number of days left for the Tweet cap to reset |
| `daily_client_app_usage` | ClientAppUsage[] | No | The daily usage breakdown for each Client Application a project |
| `daily_project_usage` | object | No | The daily usage breakdown for a project |
| `project_cap` | integer (int32) | No | Total number of Posts that can be read in this project per month |
| `project_id` | string (^[0-9]{1,19}$) | No | The unique identifier for this project |
| `project_usage` | integer (int32) | No | The number of Posts read in this project |

## Nested Fields

### `daily_project_usage`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `project_id` | integer (int32) | No | The unique identifier for this project |
| `usage` | UsageFields[] | No | The usage value |

