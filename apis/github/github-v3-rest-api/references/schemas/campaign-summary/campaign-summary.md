# campaign-summary

The campaign metadata and alert stats.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `number` | integer | Yes | The number of the newly created campaign |
| `created_at` | string (date-time) | Yes | The date and time the campaign was created, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `updated_at` | string (date-time) | Yes | The date and time the campaign was last updated, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `name` | string | No | The campaign name |
| `description` | string | Yes | The campaign description |
| `managers` | simple-user[] | Yes | The campaign managers |
| `team_managers` | team[] | No | The campaign team managers |
| `published_at` | string (date-time) | No | The date and time the campaign was published, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `ends_at` | string (date-time) | Yes | The date and time the campaign has ended, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `closed_at` | string (date-time) | No | The date and time the campaign was closed, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. Will be null if the campaign is still open. |
| `state` | [campaign-state](campaign-state.md) | Yes |  |
| `contact_link` | string (uri) | Yes | The contact link of the campaign. |
| `alert_stats` | object | No |  |

## Nested Fields

### `alert_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `open_count` | integer | Yes | The number of open alerts |
| `closed_count` | integer | Yes | The number of closed alerts |
| `in_progress_count` | integer | Yes | The number of in-progress alerts |

