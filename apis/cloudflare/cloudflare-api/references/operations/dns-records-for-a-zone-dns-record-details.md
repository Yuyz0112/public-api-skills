# GET /zones/{zone_id}/dns_records/{dns_record_id}

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**DNS Record Details**
**Operation ID:** `dns-records-for-a-zone-dns-record-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_record_id` | path | dns-records_identifier | Yes |  |
| `zone_id` | path | dns-records_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DNS Record Details response |
| 4XX | DNS Record Details response failure |

**Success Response Schema:**

[dns-records_dns_response_single](../schemas/dns-records/dns-records-dns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
