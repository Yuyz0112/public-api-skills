# POST /zones/{zone_id}/healthchecks/preview

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Create Preview Health Check**
**Operation ID:** `health-checks-create-preview-health-check`

Create a new preview health check.

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
| 200 | Create Preview Health Check response. |
| 4XX | Create Preview Health Check response failure. |

**Success Response Schema:**

[healthchecks_single_response](../schemas/healthchecks/healthchecks-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
