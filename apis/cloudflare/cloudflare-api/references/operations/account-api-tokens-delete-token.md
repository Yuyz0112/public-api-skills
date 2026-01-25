# DELETE /accounts/{account_id}/tokens/{token_id}

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Delete Token**
**Operation ID:** `account-api-tokens-delete-token`

Destroy an Account Owned API token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `token_id` | path | iam_token_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Token response |
| 4XX | Delete Token response failure |

**Success Response Schema:**

[iam_api-response-single-id](../schemas/iam/iam-api-response-single-id.md)

## Security

- **api_token**
