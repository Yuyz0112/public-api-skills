# page-shield_cookie

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `domain_attribute` | string | No |  |
| `expires_attribute` | string (date-time) | No |  |
| `first_seen_at` | string (date-time) | Yes |  |
| `host` | string | Yes |  |
| `http_only_attribute` | boolean | No |  |
| `id` | [page-shield_id](page-shield-id.md) | Yes |  |
| `last_seen_at` | string (date-time) | Yes |  |
| `max_age_attribute` | integer | No |  |
| `name` | string | Yes |  |
| `page_urls` | string[] | No |  |
| `path_attribute` | string | No |  |
| `same_site_attribute` | enum: lax, strict, none | No |  |
| `secure_attribute` | boolean | No |  |
| `type` | enum: first_party, unknown | Yes |  |

