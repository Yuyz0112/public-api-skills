# AnalyticsUserFilterConditions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at_start` | string (date-time) | No | The start of the date range to search |
| `created_at_end` | string (date-time) | No | The end of the date range to search |
| `team_ids` | string[] | No | An array of team IDs. Only users belonging to these teams will be included in results. |
| `user_ids` | string[] | No | An array of user IDs. Only these users will be included in results. |
| `role_ids` | string[] | No | An array of role IDs. Only users with these roles will be included in results. |

