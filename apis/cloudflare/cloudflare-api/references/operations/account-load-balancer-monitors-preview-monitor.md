# POST /accounts/{account_id}/load_balancers/monitors/{monitor_id}/preview

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**Preview Monitor**
**Operation ID:** `account-load-balancer-monitors-preview-monitor`

Preview pools using the specified monitor with provided monitor details. The returned preview_id can be used in the preview endpoint to retrieve the results.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_id` | path | load-balancing_identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Preview Monitor response. |
| 4XX | Preview Monitor response failure. |

**Success Response Schema:**

[load-balancing_preview_response](../schemas/load-balancing/load-balancing-preview-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
