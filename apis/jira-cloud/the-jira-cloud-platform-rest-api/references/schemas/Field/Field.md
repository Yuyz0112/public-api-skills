# Field

Details of a field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `contextsCount` | integer (int64) | No | Number of contexts where the field is used. |
| `description` | string | No | The description of the field. |
| `id` | string | Yes | The ID of the field. |
| `isLocked` | boolean | No | Whether the field is locked. |
| `isUnscreenable` | boolean | No | Whether the field is shown on screen or not. |
| `key` | string | No | The key of the field. |
| `lastUsed` | [FieldLastUsed](FieldLastUsed.md) | No |  |
| `name` | string | Yes | The name of the field. |
| `projectsCount` | integer (int64) | No | Number of projects where the field is used. |
| `schema` | [JsonTypeBean](JsonTypeBean.md) | Yes |  |
| `screensCount` | integer (int64) | No | Number of screens where the field is used. |
| `searcherKey` | string | No | The searcher key of the field. Returned for custom fields. |
| `stableId` | string | No | The stable ID of the field. |
| `typeDisplayName` | string | No | The display name of the field type |

