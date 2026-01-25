# PUT /accounts/{account_id}/tokens/{token_id}/value

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Roll Token**
**Operation ID:** `account-api-tokens-roll-token`

Roll the Account Owned API token secret.

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
| 200 | Roll Token response |
| 4XX | Roll Token response failure |

**Success Response Schema:**

[iam_response_single_value](../schemas/iam/iam-response-single-value.md)

## Security

- **api_token**
