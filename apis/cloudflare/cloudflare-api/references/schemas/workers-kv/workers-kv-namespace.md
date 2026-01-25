# workers-kv_namespace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [workers-kv_namespace_identifier](workers-kv-namespace-identifier.md) | Yes |  |
| `supports_url_encoding` | boolean | No | True if keys written on the URL will be URL-decoded before storing. For example, if set to "true", a key written on the URL as "%3F" will be stored as "?". |
| `title` | [workers-kv_namespace_title](workers-kv-namespace-title.md) | Yes |  |

