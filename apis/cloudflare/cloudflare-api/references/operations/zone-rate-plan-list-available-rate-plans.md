# GET /zones/{zone_id}/available_rate_plans

**Resource:** [Zone Rate Plan](../resources/Zone-Rate-Plan.md)
**List Available Rate Plans**
**Operation ID:** `zone-rate-plan-list-available-rate-plans`

Lists all rate plans the zone can subscribe to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bill-subs-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Available Rate Plans response |
| 4XX | List Available Rate Plans response failure |

**Success Response Schema:**

[bill-subs-api_plan_response_collection](../schemas/bill-subs-api/bill-subs-api-plan-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
