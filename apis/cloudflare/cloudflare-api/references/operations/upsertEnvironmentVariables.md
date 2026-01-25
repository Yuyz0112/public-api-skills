# PATCH /accounts/{account_id}/builds/triggers/{trigger_uuid}/environment_variables

**Resource:** [Environment Variables](../resources/Environment-Variables.md)
**Upsert environment variables**
**Operation ID:** `upsertEnvironmentVariables`

Create or update environment variables for a trigger

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_EnvironmentVariablesRequest](../schemas/builds/builds-EnvironmentVariablesRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Environment variables updated successfully |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
