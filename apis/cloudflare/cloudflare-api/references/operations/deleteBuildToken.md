# DELETE /accounts/{account_id}/builds/tokens/{build_token_uuid}

**Resource:** [Build Tokens](../resources/Build-Tokens.md)
**Delete build token**
**Operation ID:** `deleteBuildToken`

Remove a build authentication token

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `build_token_uuid` | path | string (uuid) | Yes | Build token UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
