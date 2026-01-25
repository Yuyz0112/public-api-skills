# workers_version-item-short

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Unique identifier for the version. |
| `metadata` | object | No |  |
| `number` | number | No | Sequential version number. |

## Nested Fields

### `metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author_email` | string | No | Email of the user who created the version. |
| `author_id` | string | No | Identifier of the user who created the version. |
| `created_on` | string | No | When the version was created. |
| `hasPreview` | boolean | No | Whether the version can be previewed. |
| `modified_on` | string | No | When the version was last modified. |
| `source` | enum: unknown, api, wrangler... | No | The source of the version upload. |

