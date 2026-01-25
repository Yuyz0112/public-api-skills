# POST /zones/{zone_id}/dns_records/scan/trigger

**Resource:** [DNS Records for a Zone](../resources/DNS-Records-for-a-Zone.md)
**Trigger DNS Record Scan**
**Operation ID:** `dns-records-for-a-zone-trigger-dns-scan`

Initiates an asynchronous scan for common DNS records on your domain. Note that this **does not** automatically add records to your zone. The scan runs in the background, and results can be reviewed later using the `/scan/review` endpoints. Useful if you haven't updated your nameservers yet.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-records_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Trigger DNS Records Scan Response |
| 4XX | Trigger DNS Records Scan response failure |

**Success Response Schema:**

[dns-records_dns_response_trigger_scan](../schemas/dns-records/dns-records-dns-response-trigger-scan.md)

## Security

- **api_token**
- **api_email**
- **api_key**
