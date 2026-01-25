# ReorderIssueResolutionsRequest

Change the order of issue resolutions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | No | The ID of the resolution. Required if `position` isn't provided. |
| `ids` | string[] | Yes | The list of resolution IDs to be reordered. Cannot contain duplicates nor after ID. |
| `position` | string | No | The position for issue resolutions to be moved to. Required if `after` isn't provided. |

