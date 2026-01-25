# content-tree

Content Tree

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `size` | integer | Yes |  |
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `sha` | string | Yes |  |
| `content` | string | No |  |
| `url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `download_url` | string (uri) | Yes |  |
| `entries` | object[] | No |  |
| `encoding` | string | No |  |
| `_links` | object | Yes |  |

## Nested Fields

### `entries`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `size` | integer | Yes |  |
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `download_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |

#### `entries._links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `git` | string (uri) | Yes |  |
| `html` | string (uri) | Yes |  |
| `self` | string (uri) | Yes |  |

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `git` | string (uri) | Yes |  |
| `html` | string (uri) | Yes |  |
| `self` | string (uri) | Yes |  |

