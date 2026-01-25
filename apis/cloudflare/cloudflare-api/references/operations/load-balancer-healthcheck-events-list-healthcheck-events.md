# GET /user/load_balancing_analytics/events

**Resource:** [Load Balancer Healthcheck Events](../resources/Load-Balancer-Healthcheck-Events.md)
**List Healthcheck Events**
**Operation ID:** `load-balancer-healthcheck-events-list-healthcheck-events`

List origin health changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `until` | query | load-balancing_until | No |  |
| `pool_name` | query | load-balancing_pool_name | No |  |
| `origin_healthy` | query | load-balancing_origin_healthy | No |  |
| `pool_id` | query | load-balancing_schemas-identifier | No |  |
| `since` | query | string (date-time) | No |  |
| `origin_name` | query | string | No |  |
| `pool_healthy` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Healthcheck Events response. |
| 4XX | List Healthcheck Events response failure. |

**Success Response Schema:**

[load-balancing_components-schemas-response_collection](../schemas/load-balancing/load-balancing-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
