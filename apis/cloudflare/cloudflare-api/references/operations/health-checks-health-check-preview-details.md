# GET /zones/{zone_id}/healthchecks/preview/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Health Check Preview Details**
**Operation ID:** `health-checks-health-check-preview-details`

Fetch a single configured health check preview.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | healthchecks_identifier | Yes |  |
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Health Check Preview Details response. |
| 4XX | Health Check Preview Details response failure. |

**Success Response Schema:**

[healthchecks_single_response](../schemas/healthchecks/healthchecks-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
