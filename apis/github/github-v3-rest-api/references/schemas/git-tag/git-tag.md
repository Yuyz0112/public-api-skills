# git-tag

Metadata for a Git tag

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `node_id` | string | Yes |  |
| `tag` | string | Yes | Name of the tag |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the tag |
| `message` | string | Yes | Message describing the purpose of the tag |
| `tagger` | object | Yes |  |
| `object` | object | Yes |  |
| `verification` | [verification](verification.md) | No |  |

## Nested Fields

### `tagger`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | Yes |  |
| `email` | string | Yes |  |
| `name` | string | Yes |  |

### `object`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `type` | string | Yes |  |
| `url` | string (uri) | Yes |  |

