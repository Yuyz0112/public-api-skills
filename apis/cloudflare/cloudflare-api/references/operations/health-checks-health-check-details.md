# GET /zones/{zone_id}/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Health Check Details**
**Operation ID:** `health-checks-health-check-details`

Fetch a single configured health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | healthchecks_identifier | Yes |  |
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Health Check Details response. |
| 4XX | Health Check Details response failure. |

**Success Response Schema:**

[healthchecks_single_response](../schemas/healthchecks/healthchecks-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
