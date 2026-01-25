# intel_miscategorization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content_adds` | integer[] | No | Content category IDs to add. |
| `content_removes` | integer[] | No | Content category IDs to remove. |
| `indicator_type` | enum: domain, ipv4, ipv6... | No |  |
| `ip` | string | No | Provide only if indicator_type is `ipv4` or `ipv6`. |
| `security_adds` | integer[] | No | Security category IDs to add. |
| `security_removes` | integer[] | No | Security category IDs to remove. |
| `url` | string | No | Provide only if indicator_type is `domain` or `url`. Example if indicator_type is `domain`: `example.com`. Example if indicator_type is `url`: `https://example.com/news/`. |

