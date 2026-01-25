# GET /zones/{zone_id}/dns_records/usage

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Get DNS Record Usage**
**Operation ID:** `dns-records-for-a-zone-get-usage`

Get the current DNS record usage for a zone, including the number of records and the quota limit.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get DNS Record Usage response |
| 4XX | Get DNS Record Usage response failure |

**Success Response Schema:**

[dns-records_dns_response_zone_usage](../schemas/dns-records/dns-records-dns-response-zone-usage.md)

## Security

- **api_token**
- **api_email**
- **api_key**
