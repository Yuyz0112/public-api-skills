# page-shield_connection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added_at` | string (date-time) | Yes |  |
| `domain_reported_malicious` | boolean | No |  |
| `first_page_url` | string | No |  |
| `first_seen_at` | string (date-time) | Yes |  |
| `host` | string | Yes |  |
| `id` | [page-shield_id](page-shield-id.md) | Yes |  |
| `last_seen_at` | string (date-time) | Yes |  |
| `malicious_domain_categories` | string[] | No |  |
| `malicious_url_categories` | string[] | No |  |
| `page_urls` | string[] | No |  |
| `url` | string | Yes |  |
| `url_contains_cdn_cgi_path` | boolean | Yes |  |
| `url_reported_malicious` | boolean | No |  |

