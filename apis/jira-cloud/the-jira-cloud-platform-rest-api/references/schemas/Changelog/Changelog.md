# Changelog

A log of changes made to issue fields. Changelogs related to workflow associations are currently being deprecated.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | any | No | The user who made the change. |
| `created` | string (date-time) | No | The date on which the change took place. |
| `historyMetadata` | any | No | The history metadata associated with the changed. |
| `id` | string | No | The ID of the changelog. |
| `items` | ChangeDetails[] | No | The list of items changed. |

