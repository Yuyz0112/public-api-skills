# content-file

Content File

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: file | Yes |  |
| `encoding` | string | Yes |  |
| `size` | integer | Yes |  |
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `content` | string | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `download_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |
| `target` | string | No |  |
| `submodule_git_url` | string | No |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `git` | string (uri) | Yes |  |
| `html` | string (uri) | Yes |  |
| `self` | string (uri) | Yes |  |

