# PUT /accounts/{account_id}/builds/repos/connections

**Resource:** [Repository Connections](../resources/Repository-Connections.md)
**Create or update repository connection**
**Operation ID:** `upsertRepoConnection`

Upsert a repository connection for CI/CD integration

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_UpsertRepoConnectionRequest](../schemas/builds/builds-UpsertRepoConnectionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Repository connection upserted successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
