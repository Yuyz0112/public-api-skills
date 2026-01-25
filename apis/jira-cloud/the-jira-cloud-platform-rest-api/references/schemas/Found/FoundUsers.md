# FoundUsers

The list of users found in a search, including header text (Showing X of Y matching users) and total of matched users.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `header` | string | No | Header text indicating the number of users in the response and the total number of users found in the search. |
| `total` | integer (int32) | No | The total number of users found in the search. |
| `users` | UserPickerUser[] | No |  |

