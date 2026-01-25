# GET /zones/{zone_id}/dnssec

**Resource:** [DNSSEC](../resources/DNSSEC.md)
**DNSSEC Details**
**Operation ID:** `dnssec-dnssec-details`

Details about DNSSEC status and configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dnssec_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | DNSSEC Details response. |
| 4XX | DNSSEC Details response failure. |

**Success Response Schema:**

[dnssec_dnssec_response_single](../schemas/dnssec/dnssec-dnssec-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
