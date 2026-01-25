# GET /zones/{zone_id}/dns_records/scan/review

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**List Scanned DNS Records**
**Operation ID:** `dns-records-for-a-zone-review-dns-scan`

Retrieves the list of DNS records discovered up to this point by the asynchronous scan. These records are temporary until explicitly accepted or rejected via `POST /scan/review`. Additional records may be discovered by the scan later.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of discovered DNS records |
| 4XX | Scan review failure |

**Success Response Schema:**

[dns-records_dns_response_collection](../schemas/dns-records/dns-records-dns-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
