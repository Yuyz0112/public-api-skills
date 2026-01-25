# GET /accounts/{account_id}/load_balancers/regions/{region_id}

**Resource:** [Load Balancer Regions](../resources/Load-Balancer-Regions.md)
**Get Region**
**Operation ID:** `load-balancer-regions-get-region`

Get a single region mapping.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `region_id` | path | load-balancing_region_code | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Region response. |
| 4XX | Get Region response failure. |

**Success Response Schema:**

[load-balancing_components-schemas-single_response](../schemas/load-balancing/load-balancing-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
