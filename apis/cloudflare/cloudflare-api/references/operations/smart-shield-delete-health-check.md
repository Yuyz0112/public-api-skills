# DELETE /zones/{zone_id}/smart_shield/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Delete Health Check**
**Operation ID:** `smart-shield-delete-health-check`

Delete a health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | smartshield_identifier | Yes |  |
| `zone_id` | path | smartshield_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Health Check response. |
| 4XX | Delete Health Check response failure. |

**Success Response Schema:**

[smartshield_single_hc_id_response](../schemas/smartshield/smartshield-single-hc-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
