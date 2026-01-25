# GET /user/tokens/{token_id}

**Resource:** [User API Tokens](../resources/User-API-Tokens.md)
**Token Details**
**Operation ID:** `user-api-tokens-token-details`

Get information about a specific token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
