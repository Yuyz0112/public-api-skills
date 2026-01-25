# POST /zones/{zone_id}/healthchecks

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Create Health Check**
**Operation ID:** `health-checks-create-health-check`

Create a new health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [healthchecks_query_healthcheck](../schemas/healthchecks/healthchecks-query-healthcheck.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Health Check response. |
| 4XX | Create Health Check response failure. |

**Success Response Schema:**

[healthchecks_single_response](../schemas/healthchecks/healthchecks-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
