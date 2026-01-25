# POST /accounts/{account_id}/builds/tokens

**Resource:** [Build Tokens](../resources/Build-Tokens.md)
**Create build token**
**Operation ID:** `createBuildToken`

Create a new build authentication token

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_CreateBuildTokenRequest](../schemas/builds/builds-CreateBuildTokenRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Build token created successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
