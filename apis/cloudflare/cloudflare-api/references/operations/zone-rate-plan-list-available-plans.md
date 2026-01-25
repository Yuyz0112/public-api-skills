# GET /zones/{zone_id}/available_plans

**Resource:** [Zone Rate Plan](../resources/Zone-Rate-Plan.md)
**List Available Plans**
**Operation ID:** `zone-rate-plan-list-available-plans`

Lists available plans the zone can subscribe to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Available Plans response |
| 4XX | List Available Plans response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
