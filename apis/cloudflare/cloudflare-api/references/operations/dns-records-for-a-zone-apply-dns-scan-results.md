# POST /zones/{zone_id}/dns_records/scan/review

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Review Scanned DNS Records**
**Operation ID:** `dns-records-for-a-zone-apply-dns-scan-results`

Accept or reject DNS records found by the DNS records scan. Accepted records will be permanently added to the zone, while rejected records will be permanently deleted.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-records_dns-request-review-scan-object](../schemas/dns-records/dns-records-dns-request-review-scan-object.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Records reviewed successfully |
| 4XX | Review failure |

**Success Response Schema:**

[dns-records_dns_response_review_scan](../schemas/dns-records/dns-records-dns-response-review-scan.md)

## Security

- **api_token**
- **api_email**
- **api_key**
