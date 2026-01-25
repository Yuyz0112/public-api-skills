# content-symlink

An object describing a symlink

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: symlink | Yes |  |
| `target` | string | Yes |  |
| `size` | integer | Yes |  |
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `download_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `git` | string (uri) | Yes |  |
| `html` | string (uri) | Yes |  |
| `self` | string (uri) | Yes |  |

