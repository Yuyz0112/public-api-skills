# PATCH /zones/{zone_id}/dnssec

**Resource:** [DNSSEC](../resources/DNSSEC.md)
**Edit DNSSEC Status**
**Operation ID:** `dnssec-edit-dnssec-status`

Enable or disable DNSSEC.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dnssec_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit DNSSEC Status response. |
| 4XX | Edit DNSSEC Status response failure. |

**Success Response Schema:**

[dnssec_dnssec_response_single](../schemas/dnssec/dnssec-dnssec-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
