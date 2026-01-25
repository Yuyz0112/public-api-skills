# POST /zones/{zone_id}/smart_shield/healthchecks

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Create Health Check**
**Operation ID:** `smart-shield-create-health-check`

Create a new health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | smartshield_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [smartshield_query_healthcheck](../schemas/smartshield/smartshield-query-healthcheck.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Health Check response. |
| 4XX | Create Health Check response failure. |

**Success Response Schema:**

[smartshield_single_hc_response](../schemas/smartshield/smartshield-single-hc-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
