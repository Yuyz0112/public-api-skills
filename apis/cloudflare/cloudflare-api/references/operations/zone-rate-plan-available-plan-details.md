# GET /zones/{zone_id}/available_plans/{plan_identifier}

**Resource:** [Zone Rate Plan](../resources/Zone-Rate-Plan.md)
**Available Plan Details**
**Operation ID:** `zone-rate-plan-available-plan-details`

Details of the available plan that the zone can subscribe to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `plan_identifier` | path | bill-subs-api_identifier | Yes |  |
| `zone_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Available Plan Details response |
| 4XX | Available Plan Details response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
