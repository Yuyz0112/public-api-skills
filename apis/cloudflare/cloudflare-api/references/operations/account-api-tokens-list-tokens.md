# GET /accounts/{account_id}/tokens

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**List Tokens**
**Operation ID:** `account-api-tokens-list-tokens`

List all Account Owned API tokens created for this account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Tokens response |
| 4XX | List Tokens response failure |

**Success Response Schema:**

[iam_collection_tokens_response](../schemas/iam/iam-collection-tokens-response.md)

## Security

- **api_token**
