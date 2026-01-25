# intel_passive-dns-by-ip

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | No | Total results returned based on your search parameters. |
| `page` | number | No | Current page within paginated list of results. |
| `per_page` | number | No | Number of results per page of results. |
| `reverse_records` | object[] | No | Reverse DNS look-ups observed during the time period. |

## Nested Fields

### `reverse_records`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `first_seen` | string (date) | No | First seen date of the DNS record during the time period. |
| `hostname` | string | No | Hostname that the IP was observed resolving to. |
| `last_seen` | string (date) | No | Last seen date of the DNS record during the time period. |

