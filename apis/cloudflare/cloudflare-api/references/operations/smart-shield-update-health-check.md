# PUT /zones/{zone_id}/smart_shield/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Update Health Check**
**Operation ID:** `smart-shield-update-health-check`

Update a configured health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | smartshield_identifier | Yes |  |
| `zone_id` | path | smartshield_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [smartshield_single_hc_response](../schemas/smartshield/smartshield-single-hc-response.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Health Check response. |
| 4XX | Update Health Check response failure. |

**Success Response Schema:**

[smartshield_single_hc_response](../schemas/smartshield/smartshield-single-hc-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
