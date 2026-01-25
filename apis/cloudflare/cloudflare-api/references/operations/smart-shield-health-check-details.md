# GET /zones/{zone_id}/smart_shield/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Health Check Details**
**Operation ID:** `smart-shield-health-check-details`

Fetch a single configured health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | smartshield_identifier | Yes |  |
| `zone_id` | path | smartshield_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Health Check Details response. |
| 4XX | Health Check Details response failure. |

**Success Response Schema:**

[smartshield_single_hc_response](../schemas/smartshield/smartshield-single-hc-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
