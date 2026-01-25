# GET /accounts/{account_id}/load_balancers/pools

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**List Pools**
**Operation ID:** `account-load-balancer-pools-list-pools`

List configured pools.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |
| `monitor` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Pools response. |
| 4XX | List Pools response failure. |

**Success Response Schema:**

[load-balancing_schemas-response_collection](../schemas/load-balancing/load-balancing-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
