# DELETE /zones/{zone_id}/healthchecks/preview/{healthcheck_id}

**Resource:** [Health Checks](../resources/Health-Checks.md)
**Delete Preview Health Check**
**Operation ID:** `health-checks-delete-preview-health-check`

Delete a health check.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `healthcheck_id` | path | healthchecks_identifier | Yes |  |
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Preview Health Check response. |
| 4XX | Delete Preview Health Check response failure. |

**Success Response Schema:**

[healthchecks_id_response](../schemas/healthchecks/healthchecks-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
