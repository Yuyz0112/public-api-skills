# GET /accounts/{account_id}/tokens/{token_id}

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Token Details**
**Operation ID:** `account-api-tokens-token-details`

Get information about a specific Account Owned API token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `token_id` | path | iam_token_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Token Details response |
| 4XX | Token Details response failure |

**Success Response Schema:**

[iam_single_token_response](../schemas/iam/iam-single-token-response.md)

## Security

- **api_token**
