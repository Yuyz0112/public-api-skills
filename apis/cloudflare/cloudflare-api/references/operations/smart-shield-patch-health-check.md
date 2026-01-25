# PATCH /zones/{zone_id}/smart_shield/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Patch Health Check**
**Operation ID:** `smart-shield-patch-health-check`

Patch a configured health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | smartshield_identifier | Yes |  |
| `zone_id` | path | smartshield_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [smartshield_query_healthcheck](../schemas/smartshield/smartshield-query-healthcheck.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Health Check response. |
| 4XX | Patch Health Check response failure. |

**Success Response Schema:**

[smartshield_single_hc_response](../schemas/smartshield/smartshield-single-hc-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
