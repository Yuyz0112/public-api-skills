# PublishedVariableCollection

A grouping of related Variable objects each with the same modes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of this variable collection. |
| `subscribed_id` | string | Yes | The ID of the variable collection that is used by subscribing files. This ID changes every time the variable collection is modified and published. |
| `name` | string | Yes | The name of this variable collection. |
| `key` | string | Yes | The key of this variable collection. |
| `updatedAt` | string (date-time) | Yes | The UTC ISO 8601 time at which the variable collection was last updated.

This timestamp will change any time a variable in the collection is changed. |

