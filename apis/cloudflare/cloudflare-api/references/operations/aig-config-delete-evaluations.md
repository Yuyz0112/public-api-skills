# DELETE /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/evaluations/{id}

**Resource:** [AI Gateway Evaluations](../resources/AI-Gateway-Evaluations.md)
**Delete a Evaluation**
**Operation ID:** `aig-config-delete-evaluations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the Object if it was successfully deleted |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
