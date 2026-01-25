# GET /accounts/{account_id}/load_balancers/preview/{preview_id}

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**Preview Result**
**Operation ID:** `account-load-balancer-monitors-preview-result`

Get the result of a previous preview operation using the provided preview_id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `preview_id` | path | load-balancing_schemas-preview_id | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Preview Result response. |
| 4XX | Preview Result response failure. |

**Success Response Schema:**

[load-balancing_preview_result_response](../schemas/load-balancing/load-balancing-preview-result-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
