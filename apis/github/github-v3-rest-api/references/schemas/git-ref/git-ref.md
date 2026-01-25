# git-ref

Git references within a repository

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | string | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `object` | object | Yes |  |

## Nested Fields

### `object`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `sha` | string | Yes | SHA for the reference |
| `url` | string (uri) | Yes |  |

