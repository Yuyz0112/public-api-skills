# GET /user/load_balancers/preview/{preview_id}

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**Preview Result**
**Operation ID:** `load-balancer-monitors-preview-result`

Get the result of a previous preview operation using the provided preview_id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `preview_id` | path | load-balancing_preview_id | Yes |  |

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
