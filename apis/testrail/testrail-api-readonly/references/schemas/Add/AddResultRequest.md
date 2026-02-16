# AddResultRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status_id` | integer | No | Default system statuses: 1 Passed, 2 Blocked, 4 Retest, 5 Failed. |
| `comment` | string | No |  |
| `version` | string | No |  |
| `elapsed` | string | No | Examples: 30s, 1m 45s, 2h. |
| `defects` | string | No | Comma-separated references, for example BUG-123,BUG-456. |
| `assignedto_id` | integer | No |  |
| `custom_step_results` | ResultStep[] | No |  |

