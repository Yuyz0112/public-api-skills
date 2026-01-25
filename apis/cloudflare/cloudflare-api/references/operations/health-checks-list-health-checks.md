# GET /zones/{zone_id}/healthchecks

**Resource:** [Health Checks](../resources/Health-Checks.md)
**List Health Checks**
**Operation ID:** `health-checks-list-health-checks`

List configured health checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | healthchecks_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Health Checks response |
| 4XX | List Health Checks response failure. |

**Success Response Schema:**

[healthchecks_response_collection](../schemas/healthchecks/healthchecks-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
