# GET /zones/{zone_id}/smart_shield/healthchecks

**Resource:** [Health Checks](../resources/Health-Checks.md)
**List Health Checks**
**Operation ID:** `smart-shield-list-health-checks`

List configured health checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | smartshield_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Health Checks response |
| 4XX | List Health Checks response failure. |

**Success Response Schema:**

[smartshield_response_collection](../schemas/smartshield/smartshield-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
