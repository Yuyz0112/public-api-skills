# GET /accounts/{account_id}/load_balancers/regions

**Resource:** [Load Balancer Regions](../resources/Load-Balancer-Regions.md)
**List Regions**
**Operation ID:** `load-balancer-regions-list-regions`

List all region mappings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |
| `subdivision_code` | query | load-balancing_subdivision_code_a2 | No |  |
| `subdivision_code_a2` | query | load-balancing_subdivision_code_a2 | No |  |
| `country_code_a2` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Regions response. |
| 4XX | List Regions response failure. |

**Success Response Schema:**

[load-balancing_region_components-schemas-response_collection](../schemas/load-balancing/load-balancing-region-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
