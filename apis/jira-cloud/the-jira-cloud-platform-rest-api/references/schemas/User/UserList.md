# UserList

A paginated list of users sharing the filter. This includes users that are members of the groups or can browse the projects that the filter is shared with.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `end-index` | integer (int32) | No | The index of the last item returned on the page. |
| `items` | User[] | No | The list of items. |
| `max-results` | integer (int32) | No | The maximum number of results that could be on the page. |
| `size` | integer (int32) | No | The number of items on the page. |
| `start-index` | integer (int32) | No | The index of the first item returned on the page. |

