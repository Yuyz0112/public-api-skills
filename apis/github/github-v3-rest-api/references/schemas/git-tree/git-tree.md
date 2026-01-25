# git-tree

The hierarchy between files in a Git repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | No |  |
| `truncated` | boolean | Yes |  |
| `tree` | object[] | Yes | Objects specifying a tree structure |

## Nested Fields

### `tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes |  |
| `mode` | string | Yes |  |
| `type` | string | Yes |  |
| `sha` | string | Yes |  |
| `size` | integer | No |  |
| `url` | string | No |  |

