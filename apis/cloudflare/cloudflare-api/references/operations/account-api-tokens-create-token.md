# POST /accounts/{account_id}/tokens

**Resource:** [Account Owned API Tokens](../resources/Account-Owned-API-Tokens.md)
**Create Token**
**Operation ID:** `account-api-tokens-create-token`

Create a new Account Owned API token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | iam_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [iam_create_payload](../schemas/iam/iam-create-payload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Token response |
| 4XX | Create Token response failure |

**Success Response Schema:**

[iam_single_token_create_response](../schemas/iam/iam-single-token-create-response.md)

## Security

- **api_token**
