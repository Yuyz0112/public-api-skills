# POST /zones/{zone_id}/dns_records/scan

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Scan DNS Records**
**Operation ID:** `dns-records-for-a-zone-scan-dns-records`
⚠️ **Deprecated**

Scan for common DNS records on your domain and automatically add them to your zone. Useful if you haven't updated your nameservers yet.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scan DNS Records response |
| 4XX | Scan DNS Records response failure |

**Success Response Schema:**

[dns-records_dns_response_import_scan](../schemas/dns-records/dns-records-dns-response-import-scan.md)

## Security

- **api_token**
- **api_email**
- **api_key**
