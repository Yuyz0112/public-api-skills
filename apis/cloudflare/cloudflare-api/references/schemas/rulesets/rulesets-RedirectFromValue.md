# rulesets_RedirectFromValue

A redirect based on the request properties.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `preserve_query_string` | boolean | No | Whether to keep the query string of the original request. |
| `status_code` | enum: 301, 302, 303... | No | The status code to use for the redirect. |
| `target_url` | object | Yes | A URL to redirect the request to. |

## Nested Fields

### `target_url`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expression` | string | No | An expression that evaluates to a URL to redirect the request to. |
| `value` | string | No | A URL to redirect the request to. |

