# LinkedIssue

The ID or key of a linked issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fields` | any | No | The fields associated with the issue. |
| `id` | string | No | The ID of an issue. Required if `key` isn't provided. |
| `key` | string | No | The key of an issue. Required if `id` isn't provided. |
| `self` | string (uri) | No | The URL of the issue. |

