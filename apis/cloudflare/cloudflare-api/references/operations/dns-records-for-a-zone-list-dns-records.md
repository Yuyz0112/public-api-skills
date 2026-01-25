# GET /zones/{zone_id}/dns_records

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**List DNS Records**
**Operation ID:** `dns-records-for-a-zone-list-dns-records`

List, search, sort, and filter a zones' DNS records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |
| `name` | query | string | No |  |
| `name.exact` | query | string | No |  |
| `name.contains` | query | string | No |  |
| `name.startswith` | query | string | No |  |
| `name.endswith` | query | string | No |  |
| `type` | query | dns-records_type | No |  |
| `content` | query | string | No |  |
| `content.exact` | query | string | No |  |
| `content.contains` | query | string | No |  |
| `content.startswith` | query | string | No |  |
| `content.endswith` | query | string | No |  |
| `proxied` | query | dns-records_proxied | No |  |
| `match` | query | dns-records_match | No |  |
| `comment` | query | string | No |  |
| `comment.present` | query | string | No |  |
| `comment.absent` | query | string | No |  |
| `comment.exact` | query | string | No |  |
| `comment.contains` | query | string | No |  |
| `comment.startswith` | query | string | No |  |
| `comment.endswith` | query | string | No |  |
| `tag` | query | string | No |  |
| `tag.present` | query | string | No |  |
| `tag.absent` | query | string | No |  |
| `tag.exact` | query | string | No |  |
| `tag.contains` | query | string | No |  |
| `tag.startswith` | query | string | No |  |
| `tag.endswith` | query | string | No |  |
| `search` | query | dns-records_search | No |  |
| `tag_match` | query | dns-records_tag_match | No |  |
| `page` | query | dns-records_page | No |  |
| `per_page` | query | dns-records_per_page | No |  |
| `order` | query | dns-records_order | No |  |
| `direction` | query | dns-records_direction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List DNS Records response |
| 4XX | List DNS Records response failure |

**Success Response Schema:**

[dns-records_dns_response_collection](../schemas/dns-records/dns-records-dns-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
