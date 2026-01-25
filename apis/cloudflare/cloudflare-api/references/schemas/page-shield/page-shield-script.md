# page-shield_script

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added_at` | string (date-time) | Yes |  |
| `cryptomining_score` | [page-shield_cryptomining_score](page-shield-cryptomining-score.md) | No |  |
| `dataflow_score` | [page-shield_dataflow_score](page-shield-dataflow-score.md) | No |  |
| `domain_reported_malicious` | boolean | No |  |
| `fetched_at` | [page-shield_fetched_at](page-shield-fetched-at.md) | No |  |
| `first_page_url` | string | No |  |
| `first_seen_at` | string (date-time) | Yes |  |
| `hash` | [page-shield_hash](page-shield-hash.md) | No |  |
| `host` | string | Yes |  |
| `id` | [page-shield_id](page-shield-id.md) | Yes |  |
| `js_integrity_score` | [page-shield_js_integrity_score](page-shield-js-integrity-score.md) | No |  |
| `last_seen_at` | string (date-time) | Yes |  |
| `magecart_score` | [page-shield_magecart_score](page-shield-magecart-score.md) | No |  |
| `malicious_domain_categories` | string[] | No |  |
| `malicious_url_categories` | string[] | No |  |
| `malware_score` | [page-shield_malware_score](page-shield-malware-score.md) | No |  |
| `obfuscation_score` | [page-shield_obfuscation_score](page-shield-obfuscation-score.md) | No |  |
| `page_urls` | string[] | No |  |
| `url` | string | Yes |  |
| `url_contains_cdn_cgi_path` | boolean | Yes |  |
| `url_reported_malicious` | boolean | No |  |

