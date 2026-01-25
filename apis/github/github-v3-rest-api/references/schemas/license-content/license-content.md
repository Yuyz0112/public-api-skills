# license-content

License Content

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `sha` | string | Yes |  |
| `size` | integer | Yes |  |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `download_url` | string (uri) | Yes |  |
| `type` | string | Yes |  |
| `content` | string | Yes |  |
| `encoding` | string | Yes |  |
| `_links` | object | Yes |  |
| `license` | [nullable-license-simple](nullable-license-simple.md) | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `git` | string (uri) | Yes |  |
| `html` | string (uri) | Yes |  |
| `self` | string (uri) | Yes |  |

