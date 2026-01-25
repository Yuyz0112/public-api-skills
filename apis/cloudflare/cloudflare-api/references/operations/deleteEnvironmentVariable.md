# DELETE /accounts/{account_id}/builds/triggers/{trigger_uuid}/environment_variables/{environment_variable_key}

**Resource:** [Environment Variables](../resources/Environment-Variables.md)
**Delete environment variable**
**Operation ID:** `deleteEnvironmentVariable`

Remove a specific environment variable from a trigger

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environment_variable_key` | path | string | Yes | Environment variable key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
