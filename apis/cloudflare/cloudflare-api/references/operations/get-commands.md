# GET /accounts/{account_id}/dex/commands

**Resource:** [DEX Remote Commands](../resources/DEX-Remote-Commands.md)
**List account commands**
**Operation ID:** `get-commands`

Retrieves a paginated list of commands issued to devices under the specified account, optionally filtered by time range, device, or other parameters

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |
| `page` | query | number | Yes | Page number for pagination |
| `per_page` | query | number | Yes | Number of results per page |
| `from` | query | string (date-time) | No | Start time for the query in ISO (RFC3339 - ISO 8601) format |
| `to` | query | string (date-time) | No | End time for the query in ISO (RFC3339 - ISO 8601) format |
| `device_id` | query | string | No | Unique identifier for a device |
| `user_email` | query | string | No | Email tied to the device |
| `command_type` | query | string | No | Optionally filter executed commands by command type |
| `status` | query | enum: PENDING_EXEC, PENDING_UPLOAD, SUCCESS... | No | Optionally filter executed commands by status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get commands response |
| 4XX | Get commands failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
