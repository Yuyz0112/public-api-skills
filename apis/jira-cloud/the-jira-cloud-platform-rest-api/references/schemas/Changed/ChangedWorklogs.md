# ChangedWorklogs

List of changed worklogs.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `lastPage` | boolean | No |  |
| `nextPage` | string (uri) | No | The URL of the next list of changed worklogs. |
| `self` | string (uri) | No | The URL of this changed worklogs list. |
| `since` | integer (int64) | No | The datetime of the first worklog item in the list. |
| `until` | integer (int64) | No | The datetime of the last worklog item in the list. |
| `values` | ChangedWorklog[] | No | Changed worklog list. |

