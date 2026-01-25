# DELETE /zones/{zone_id}/dnssec

**Resource:** [DNSSEC](../resources/DNSSEC.md)
**Delete DNSSEC records**
**Operation ID:** `dnssec-delete-dnssec-records`

Delete DNSSEC.

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
| 200 | Delete DNSSEC records response. |
| 4XX | Delete DNSSEC records response failure. |

**Success Response Schema:**

[dnssec_delete_dnssec_response_single](../schemas/dnssec/dnssec-delete-dnssec-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
