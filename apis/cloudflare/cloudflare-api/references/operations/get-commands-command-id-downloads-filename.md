# GET /accounts/{account_id}/dex/commands/{command_id}/downloads/{filename}

**Resource:** [DEX Remote Commands](../resources/DEX-Remote-Commands.md)
**Download command output file**
**Operation ID:** `get-commands-command-id-downloads-filename`

Downloads artifacts for an executed command. Bulk downloads are not supported

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes | unique identifier linked to an account in the API request path |
| `command_id` | path | digital-experience-monitoring_command_id | Yes | Unique identifier for command |
| `filename` | path | string | Yes | The name of the file to be downloaded, including the `.zip` extension |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get command artifacts response |
| 4XX | Get downloaded commands failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**
