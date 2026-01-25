# Dashboard

Details of a dashboard.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `automaticRefreshMs` | integer (int32) | No | The automatic refresh interval for the dashboard in milliseconds. |
| `description` | string | No |  |
| `editPermissions` | SharePermission[] | No | The details of any edit share permissions for the dashboard. |
| `id` | string | No | The ID of the dashboard. |
| `isFavourite` | boolean | No | Whether the dashboard is selected as a favorite by the user. |
| `isWritable` | boolean | No | Whether the current user has permission to edit the dashboard. |
| `name` | string | No | The name of the dashboard. |
| `owner` | any | No | The owner of the dashboard. |
| `popularity` | integer (int64) | No | The number of users who have this dashboard as a favorite. |
| `rank` | integer (int32) | No | The rank of this dashboard. |
| `self` | string (uri) | No | The URL of these dashboard details. |
| `sharePermissions` | SharePermission[] | No | The details of any view share permissions for the dashboard. |
| `systemDashboard` | boolean | No | Whether the current dashboard is system dashboard. |
| `view` | string | No | The URL of the dashboard. |

