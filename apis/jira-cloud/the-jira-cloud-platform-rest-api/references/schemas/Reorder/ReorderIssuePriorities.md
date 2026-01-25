# ReorderIssuePriorities

Change the order of issue priorities.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | No | The ID of the priority. Required if `position` isn't provided. |
| `ids` | string[] | Yes | The list of issue IDs to be reordered. Cannot contain duplicates nor after ID. |
| `position` | string | No | The position for issue priorities to be moved to. Required if `after` isn't provided. |

