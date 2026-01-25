# code-search-result-item

Code Search Result Item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `path` | string | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `git_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `score` | number | Yes |  |
| `file_size` | integer | No |  |
| `language` | string | No |  |
| `last_modified_at` | string (date-time) | No |  |
| `line_numbers` | string[] | No |  |
| `text_matches` | [search-result-text-matches](search-result-text-matches.md) | No |  |

