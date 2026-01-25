# PUT /accounts/{account_id}/tokens/{token_id}

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Update Token**
**Operation ID:** `account-api-tokens-update-token`

Update an existing token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |
| `token_id` | path | iam_token_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_token_body](../schemas/iam/iam-token-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Token response |
| 4XX | Update Token response failure |

**Success Response Schema:**

[iam_single_token_response](../schemas/iam/iam-single-token-response.md)

## Security

- **api_token**
