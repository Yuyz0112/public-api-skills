# PATCH /zones/{zone_id}/healthchecks/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Patch Health Check**
**Operation ID:** `health-checks-patch-health-check`

Patch a configured health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | healthchecks_identifier | Yes |  |
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [healthchecks_query_healthcheck](../schemas/healthchecks/healthchecks-query-healthcheck.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Health Check response. |
| 4XX | Patch Health Check response failure. |

**Success Response Schema:**

[healthchecks_single_response](../schemas/healthchecks/healthchecks-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
