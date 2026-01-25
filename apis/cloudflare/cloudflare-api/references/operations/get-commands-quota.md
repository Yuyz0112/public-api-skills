# GET /accounts/{account_id}/dex/commands/quota

**Resource:** [DEX Remote Commands](../resources/DEX-Remote-Commands.md)
**Returns account commands usage, quota, and reset time**
**Operation ID:** `get-commands-quota`

Retrieves the current quota usage and limits for device commands within a specific account, including the time when the quota will reset

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get commands quota response |
| 4XX | Get commands quota failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
