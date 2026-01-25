# lists_item_redirect

The definition of the redirect.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `include_subdomains` | boolean | No |  |
| `preserve_path_suffix` | boolean | No |  |
| `preserve_query_string` | boolean | No |  |
| `source_url` | string | Yes |  |
| `status_code` | enum: 301, 302, 307... | No |  |
| `subpath_matching` | boolean | No |  |
| `target_url` | string | Yes |  |

